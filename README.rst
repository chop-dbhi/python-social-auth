Python Social Auth
==================

Python Social Auth is an easy-to-setup social authentication/registration
mechanism with support for several frameworks and auth providers.

Crafted using base code from django-social-auth, it implements a common interface
to define new authentication providers from third parties, and to bring support
for more frameworks and ORMs.

Deprecation notice - 2016-12-03
-------------------------------

As for Dec 03 2016, this library is now deprecated, the codebase wasoff
split and migrated into the `python-social-auth organization`_,
where a more organized development process is expected to take place.

Details about moving towards the new setup is documented in the
`migrating to social`_ document.

.. _python-social-auth organization: https://github.com/python-social-auth
.. _migrating to social: https://github.com/omab/python-social-auth/blob/master/MIGRATING_TO_SOCIAL.md

CHOP-DBHi fork info - 2019-03-07
-------------------------------

To support CBTTC-Harvest (using a Django v1.5 Harvest stack) beyond the Google+ cut-off date of March 7th, 2019,
pulling out the few remaining Google+ dependencies from GoogleOAuth2. Although attempts were made towards migrating
the Django v1.5 stack towards the active social split organization of Python Social Auth repo
(w/ its Django component now under python-social-auth/social-app-django), continued discrepencies with limited time 
lead us to instead just work with what already worked pretty well, the original omab/python-social-auth.  As such, this has been forked into a CHOP-DBHi repo to best facilitate any such adjustments to life beyond Google+.
