#Drupal Basic Set-up

##New project set-up
<ul>
<li>clone project from git repository</li></ul>
 <code>git clone https://github.com/indrajith-kb/drupal_basic_setup.git</code>
 <br/>
 
 <ul><li>configure the db connection <a href="https://www.drupal.org/docs/8/api/database-api/database-configuration"> click here</a></li></ul>
 
 <ul><li>Export db from dev </li></ul>
 <code>drush sql-dump > /tmp/dbname.sql</code>
 
 <ul><li>import db to ur local</li></ul>
 <code>mysql -uusername -ppasswoed dbname < dbname.sql </code>
 
 <u>some short-cut for db updates</u>
 <ul><li><code>drush sql-sync @dev @local </code></li></ul>
 
 
