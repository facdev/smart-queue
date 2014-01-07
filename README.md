smart-queue
===========
Система Электроных Очередей





# Installation

### PEAR

	$ pear config-set auto_discover 1
	$ pear channel-discover components.ez.no
	$ pear install ezc/base
	$ pear install ezc/database


### Composer

installer:

	$ curl -sS https://getcomposer.org/installer | php && mv composer.phar /usr/local/bin/composer


require:

	{
		"require": {
			"php-console/php-console":"dev-master",
			"phpunit/phpunit": "3.7.*",
			"psr/log": "dev-master",
			"mustangostang/spyc":"dev-master",
			"pimple/pimple": "1.*"
		}
	}


### libraries


#### A JavaScript optimizer

The [Closure Compiler](https://developers.google.com/closure/compiler/) compiles JavaScript into compact, high-performance code. 
Pre-built Closure binaries can be found at [here](http://code.google.com/p/closure-compiler/downloads/list)

#### Smarty 3.1.15

Please refer to the online [documentation](http://www.smarty.net/documentation) for all specific changes.


#### FirePHPCore

See <http://www.firephp.org>


#### PHP Lib

 - **Psr/Log**		<https://github.com/php-fig/log.git>
 - **PhpConsole** 	<https://github.com/barbushin/php-console.git>
 - **JSON** 		<http://pear.php.net/pepr/pepr-proposal-show.php?id=198>
 - **JavaScript** 	<http://www.yiiframework.com>
 - **VarDumper** 	<http://www.yiiframework.com>
 - **PasswordHash** <http://www.openwall.com/phpass/>
 - **Pimple** 		<https://github.com/fabpot/Pimple.git>
 - **Spyc** 		<https://github.com/mustangostang/spyc.git>





## License

  MIT
