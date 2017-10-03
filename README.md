# network-connected-logger

# Setup
execute `crontab -e` and edit

```cron
*/5 * * * * PATH="/bin/:/sbin/:/usr/sbin:$PATH" $FULL_PATH/network-connected-logger/network-connected-logger
```
