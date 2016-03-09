title: Install phpMyAdmin onto Ubuntu...
link: http://www.flamelily.co.uk/2012/08/install-phpmyadmin-onto-ubuntu/
author: admin
description: 
post_id: 338
created: 2012/08/06 14:08:44
created_gmt: 2012/08/06 13:08:44
comment_status: open
post_name: install-phpmyadmin-onto-ubuntu
status: publish
post_type: post

# Install phpMyAdmin onto Ubuntu...

From console: 
    
    
    sudo apt-get install phpmyadmin

This must be done from the console as some questions will need to be answered. Use Putty to login into your server and run the command above. Once phpMyAdmin is installed point your browser to http://your server ip address/phpmyadmin to start using it. You should be able to login using any users you've setup in MySQL. If no users have been setup, use _admin_ with no password to login. **To remove Wordpress posts revisions from your database** Just in case you are wondering how post revision works, whenever a post is edited, **a new row** will be created in wp_posts table. Hence if your posts or pages got edited 10 times, you will have 10 new rows in wp_posts table. In no** time** your wp_posts table will be filling up and the post ID will be grow. To turn off this feature, add this following code to **wp-config.php**: 
    
    
    define('WP_POST_REVISIONS', false);

You can also delete all post revisions by running this query on your Wordpress database in phpMyAdmin: 
    
    
    DELETE a,b,c   
     
    FROM wp_posts a    
    
    LEFT JOIN wp_term_relationships b ON (a.ID = b.object_id)    
    
    LEFT JOIN wp_postmeta c ON (a.ID = c.post_id)   
     
    WHERE a.post_type = 'revision'

Be sure to backup your database first before performing any queries in phpMyAdmin.