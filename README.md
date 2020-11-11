# aws-amplify-flutter-snippet README

Over 40 code snippets for [AWS Amplify Flutter](https://docs.amplify.aws/lib/q/platform/flutter).
This extension for VSCode contains over 40 code snippets for the AWS Amplify Flutter.The code snippets are taken from the latest official documentation and cover the following topics:
* Authentication
* Initializing a new AWS Amplify project in Flutter
* Analytics
* Dependencies(YAML)
* Storage



## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

## Init project

| command        | description         | 
| ------------- |:-------------:|
| import_amplify_packages_flutter      | import amplify packages |
| init_blank_app_amplify_flutter   |  Add the following code to your application’s root Stateful Widget, for a blank Flutter app    |

## Dependencies

| command        | description         | 
| ------------- |:-------------:|
| add_all_dependencies_amplify_flutter      | add all necessary dependencies |
| add_analytics_dependencies_amplify_flutter   |  add analytics dependencies    |
| add_storage_dependencies_amplify_flutter      | add storage dependencies  |
| add_authentication_dependencies_amplify_flutter   |  add authentication dependencies     |

## Analytics

| command        | description         | 
| ------------- |:-------------:|
| init_analytics_amplify_flutter      | Add the Auth and Analytics plugin, along with any other plugins you may have added as described in the Prerequisites section |
| init_blank_app_amplify_flutter   |  Add the Auth and Analytics plugin, along with any other plugins you may have added as described in the Prerequisites section    |
| check_configuration_analytics_amplify_flutter      | check that the amplifyconfiguration.dart file generated in the project setup is included and sent to Amplify.configure |
| record_event_amplify_flutter   |  The Amplify analytics plugin also makes it easy to record custom events within the app. The plugin handles retry logic in the event the device looses network connectivity and automatically batches requests to reduce network bandwidth    |
| flush_auto_event_amplify_flutter    | Events have default configuration to flush out to the network every 30 seconds. If you would like to change this, update amplifyconfiguration.json with the value in milliseconds you would like for autoFlushEventsInterval. This configuration will flush events every 10 seconds |
| flush_manually_amplify_flutter   |  manually flush    |
| register_global_property_amplify_flutter      | register global properties which will be sent along with all invocations of Amplify.Analytics.recordEvent |
| unregister_global_property_amplify_flutter  |  unregister a global property   |
| disable_analytics_amplify_flutter      | disable analytics in amplifys |
| enable_analytics_amplify_flutter   |  enable analytics in amplify   |
| identify_user_analytics_amplify_flutter      | This call sends information that you have specified about a user to Amazon Pinpoint. This could be for an unauthenticated (guest) or an authenticated user.You can get the current user’s ID from the Amplify Auth category as shown below. Be sure you have it added and setup per the Auth category documentation.If you have asked for location access and received permission, you can also provide that in AnalyticsUserProfileLocation |
| use_resources_analytics_amplify_flutter  |  Existing Amazon Pinpoint resources can be used with the Amplify Libraries by referencing your Application ID and Region in your amplifyconfiguration.json file    |


## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.


## Known Issues

-

## Release Notes

### 1.0.0


