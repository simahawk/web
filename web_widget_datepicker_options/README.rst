.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :alt: License: AGPL-3

Datepicker Widget Options
=========================

This module allows passing options to the jquery datepicker for fields that use
the datepicker widget. Options are passed as they are, without any validation.

To see all supported options, see the `API documentation
<http://api.jqueryui.com/datepicker/>`_.


Usage
=====

You must pass all options through the "datepicker" field in the options::

    ...
    <field name="date" options="{'datepicker': {'yearRange': 'c-100:c+0'}}"/>
    ...

Known issues / Roadmap
======================

* Absolutely no validation on options.


Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/web/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed feedback
`here <https://github.com/OCA/web/issues/new?body=module:%20web_widget_datepicker_options%0Aversion:%2011.0.1.0.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.


Credits
=======

Contributors
------------

* Vincent Vinet <vincent.vinet@savoirfairelinux.com>
* Yanina Aular <yanina.aular@vauxoo.com>
* Luis González <lgonzalez@vauxoo.com>

Do not contact contributors directly about support or help with technical issues.

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
