# checkin_report
define processes to correctly retrieve check-in report

### Skill set Needed: Moderate or expert Drupal 8 and Drupal 7 developer that has experience with Drupal modules and PHP. This module will be built with Drupal 8 methods (all of the logic and functionality), and include a plugin in the same module for Drupal 7 to connect with current Drupal 7 sites. All Drupal 8 sites will ignore the module's Drupal 7 plugin Hook.

### What is the goal of this task?
To build functionality within the Drupal framework to retrieve the appropriate checkin report from AWS S3

### Strategy
1. Create a button for users whose authenticated role is ___ and belong to a specific list of service providers.
2. Create functionality for the button to pass on Organization Name (?) as query input to S3 (eg: 'Arlington Free Clinic, VA.xlsx')
3. Allow for download of the xlsx file on pressing of the button
