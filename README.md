#### WordPress boilerplate focused on speed, security, and lightweight code that includes several Must Use plugins and also supports Composer (Packagist).

[![GitHub stars](https://img.shields.io/github/stars/littlebizzy/wplite.svg?style=social&logo=github&label=Star)](https://github.com/littlebizzy/wplite/stargazers) [![GitHub forks](https://img.shields.io/github/forks/littlebizzy/wplite.svg?style=social&logo=github&label=Fork)](https://github.com/littlebizzy/wplite/fork) [![GitHub watchers](https://img.shields.io/github/watchers/littlebizzy/wplite.svg?style=social&logo=github&label=Watch)](https://github.com/littlebizzy/wplite/watchers)

Place inside `/var/www/html/` when installing via [SlickStack](https://slickstack.io) on a LEMP (Nginx) server:

    composer.json
    index.php
    wp-config.php
    /wp-content/mu-plugins/
    /wp-content/mu-plugins/cf-littlebizzy/
    /wp-content/mu-plugins/delete-expired-transients-littlebizzy/
    /wp-content/mu-plugins/disable-embeds-littlebizzy/
    /wp-content/mu-plugins/disable-emojis-littlebizzy/
    /wp-content/mu-plugins/disable-empty-trash-littlebizzy/
    /wp-content/mu-plugins/disable-image-compression-littlebizzy/
    /wp-content/mu-plugins/disable-xml-rpc-littlebizzy/
    /wp-content/mu-plugins/error-log-monitor-littlebizzy/
    /wp-content/mu-plugins/force-strong-hashing-littlebizzy/
    /wp-content/mu-plugins/header-cleanup-littlebizzy/
    /wp-content/mu-plugins/nginx-cache-littlebizzy/
    /wp-content/mu-plugins/remove-query-strings-littlebizzy/
    /wp-content/mu-plugins/server-status-littlebizzy/
    /wp-content/mu-plugins/virtual-robotstxt-littlebizzy/
    /wp-content/plugins/
    /wp-content/themes/
    /wp-content/uploads/

List of defined constants supported by wplite:

    // Remove Query Strings
    define('REMOVE_QUERY_STRING_ARGS', 'v,ver,version');
    
    // Delete Expired Transients
    define('DELETE_EXPIRED_TRANSIENTS_HOURS', '6');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_EXECUTION_TIME', '10');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_BATCH_RECORDS', '50');
    
    // Server Status
    define('SVRSTS_DISPLAY', 'grid, widefat');

❤ from [LittleBizzy](https://www.littlebizzy.com) | License: [GPLv3](https://www.gnu.org/licenses/gpl-3.0)
