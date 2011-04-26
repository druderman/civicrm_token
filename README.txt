README.txt
==========

CiviCRM Token Module

This module exposes tokens to Drupal. 
It makes available as Drupa Tokens those CiviCRM Contact fields (and Address, Phone, and Email) which are flagged for Export.
Eventually it should support other CiviCRM entities like Events.
It has been tested with the Drupal Rules module.

To test, enable the Drupal module Token and the civicrm_rules module in the CiviCRM distribution.
To see a list of Tokens for an Entitiy, go to yoursite.example.com/admin/help/token
To use, create a Rule condition or action in a Contact context.

COMPATIBILITY
=============

Requires:
Drupal 6.x
CiviCRM 3.3.x
Token module

Works with: 
Rules and cvicrm_rules modules.

AUTHOR/MAINTAINER
=================

David Ruderman, druderman AT admin DOT umass DOT edu
