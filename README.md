# laravel-on-nginx-fpm

This repository contains configurations for Laravel Optimizied on Nginx PHP-FPM

An important note that these configurations are not the exact values you would like your server to work in. But the comments above each variable contains the ways to calculate(if applicable) the value to be set.

The initial focus should be making sure the application is efficient enough and not having any memory exhausting stuff going on.

However, making sure you server is configured properly is important. You may have bigger server but the configurations are not optimized to use to its full potential.

Make sure you obeserve these values against a benchmark and specific stress tests using tools like JMeter or Siege(my personal fav).
