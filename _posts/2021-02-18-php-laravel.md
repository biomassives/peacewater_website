---
layout: post
title: a resilient technology stack
sub_heading: on using several apis
date: 
tags:
- php-laravel
- strapi
- mongodbatlas
- google sheets
- umati portal
- mongodb
- single ec2 apps
- simple is better
banner_image: ''
related_posts: []

---
> Laravel Cloud instance
>
>   via Digital Ocean:  
>
> Laravel local install low - Feb 18 2021 - Greg
>
>       75/75 [============================] 100%
>       - Installing doctrine/inflector (2.0.3): Extracting archive
>       
>       - Installing doctrine/lexer (1.2.1): Extracting archive
>     
>       - Installing symfony/polyfill-ctype (v1.22.1): Extracting archive
>     
>       - Installing webmozart/assert (1.9.1): Extracting archive
>     
>       - Installing dragonmantank/cron-expression (v3.1.0): Extracting archive
>     
>       - Installing symfony/polyfill-php80 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-mbstring (v1.22.1): Extracting archive
>     
>       - Installing symfony/var-dumper (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-intl-normalizer (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-grapheme (v1.22.1): Extracting archive
>     
>       - Installing symfony/string (v5.2.3): Extracting archive
>     
>       - Installing psr/container (1.0.0): Extracting archive
>     
>       - Installing symfony/service-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/polyfill-php73 (v1.22.1): Extracting archive
>     
>       - Installing symfony/console (v5.2.3): Extracting archive
>     
>       - Installing psr/log (1.1.3): Extracting archive
>     
>       - Installing monolog/monolog (2.2.0): Extracting archive
>     
>       - Installing voku/portable-ascii (1.5.6): Extracting archive
>     75/75 [============================] 100%      - Installing doctrine/inflector (2.0.3): Extracting archive
>       - Installing phpoption/phpoption (1.7.5): Extracting archive
>     
>       - Installing graham-campbell/result-type (v1.0.1): Extracting archive
>     
>       - Installing vlucas/phpdotenv (v5.3.0): Extracting archive
>     
>       - Installing symfony/css-selector (v5.2.3): Extracting archive
>     
>       - Installing tijsverkoyen/css-to-inline-styles (2.2.3): Extracting archive
>     
>       - Installing symfony/deprecation-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/routing (v5.2.3): Extracting archive
>     
>       - Installing symfony/process (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-php72 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-idn (v1.22.1): Extracting archive
>     
>       - Installing symfony/mime (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-foundation (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-client-contracts (v2.3.1): Extracting archive
>     
>       - Installing psr/event-dispatcher (1.0.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher (v5.2.3): Extracting archive
>     
>       - Installing symfony/error-handler (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-kernel (v5.2.3): Extracting archive
>     
>       - Installing symfony/finder (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-iconv (v1.22.1): Extracting archive
>     
>       - Installing egulias/email-validator (2.1.25): Extracting archive
>     
>       - Installing swiftmailer/swiftmailer (v6.2.5): Extracting archive
>     
>       - Installing ramsey/collection (1.1.3): Extracting archive
>     
>       - Installing brick/math (0.9.2): Extracting archive
>     
>       - Installing ramsey/uuid (4.1.1): Extracting archive
>     
>       - Installing psr/simple-cache (1.0.1): Extracting archive
>     
>       - Installing opis/closure (3.6.1): Extracting archive
>     
>       - Installing symfony/translation-contracts (v2.3.0): Extracting archive
>     
>       - Installing symfony/translation (v5.2.3): Extracting archive
>     
>       - Installing nesbot/carbon (2.45.1): Extracting archive
>     
>       - Installing league/mime-type-detection (1.7.0): Extracting archive
>     
>       - Installing league/flysystem (1.1.3): Extracting archive
>     
>       - Installing league/commonmark (1.5.7): Extracting archive
>     
>       - Installing laravel/framework (v8.28.1): Extracting archive
>     
>       - Installing filp/whoops (2.9.2): Extracting archive
>     
>       - Installing facade/ignition-contracts (1.0.2): Extracting archive
>     
>       - Installing facade/flare-client-php (1.4.0): Extracting archive
>     
>       - Installing facade/ignition (2.5.13): Extracting archive
>     
>       - Installing fakerphp/faker (v1.13.0): Extracting archive
>     
>       - Installing fideloper/proxy (4.4.1): Extracting archive
>     
>       - Installing asm89/stack-cors (v2.0.2): Extracting archive
>     
>       - Installing fruitcake/laravel-cors (v2.0.3): Extracting archive
>     
>       - Installing psr/http-message (1.0.1): Extracting archive
>     
>       - Installing psr/http-client (1.0.1): Extracting archive
>     
>       - Installing ralouphie/getallheaders (3.0.3): Extracting archive
>     
>       - Installing guzzlehttp/psr7 (1.7.0): Extracting archive
>     
>       - Installing guzzlehttp/promises (1.4.0): Extracting archive
>     
>       - Installing guzzlehttp/guzzle (7.2.0): Extracting archive
>     
>       - Installing laravel/sail (v1.3.1): Extracting archive
>     
>       - Installing nikic/php-parser (v4.10.4): Extracting archive
>     
>       - Installing dnoegel/php-xdg-base-dir (v0.1.1): Extracting archive
>     
>       - Installing psy/psysh (v0.10.6): Extracting archive
>     
>       - Installing laravel/tinker (v2.6.0): Extracting archive
>     
>       - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
>     
>       - Installing mockery/mockery (1.4.2): Extracting archive
>     
>       - Installing nunomaduro/collision (v5.3.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-common (2.2.0): Extracting archive
>     
>       - Installing phpdocumentor/type-resolver (1.4.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-docblock (5.2.2): Extracting archive
>     
>       - Installing sebastian/version (3.0.2): Extracting archive
>     
>       - Installing sebastian/type (2.3.1): Extracting archive
>     
>       - Installing sebastian/resource-operations (3.0.3): Extracting archive
>     
>       - Installing sebastian/recursion-context (4.0.4): Extracting archive
>     
>       - Installing sebastian/object-reflector (2.0.4): Extracting archive
>     
>       - Installing sebastian/object-enumerator (4.0.4): Extracting archive
>     
>       - Installing sebastian/global-state (5.0.2): Extracting archive
>     
>       - Installing sebastian/exporter (4.0.3): Extracting archive
>     
>       - Installing sebastian/environment (5.1.3): Extracting archive
>     
>       - Installing sebastian/diff (4.0.4): Extracting archive
>     
>       - Installing sebastian/comparator (4.0.6): Extracting archive
>     
>       - Installing sebastian/code-unit (1.0.8): Extracting archive
>     
>       - Installing sebastian/cli-parser (1.0.1): Extracting archive
>     
>       - Installing phpunit/php-timer (5.0.3): Extracting archive
>     
>       - Installing phpunit/php-text-template (2.0.4): Extracting archive
>     
>       - Inst75/75 \[============================\] 100%      - Installing doctrine/inflector (2.0.3): Extracting archive
>     
>       - Installing doctrine/lexer (1.2.1): Extracting archive
>     
>       - Installing symfony/polyfill-ctype (v1.22.1): Extracting archive
>     
>       - Installing webmozart/assert (1.9.1): Extracting archive
>     
>       - Installing dragonmantank/cron-expression (v3.1.0): Extracting archive
>     
>       - Installing symfony/polyfill-php80 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-mbstring (v1.22.1): Extracting archive
>     
>       - Installing symfony/var-dumper (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-intl-normalizer (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-grapheme (v1.22.1): Extracting archive
>     
>       - Installing symfony/string (v5.2.3): Extracting archive
>     
>       - Installing psr/container (1.0.0): Extracting archive
>     
>       - Installing symfony/service-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/polyfill-php73 (v1.22.1): Extracting archive
>     
>       - Installing symfony/console (v5.2.3): Extracting archive
>     
>       - Installing psr/log (1.1.3): Extracting archive
>     
>       - Installing monolog/monolog (2.2.0): Extracting archive
>     
>       - Installing voku/portable-ascii (1.5.6): Extracting archive
>     
>       - Installing phpoption/phpoption (1.7.5): Extracting archive
>     
>       - Installing graham-campbell/result-type (v1.0.1): Extracting archive
>     
>       - Installing vlucas/phpdotenv (v5.3.0): Extracting archive
>     
>       - Installing symfony/css-selector (v5.2.3): Extracting archive
>     
>       - Installing tijsverkoyen/css-to-inline-styles (2.2.3): Extracting archive
>     
>       - Installing symfony/deprecation-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/routing (v5.2.3): Extracting archive
>     
>       - Installing symfony/process (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-php72 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-idn (v1.22.1): Extracting archive
>     
>       - Installing symfony/mime (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-foundation (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-client-contracts (v2.3.1): Extracting archive
>     
>       - Installing psr/event-dispatcher (1.0.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher (v5.2.3): Extracting archive
>     
>       - Installing symfony/error-handler (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-kernel (v5.2.3): Extracting archive
>     
>       - Installing symfony/finder (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-iconv (v1.22.1): Extracting archive
>     
>       - Installing egulias/email-validator (2.1.25): Extracting archive
>     
>       - Installing swiftmailer/swiftmailer (v6.2.5): Extracting archive
>     
>       - Installing ramsey/collection (1.1.3): Extracting archive
>     
>       - Installing brick/math (0.9.2): Extracting archive
>     
>       - Installing ramsey/uuid (4.1.1): Extracting archive
>     
>       - Installing psr/simple-cache (1.0.1): Extracting archive
>     
>       - Installing opis/closure (3.6.1): Extracting archive
>     
>       - Installing symfony/translation-contracts (v2.3.0): Extracting archive
>     
>       - Installing symfony/translation (v5.2.3): Extracting archive
>     
>       - Installing nesbot/carbon (2.45.1): Extracting archive
>     
>       - Installing league/mime-type-detection (1.7.0): Extracting archive
>     
>       - Installing league/flysystem (1.1.3): Extracting archive
>     
>       - Installing league/commonmark (1.5.7): Extracting archive
>     
>       - Installing laravel/framework (v8.28.1): Extracting archive
>     
>       - Installing filp/whoops (2.9.2): Extracting archive
>     
>       - Installing facade/ignition-contracts (1.0.2): Extracting archive
>     
>       - Installing facade/flare-client-php (1.4.0): Extracting archive
>     
>       - Installing facade/ignition (2.5.13): Extracting archive
>     
>       - Installing fakerphp/faker (v1.13.0): Extracting archive
>     
>       - Installing fideloper/proxy (4.4.1): Extracting archive
>     
>       - Installing asm89/stack-cors (v2.0.2): Extracting archive
>     
>       - Installing fruitcake/laravel-cors (v2.0.3): Extracting archive
>     
>       - Installing psr/http-message (1.0.1): Extracting archive
>     
>       - Installing psr/http-client (1.0.1): Extracting archive
>     
>       - Installing ralouphie/getallheaders (3.0.3): Extracting archive
>     
>       - Installing guzzlehttp/psr7 (1.7.0): Extracting archive
>     
>       - Installing guzzlehttp/promises (1.4.0): Extracting archive
>     
>       - Installing guzzlehttp/guzzle (7.2.0): Extracting archive
>     
>       - Installing laravel/sail (v1.3.1): Extracting archive
>     
>       - Installing nikic/php-parser (v4.10.4): Extracting archive
>     
>       - Installing dnoegel/php-xdg-base-dir (v0.1.1): Extracting archive
>     
>       - Installing psy/psysh (v0.10.6): Extracting archive
>     
>       - Installing laravel/tinker (v2.6.0): Extracting archive
>     
>       - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
>     
>       - Installing mockery/mockery (1.4.2): Extracting archive
>     
>       - Installing nunomaduro/collision (v5.3.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-common (2.2.0): Extracting archive
>     
>       - Installing phpdocumentor/type-resolver (1.4.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-docblock (5.2.2): Extracting archive
>     
>       - Installing sebastian/version (3.0.2): Extracting archive
>     
>       - Installing sebastian/type (2.3.1): Extracting archive
>     
>       - Installing sebastian/resource-operations (3.0.3): Extracting archive
>     
>       - Installing sebastian/recursion-context (4.0.4): Extracting archive
>     
>       - Installing sebastian/object-reflector (2.0.4): Extracting archive
>     
>       - Installing sebastian/object-enumerator (4.0.4): Extracting archive
>     
>       - Installing sebastian/global-state (5.0.2): Extracting archive
>     
>       - Installing sebastian/exporter (4.0.3): Extracting archive
>     
>       - Installing sebastian/environment (5.1.3): Extracting archive
>     
>       - Installing sebastian/diff (4.0.4): Extracting archive
>     
>       - Installing sebastian/comparator (4.0.6): Extracting archive
>     
>       - Installing sebastian/code-unit (1.0.8): Extracting archive
>     
>       - Installing sebastian/cli-parser (1.0.1): Extracting archive
>     
>       - Installing phpunit/php-timer (5.0.3): Extracting archive
>     
>       - Installing phpunit/php-text-template (2.0.4): Extracting archive
>     
>       - Installing phpunit/php-invoker (3.1.1): Extracting archive
>     
>       - Installing phpunit/php-file-iterator (3.0.5): Extracting archive
>     
>       - Installing theseer/tokenizer (1.2.0): Extracting archive
>     
>       - Installing sebastian/lines-of-code (1.0.3): Extracting archive
>     
>       - Installing sebastian/complexity (2.0.2): Extracting archive
>     
>       - Installing sebastian/code-unit-reverse-lookup (2.0.3): Extracting archive
>     
>       - Installing phpunit/php-code-coverage (9.2.5): Extracting archive
>     
>       - Installing doctrine/instantiator (1.4.0): Extracting archive
>     
>       - Installing phpspec/prophecy (1.12.2): Extracting archive
>     
>       - Installing phar-io/version (3.0.4): Extracting archive
>     
>       - Installing phar-io/manifest (2.0.1): Extracting archive
>     
>       - Installing myclabs/deep-copy (1.10.2): Extracting archive
>     
>       - Installing phpunit/phpunit (9.5.2): Extracting archive75/75 \[============================\] 100%      - Installing doctrine/inflector (2.0.3): Extracting archive
>     
>       - Installing doctrine/lexer (1.2.1): Extracting archive
>     
>       - Installing symfony/polyfill-ctype (v1.22.1): Extracting archive
>     
>       - Installing webmozart/assert (1.9.1): Extracting archive
>     
>       - Installing dragonmantank/cron-expression (v3.1.0): Extracting archive
>     
>       - Installing symfony/polyfill-php80 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-mbstring (v1.22.1): Extracting archive
>     
>       - Installing symfony/var-dumper (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-intl-normalizer (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-grapheme (v1.22.1): Extracting archive
>     
>       - Installing symfony/string (v5.2.3): Extracting archive
>     
>       - Installing psr/container (1.0.0): Extracting archive
>     
>       - Installing symfony/service-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/polyfill-php73 (v1.22.1): Extracting archive
>     
>       - Installing symfony/console (v5.2.3): Extracting archive
>     
>       - Installing psr/log (1.1.3): Extracting archive
>     
>       - Installing monolog/monolog (2.2.0): Extracting archive
>     
>       - Installing voku/portable-ascii (1.5.6): Extracting archive
>     
>       - Installing phpoption/phpoption (1.7.5): Extracting archive
>     
>       - Installing graham-campbell/result-type (v1.0.1): Extracting archive
>     
>       - Installing vlucas/phpdotenv (v5.3.0): Extracting archive
>     
>       - Installing symfony/css-selector (v5.2.3): Extracting archive
>     
>       - Installing tijsverkoyen/css-to-inline-styles (2.2.3): Extracting archive
>     
>       - Installing symfony/deprecation-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/routing (v5.2.3): Extracting archive
>     
>       - Installing symfony/process (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-php72 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-idn (v1.22.1): Extracting archive
>     
>       - Installing symfony/mime (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-foundation (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-client-contracts (v2.3.1): Extracting archive
>     
>       - Installing psr/event-dispatcher (1.0.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher (v5.2.3): Extracting archive
>     
>       - Installing symfony/error-handler (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-kernel (v5.2.3): Extracting archive
>     
>       - Installing symfony/finder (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-iconv (v1.22.1): Extracting archive
>     
>       - Installing egulias/email-validator (2.1.25): Extracting archive
>     
>       - Installing swiftmailer/swiftmailer (v6.2.5): Extracting archive
>     
>       - Installing ramsey/collection (1.1.3): Extracting archive
>     
>       - Installing brick/math (0.9.2): Extracting archive
>     
>       - Installing ramsey/uuid (4.1.1): Extracting archive
>     
>       - Installing psr/simple-cache (1.0.1): Extracting archive
>     
>       - Installing opis/closure (3.6.1): Extracting archive
>     
>       - Installing symfony/translation-contracts (v2.3.0): Extracting archive
>     
>       - Installing symfony/translation (v5.2.3): Extracting archive
>     
>       - Installing nesbot/carbon (2.45.1): Extracting archive
>     
>       - Installing league/mime-type-detection (1.7.0): Extracting archive
>     
>       - Installing league/flysystem (1.1.3): Extracting archive
>     
>       - Installing league/commonmark (1.5.7): Extracting archive
>     
>       - Installing laravel/framework (v8.28.1): Extracting archive
>     
>       - Installing filp/whoops (2.9.2): Extracting archive
>     
>       - Installing facade/ignition-contracts (1.0.2): Extracting archive
>     
>       - Installing facade/flare-client-php (1.4.0): Extracting archive
>     
>       - Installing facade/ignition (2.5.13): Extracting archive
>     
>       - Installing fakerphp/faker (v1.13.0): Extracting archive
>     
>       - Installing fideloper/proxy (4.4.1): Extracting archive
>     
>       - Installing asm89/stack-cors (v2.0.2): Extracting archive
>     
>       - Installing fruitcake/laravel-cors (v2.0.3): Extracting archive
>     
>       - Installing psr/http-message (1.0.1): Extracting archive
>     
>       - Installing psr/http-client (1.0.1): Extracting archive
>     
>       - Installing ralouphie/getallheaders (3.0.3): Extracting archive
>     
>       - Installing guzzlehttp/psr7 (1.7.0): Extracting archive
>     
>       - Installing guzzlehttp/promises (1.4.0): Extracting archive
>     
>       - Installing guzzlehttp/guzzle (7.2.0): Extracting archive
>     
>       - Installing laravel/sail (v1.3.1): Extracting archive
>     
>       - Installing nikic/php-parser (v4.10.4): Extracting archive
>     
>       - Installing dnoegel/php-xdg-base-dir (v0.1.1): Extracting archive
>     
>       - Installing psy/psysh (v0.10.6): Extracting archive
>     
>       - Installing laravel/tinker (v2.6.0): Extracting archive
>     
>       - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
>     
>       - Installing mockery/mockery (1.4.2): Extracting archive
>     
>       - Installing nunomaduro/collision (v5.3.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-common (2.2.0): Extracting archive
>     
>       - Installing phpdocumentor/type-resolver (1.4.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-docblock (5.2.2): Extracting archive
>     
>       - Installing sebastian/version (3.0.2): Extracting archive
>     
>       - Installing sebastian/type (2.3.1): Extracting archive
>     
>       - Installing sebastian/resource-operations (3.0.3): Extracting archive
>     
>       - Installing sebastian/recursion-context (4.0.4): Extracting archive
>     
>       - Installing sebastian/object-reflector (2.0.4): Extracting archive
>     
>       - Installing sebastian/object-enumerator (4.0.4): Extracting archive
>     
>       - Installing sebastian/global-state (5.0.2): Extracting archive
>     
>       - Installing sebastian/exporter (4.0.3): Extracting archive
>     
>       - Installing sebastian/environment (5.1.3): Extracting archive
>     
>       - Installing sebastian/diff (4.0.4): Extracting archive
>     
>       - Installing sebastian/comparator (4.0.6): Extracting archive
>     
>       - Installing sebastian/code-unit (1.0.8): Extracting archive
>     
>       - Installing sebastian/cli-parser (1.0.1): Extracting archive
>     
>       - Installing phpunit/php-timer (5.0.3): Extracting archive
>     
>       - Installing phpunit/php-text-template (2.0.4): Extracting archive
>     
>       - Installing phpunit/php-invoker (3.1.1): Extracting archive
>     
>       - Installing phpunit/php-file-iterator (3.0.5): Extracting archive
>     
>       - Installing theseer/tokenizer (1.2.0): Extracting archive
>     
>       - Installing sebastian/lines-of-code (1.0.3): Extracting archive
>     
>       - Installing sebastian/complexity (2.0.2): Extracting archive
>     
>       - Installing sebastian/code-unit-reverse-lookup (2.0.3): Extracting archive
>     
>       - Installing phpunit/php-code-coverage (9.2.5): Extracting archive
>     
>       - Installing doctrine/instantiator (1.4.0): Extracting archive
>     
>       - Installing phpspec/prophecy (1.12.2): Extracting archive
>     
>       - Installing phar-io/version (3.0.4): Extracting archive
>     
>       - Installing phar-io/manifest (2.0.1): Extracting archive
>     
>       - Installing myclabs/deep-copy (1.10.2): Extracting archive
>     
>       - Installing phpunit/phpunit (9.5.2): Extracting archive75/75 \[============================\] 100%      - Installing doctrine/inflector (2.0.3): Extracting archive
>     
>       - Installing doctrine/lexer (1.2.1): Extracting archive
>     
>       - Installing symfony/polyfill-ctype (v1.22.1): Extracting archive
>     
>       - Installing webmozart/assert (1.9.1): Extracting archive
>     
>       - Installing dragonmantank/cron-expression (v3.1.0): Extracting archive
>     
>       - Installing symfony/polyfill-php80 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-mbstring (v1.22.1): Extracting archive
>     
>       - Installing symfony/var-dumper (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-intl-normalizer (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-grapheme (v1.22.1): Extracting archive
>     
>       - Installing symfony/string (v5.2.3): Extracting archive
>     
>       - Installing psr/container (1.0.0): Extracting archive
>     
>       - Installing symfony/service-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/polyfill-php73 (v1.22.1): Extracting archive
>     
>       - Installing symfony/console (v5.2.3): Extracting archive
>     
>       - Installing psr/log (1.1.3): Extracting archive
>     
>       - Installing monolog/monolog (2.2.0): Extracting archive
>     
>       - Installing voku/portable-ascii (1.5.6): Extracting archive
>     
>       - Installing phpoption/phpoption (1.7.5): Extracting archive
>     
>       - Installing graham-campbell/result-type (v1.0.1): Extracting archive
>     
>       - Installing vlucas/phpdotenv (v5.3.0): Extracting archive
>     
>       - Installing symfony/css-selector (v5.2.3): Extracting archive
>     
>       - Installing tijsverkoyen/css-to-inline-styles (2.2.3): Extracting archive
>     
>       - Installing symfony/deprecation-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/routing (v5.2.3): Extracting archive
>     
>       - Installing symfony/process (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-php72 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-idn (v1.22.1): Extracting archive
>     
>       - Installing symfony/mime (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-foundation (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-client-contracts (v2.3.1): Extracting archive
>     
>       - Installing psr/event-dispatcher (1.0.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher (v5.2.3): Extracting archive
>     
>       - Installing symfony/error-handler (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-kernel (v5.2.3): Extracting archive
>     
>       - Installing symfony/finder (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-iconv (v1.22.1): Extracting archive
>     
>       - Installing egulias/email-validator (2.1.25): Extracting archive
>     
>       - Installing swiftmailer/swiftmailer (v6.2.5): Extracting archive
>     
>       - Installing ramsey/collection (1.1.3): Extracting archive
>     
>       - Installing brick/math (0.9.2): Extracting archive
>     
>       - Installing ramsey/uuid (4.1.1): Extracting archive
>     
>       - Installing psr/simple-cache (1.0.1): Extracting archive
>     
>       - Installing opis/closure (3.6.1): Extracting archive
>     
>       - Installing symfony/translation-contracts (v2.3.0): Extracting archive
>     
>       - Installing symfony/translation (v5.2.3): Extracting archive
>     
>       - Installing nesbot/carbon (2.45.1): Extracting archive
>     
>       - Installing league/mime-type-detection (1.7.0): Extracting archive
>     
>       - Installing league/flysystem (1.1.3): Extracting archive
>     
>       - Installing league/commonmark (1.5.7): Extracting archive
>     
>       - Installing laravel/framework (v8.28.1): Extracting archive
>     
>       - Installing filp/whoops (2.9.2): Extracting archive
>     
>       - Installing facade/ignition-contracts (1.0.2): Extracting archive
>     
>       - Installing facade/flare-client-php (1.4.0): Extracting archive
>     
>       - Installing facade/ignition (2.5.13): Extracting archive
>     
>       - Installing fakerphp/faker (v1.13.0): Extracting archive
>     
>       - Installing fideloper/proxy (4.4.1): Extracting archive
>     
>       - Installing asm89/stack-cors (v2.0.2): Extracting archive
>     
>       - Installing fruitcake/laravel-cors (v2.0.3): Extracting archive
>     
>       - Installing psr/http-message (1.0.1): Extracting archive
>     
>       - Installing psr/http-client (1.0.1): Extracting archive
>     
>       - Installing ralouphie/getallheaders (3.0.3): Extracting archive
>     
>       - Installing guzzlehttp/psr7 (1.7.0): Extracting archive
>     
>       - Installing guzzlehttp/promises (1.4.0): Extracting archive
>     
>       - Installing guzzlehttp/guzzle (7.2.0): Extracting archive
>     
>       - Installing laravel/sail (v1.3.1): Extracting archive
>     
>       - Installing nikic/php-parser (v4.10.4): Extracting archive
>     
>       - Installing dnoegel/php-xdg-base-dir (v0.1.1): Extracting archive
>     
>       - Installing psy/psysh (v0.10.6): Extracting archive
>     
>       - Installing laravel/tinker (v2.6.0): Extracting archive
>     
>       - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
>     
>       - Installing mockery/mockery (1.4.2): Extracting archive
>     
>       - Installing nunomaduro/collision (v5.3.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-common (2.2.0): Extracting archive
>     
>       - Installing phpdocumentor/type-resolver (1.4.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-docblock (5.2.2): Extracting archive
>     
>       - Installing sebastian/version (3.0.2): Extracting archive
>     
>       - Installing sebastian/type (2.3.1): Extracting archive
>     
>       - Installing sebastian/resource-operations (3.0.3): Extracting archive
>     
>       - Installing sebastian/recursion-context (4.0.4): Extracting archive
>     
>       - Installing sebastian/object-reflector (2.0.4): Extracting archive
>     
>       - Installing sebastian/object-enumerator (4.0.4): Extracting archive
>     
>       - Installing sebastian/global-state (5.0.2): Extracting archive
>     
>       - Installing sebastian/exporter (4.0.3): Extracting archive
>     
>       - Installing sebastian/environment (5.1.3): Extracting archive
>     
>       - Installing sebastian/diff (4.0.4): Extracting archive
>     
>       - Installing sebastian/comparator (4.0.6): Extracting archive
>     
>       - Installing sebastian/code-unit (1.0.8): Extracting archive
>     
>       - Installing sebastian/cli-parser (1.0.1): Extracting archive
>     
>       - Installing phpunit/php-timer (5.0.3): Extracting archive
>     
>       - Installing phpunit/php-text-template (2.0.4): Extracting archive
>     
>       - Installing phpunit/php-invoker (3.1.1): Extracting archive
>     
>       - Installing phpunit/php-file-iterator (3.0.5): Extracting archive
>     
>       - Installing theseer/tokenizer (1.2.0): Extracting archive
>     
>       - Installing sebastian/lines-of-code (1.0.3): Extracting archive
>     
>       - Installing sebastian/complexity (2.0.2): Extracting archive
>     
>       - Installing sebastian/code-unit-reverse-lookup (2.0.3): Extracting archive
>     
>       - Installing phpunit/php-code-coverage (9.2.5): Extracting archive
>     
>       - Installing doctrine/instantiator (1.4.0): Extracting archive
>     
>       - Installing phpspec/prophecy (1.12.2): Extracting archive
>     
>       - Installing phar-io/version (3.0.4): Extracting archive
>     
>       - Installing phar-io/manifest (2.0.1): Extracting archive
>     
>       - Installing myclabs/deep-copy (1.10.2): Extracting archive
>     
>       - Installing phpunit/phpunit (9.5.2): Extracting archive75/75 \[============================\] 100%      - Installing doctrine/inflector (2.0.3): Extracting archive
>     
>       - Installing doctrine/lexer (1.2.1): Extracting archive
>     
>       - Installing symfony/polyfill-ctype (v1.22.1): Extracting archive
>     
>       - Installing webmozart/assert (1.9.1): Extracting archive
>     
>       - Installing dragonmantank/cron-expression (v3.1.0): Extracting archive
>     
>       - Installing symfony/polyfill-php80 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-mbstring (v1.22.1): Extracting archive
>     
>       - Installing symfony/var-dumper (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-intl-normalizer (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-grapheme (v1.22.1): Extracting archive
>     
>       - Installing symfony/string (v5.2.3): Extracting archive
>     
>       - Installing psr/container (1.0.0): Extracting archive
>     
>       - Installing symfony/service-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/polyfill-php73 (v1.22.1): Extracting archive
>     
>       - Installing symfony/console (v5.2.3): Extracting archive
>     
>       - Installing psr/log (1.1.3): Extracting archive
>     
>       - Installing monolog/monolog (2.2.0): Extracting archive
>     
>       - Installing voku/portable-ascii (1.5.6): Extracting archive
>     
>       - Installing phpoption/phpoption (1.7.5): Extracting archive
>     
>       - Installing graham-campbell/result-type (v1.0.1): Extracting archive
>     
>       - Installing vlucas/phpdotenv (v5.3.0): Extracting archive
>     
>       - Installing symfony/css-selector (v5.2.3): Extracting archive
>     
>       - Installing tijsverkoyen/css-to-inline-styles (2.2.3): Extracting archive
>     
>       - Installing symfony/deprecation-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/routing (v5.2.3): Extracting archive
>     
>       - Installing symfony/process (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-php72 (v1.22.1): Extracting archive
>     
>       - Installing symfony/polyfill-intl-idn (v1.22.1): Extracting archive
>     
>       - Installing symfony/mime (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-foundation (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-client-contracts (v2.3.1): Extracting archive
>     
>       - Installing psr/event-dispatcher (1.0.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher-contracts (v2.2.0): Extracting archive
>     
>       - Installing symfony/event-dispatcher (v5.2.3): Extracting archive
>     
>       - Installing symfony/error-handler (v5.2.3): Extracting archive
>     
>       - Installing symfony/http-kernel (v5.2.3): Extracting archive
>     
>       - Installing symfony/finder (v5.2.3): Extracting archive
>     
>       - Installing symfony/polyfill-iconv (v1.22.1): Extracting archive
>     
>       - Installing egulias/email-validator (2.1.25): Extracting archive
>     
>       - Installing swiftmailer/swiftmailer (v6.2.5): Extracting archive
>     
>       - Installing ramsey/collection (1.1.3): Extracting archive
>     
>       - Installing brick/math (0.9.2): Extracting archive
>     
>       - Installing ramsey/uuid (4.1.1): Extracting archive
>     
>       - Installing psr/simple-cache (1.0.1): Extracting archive
>     
>       - Installing opis/closure (3.6.1): Extracting archive
>     
>       - Installing symfony/translation-contracts (v2.3.0): Extracting archive
>     
>       - Installing symfony/translation (v5.2.3): Extracting archive
>     
>       - Installing nesbot/carbon (2.45.1): Extracting archive
>     
>       - Installing league/mime-type-detection (1.7.0): Extracting archive
>     
>       - Installing league/flysystem (1.1.3): Extracting archive
>     
>       - Installing league/commonmark (1.5.7): Extracting archive
>     
>       - Installing laravel/framework (v8.28.1): Extracting archive
>     
>       - Installing filp/whoops (2.9.2): Extracting archive
>     
>       - Installing facade/ignition-contracts (1.0.2): Extracting archive
>     
>       - Installing facade/flare-client-php (1.4.0): Extracting archive
>     
>       - Installing facade/ignition (2.5.13): Extracting archive
>     
>       - Installing fakerphp/faker (v1.13.0): Extracting archive
>     
>       - Installing fideloper/proxy (4.4.1): Extracting archive
>     
>       - Installing asm89/stack-cors (v2.0.2): Extracting archive
>     
>       - Installing fruitcake/laravel-cors (v2.0.3): Extracting archive
>     
>       - Installing psr/http-message (1.0.1): Extracting archive
>     
>       - Installing psr/http-client (1.0.1): Extracting archive
>     
>       - Installing ralouphie/getallheaders (3.0.3): Extracting archive
>     
>       - Installing guzzlehttp/psr7 (1.7.0): Extracting archive
>     
>       - Installing guzzlehttp/promises (1.4.0): Extracting archive
>     
>       - Installing guzzlehttp/guzzle (7.2.0): Extracting archive
>     
>       - Installing laravel/sail (v1.3.1): Extracting archive
>     
>       - Installing nikic/php-parser (v4.10.4): Extracting archive
>     
>       - Installing dnoegel/php-xdg-base-dir (v0.1.1): Extracting archive
>     
>       - Installing psy/psysh (v0.10.6): Extracting archive
>     
>       - Installing laravel/tinker (v2.6.0): Extracting archive
>     
>       - Installing hamcrest/hamcrest-php (v2.0.1): Extracting archive
>     
>       - Installing mockery/mockery (1.4.2): Extracting archive
>     
>       - Installing nunomaduro/collision (v5.3.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-common (2.2.0): Extracting archive
>     
>       - Installing phpdocumentor/type-resolver (1.4.0): Extracting archive
>     
>       - Installing phpdocumentor/reflection-docblock (5.2.2): Extracting archive
>     
>       - Installing sebastian/version (3.0.2): Extracting archive
>     
>       - Installing sebastian/type (2.3.1): Extracting archive
>     
>       - Installing sebastian/resource-operations (3.0.3): Extracting archive
>     
>       - Installing sebastian/recursion-context (4.0.4): Extracting archive
>     
>       - Installing sebastian/object-reflector (2.0.4): Extracting archive
>     
>       - Installing sebastian/object-enumerator (4.0.4): Extracting archive
>     
>       - Installing sebastian/global-state (5.0.2): Extracting archive
>     
>       - Installing sebastian/exporter (4.0.3): Extracting archive
>     
>       - Installing sebastian/environment (5.1.3): Extracting archive
>     
>       - Installing sebastian/diff (4.0.4): Extracting archive
>     
>       - Installing sebastian/comparator (4.0.6): Extracting archive
>     
>       - Installing sebastian/code-unit (1.0.8): Extracting archive
>     
>       - Installing sebastian/cli-parser (1.0.1): Extracting archive
>     
>       - Installing phpunit/php-timer (5.0.3): Extracting archive
>     
>       - Installing phpunit/php-text-template (2.0.4): Extracting archive
>     
>       - Installing phpunit/php-invoker (3.1.1): Extracting archive
>     
>       - Installing phpunit/php-file-iterator (3.0.5): Extracting archive
>     
>       - Installing theseer/tokenizer (1.2.0): Extracting archive
>     
>       - Installing sebastian/lines-of-code (1.0.3): Extracting archive
>     
>       - Installing sebastian/complexity (2.0.2): Extracting archive
>     
>       - Installing sebastian/code-unit-reverse-lookup (2.0.3): Extracting archive
>     
>       - Installing phpunit/php-code-coverage (9.2.5): Extracting archive
>     
>       - Installing doctrine/instantiator (1.4.0): Extracting archive
>     
>       - Installing phpspec/prophecy (1.12.2): Extracting archive
>     
>       - Installing phar-io/version (3.0.4): Extracting archive
>     
>       - Installing phar-io/manifest (2.0.1): Extracting archive
>     
>       - Installing myclabs/deep-copy (1.10.2): Extracting archive
>     
>       - Installing phpunit/phpunit (9.5.2): Extracting archivealling phpunit/php-invoker (3.1.1): Extracting archive
>     
>       - Installing phpunit/php-file-iterator (3.0.5): Extracting archive
>     
>       - Installing theseer/tokenizer (1.2.0): Extracting archive
>     
>       - Installing sebastian/lines-of-code (1.0.3): Extracting archive
>     
>       - Installing sebastian/complexity (2.0.2): Extracting archive
>     
>       - Installing sebastian/code-unit-reverse-lookup (2.0.3): Extracting archive
>     
>       - Installing phpunit/php-code-coverage (9.2.5): Extracting archive
>     
>       - Installing doctrine/instantiator (1.4.0): Extracting archive
>     
>       - Installing phpspec/prophecy (1.12.2): Extracting archive
>     
>       - Installing phar-io/version (3.0.4): Extracting archive
>     
>       - Installing phar-io/manifest (2.0.1): Extracting archive
>     
>       - Installing myclabs/deep-copy (1.10.2): Extracting archive
>     
>       - Installing phpunit/phpunit (9.5.2): Extracting archive