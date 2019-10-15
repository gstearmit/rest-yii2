
# https://github.com/yiisoft/yii2/blob/master/framework/UPGRADE.md#upgrade-from-yii-2012
composer self-update
composer global require "fxp/composer-asset-plugin:^1.4.1" --no-plugins
composer require "yiisoft/yii2:~2.0.10" --update-with-dependencies
