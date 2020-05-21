# librenms-templates

Email templates for LibreNMS, HTTP format for graph inclusion - HTTP emails must be ENABLED in LibreNMS global settings for templates to work.

ALERT/RECOVERY title formatting can be found at bottom of template in comments, just copy+paste to title contents when creating template in LibreNMS.

---

### Configuring Graphs:
Any instance(s) of 'SERVER' in template must be replaced with your corresponding FQDN, i.e. if your LibreNMS server is @ www.yourLibreNMS.com then all \<img src\> fields should be manually updated to resemble "http://www.yourLibreNMS.com/graph.php?..."
