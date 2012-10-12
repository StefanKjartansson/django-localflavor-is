=====================
django_localflavor_is
=====================

Country-specific Django helpers for Iceland.

What's in the Iceland localflavor?
==================================

* forms.ISIdNumberField: A form field that validates input as an Icelandic
  identification number (kennitala). The format is XXXXXX-XXXX.

* forms.ISPhoneNumberField: A form field that validates input as an Icelandtic
  phone number (seven digits with an optional hyphen or space after the first
  three digits).

* forms.ISPostalCodeSelect: A ``Select`` widget that uses a list of Icelandic
  postal codes as its choices.

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
