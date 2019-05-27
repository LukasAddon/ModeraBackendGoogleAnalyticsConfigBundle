# ModeraBackendGoogleAnalyticsConfigBundle

[![Build Status](https://travis-ci.org/modera/ModeraBackendGoogleAnalyticsConfigBundle.svg?branch=master)](https://travis-ci.org/modera/ModeraBackendGoogleAnalyticsConfigBundle)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/modera/ModeraBackendGoogleAnalyticsConfigBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/modera/ModeraBackendGoogleAnalyticsConfigBundle/?branch=master)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/545d2f81-38f7-4936-b231-78fcdce7b400/mini.png)](https://insight.sensiolabs.com/projects/545d2f81-38f7-4936-b231-78fcdce7b400)

Contributes a section to Settings page that allows to configure Google Analytics.

## Installation

Add a dependency to your composer.json by running:

    composer require modera/backend-google-analytics-config-bundle

You don't have to manually update your AppKernel class if you have `modera/module-bundle` bundle installed already, otherwise
you need to add this to your AppKernel:

    new \Modera\BackendGoogleAnalyticsConfigBundle\ModeraBackendGoogleAnalyticsConfigBundle(),

## Documentation

You can use "modera_config_value" Twig function to fetch values of your configuration properties right from templates
(for this you need to use v1.1.0 of `modera/config-bundle` bundle).

## Licensing

This bundle is under the MIT license. See the complete license in the bundle:
Resources/meta/LICENSE