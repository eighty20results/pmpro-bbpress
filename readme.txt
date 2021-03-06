=== Paid Memberships Pro - bbPress Add On ===
Contributors: strangerstudios, slocumstudio, jessica o
Tags: paid memberships pro, pmpro, bbpress, forums, membership forum, restrict forum
Requires at least: 3.5
Tested up to: 4.4.2
Stable tag: 1.5

Integrate bbPress with Paid Memberships Pro to restrict forums by membership level.

== Description ==

The bbPress Add On for Paid Memberships Pro adds a "Require Membership" meta box to the "Edit Forum" page, allowing you to easily toggle the membership level(s) that can access the forum. 

Requires bbPress and Paid Memberships Pro installed and activated.

== Installation ==

= Prerequisites =
1. You must have Paid Memberships Pro and bbPress installed and activated on your site.

= Download, Install and Activate! =
1. Download the latest version of the plugin.
1. Unzip the downloaded file to your computer.
1. Upload the /pmpro-bbpress/ directory to the /wp-content/plugins/ directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.

= How to Use =

1. After activation, navigate to the "Edit Forum" page for the forum you would like to restrict. 
1. Check the box for each level that can access this forum in the "Require Membership" meta box (below the Publish box in the right sidebar). 
1. Save your changes by clicking the "Update" button (or "Publish" if you are creating a new forum).
1. Further settings can be found on the Settings -> Forums page of your admin dashboard.

== Screenshots ==

1. The "Require Membership" meta box for controlling forum access.

2. Settings -> Forums

== Changelog ==
= 1.5 =
* FEATURE: Added a membership level setting to set the background color of member topics and replies.
* FEATURE: Added an option to the bbPress settings page to change the error message shown when non-members try to access a member forum.
* FEATURE: Added an option to the bbPress settings page to add "member links" linking to forums a user has access to.
* FEATURE: Added an option to the bbPress settings page to hide member forums from the forums list and search results.
* FEATURE: Added an option to the bbPress settings page to hide forum roles in replies.
* FEATURE: Added an option to the bbPress settings page to show membership level in replies.

= 1.4 =
* Removed TGM and using different methods to make sure PMPro and bbPress are activated.
* Changed forum check to use template_redirect instead of wp hook.

= 1.3 =
* Updated TGM Plugin Activation class

= 1.2 =
* Added the "pmpro_bbp_error_msg" filter so you can change the message shown when users try to access forums they don't have access to.

= 1.1.5 =
* Added bbp_is_single_topic() check to search filter to fix issues where main topic is hidden on single topic pages. (Thans, Spence)

= 1.1.4 =
* Updates to name, description, tags. Added link to support and settings on plugins page.

= 1.1.3 =
* Fixed fatal error that would come up if Paid Memberships Pro was not active. (Thanks, Karmyn Tyler Cobb)
 
= 1.1.2 =
* BUG: Fixed bug in search filter that would hide member forums/topics from members when more than one level had access to a forum.

= 1.1.1 =
* Moved filterqueries code into init function to avoid function not found error.

= 1.1 =
* pmpro_search_filter now hides restricted forums and topics as well.

= 1.0.1 =
* Fixed generation of URLs &noaccess=1. The old URLs could sometimes lead to 404 pages. (Thanks, bfintal on the WordPress.org forums.)

= 1.0 =
* Initial WP.org release.
