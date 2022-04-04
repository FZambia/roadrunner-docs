# Table of Contents
RoadRunner is an open-source (MIT licensed), high-performance PHP application server, load balancer, and process manager.

![CI](https://github.com/spiral/roadrunner-docs/workflows/CI/badge.svg)

* Introduction
    * [What is it?](intro/about.md)
    * [Features](intro/features.md)
    * [Installation](intro/install.md)
    * [Configuration](intro/config.md)
    * [LICENSE](license.md)
* PHP Workers
    * [Worker](php/worker.md)
    * [Environment](php/environment.md)
    * [Developer Mode](php/developer.md)
    * [Error Handling](php/error-handling.md)
    * [Restarting](php/restarting.md)
    * [Embedded Monitoring](php/limit.md)
    * [RPC to App Server](php/rpc.md)
    * [Caveats](php/caveats.md)
    * [Debugging](php/debugging.md)
* App Server
    * [CLI Commands](beep-beep/cli.md)
    * [Production Usage](beep-beep/production.md)
    * [Writing a RR systemd unit file](beep-beep/systemd.md)
    * [Auto-Reloading](beep-beep/reload.md)
    * [Prometheus Metrics](beep-beep/metrics.md)
    * [Healthcheck](beep-beep/health.md)
    * [Building a Server](beep-beep/build.md)
    * [RPC](beep-beep/rpc.md)
    * [Write a Service](beep-beep/service.md)
    * [Overriding HTTP error codes](beep-beep/http-error-codes.md)
* HTTPs and HTTP/2
    * [HTTPs and HTTP/2](http/https.md)
    * [Headers](http/headers.md)
    * [Middleware](http/middleware.md)
* Integrations
    * [CakePHP](integration/cake.md)
    * [Laravel](integration/laravel.md)
    * [Slim](integration/slim.md)
    * [Spiral Framework](integration/spiral.md)
    * [Symfony Framework](integration/symfony.md)
    * [Symlex Framework](integration/symlex.md)
    * [Ubiquity Framework](integration/ubiquity.md)
    * [Zend Expressive](https://github.com/sergey-telpuk/roadrunner-zend-expressive-integration)
    * [Yii2 and Yii3](integration/yii.md)
    * [Phalcon3 and Phalcon4](integration/phalcon.md)
    * [**All Composer Libraries**](https://packagist.org/packages/spiral/roadrunner/dependents)
* Docker
    * [Ports and Containers](docker/ports.md)
    * [Available Images](docker/images.md)
* As Library
    * [Event Listeners](library/event-listeners.md)
    * [Standalone Usage](library/standalone-usage.md)
    * [AWS Lambda](library/aws-lambda.md)
