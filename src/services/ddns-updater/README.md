Constraint:
User 1000:1000 shoud be granted write access to ${APP_DATA_DIRECTORY}/ddns_updater/ 
==> 
sudo chown 1000:1000 ${APP_DATA_DIRECTORY}/ddns_updater
and then 
chmod u+w ${APP_DATA_DIRECTORY}/ddns_updater
