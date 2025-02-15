﻿.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: /Includes.rst.txt


.. _extconf:

==================
Extension settings
==================

Some general settings can be configured in the Extension Configuration.

#. Go to :guilabel:`Admin Tools > Settings > Extension Configuration`
#. Choose :guilabel:`sf_event_mgt`

.. only:: html

   .. contents:: Properties
      :depth: 1
      :local:

Records
=======

Slug behaviour `slugBehaviour`
------------------------------

.. confval:: slugBehaviour

   :type: string, keyword
   :Default: unique

   Choose one of the following slug behaviours:

   uniqueInSite
      The same slug can be used for news in different sites. Use this
      setting *only* if no event records are shared between sites.

   unique
      The same news title in different sites will lead to different slug names.

Payment
=======

Enable payment method 'invoice' `enableInvoice`
-----------------------------------------------

.. confval:: enableInvoice

   :type: bool
   :Default: 1

   Enable payment method 'invoice'

Enable payment method 'transfer' `enableTransfer`
-------------------------------------------------

.. confval:: enableTransfer

   :type: bool
   :Default: 1

   Enable payment method 'transfer'

Backend
=======

Hide registrations in event record by limit `hideInlineRegistrations`
---------------------------------------------------------------------

.. confval:: hideInlineRegistrations

   :type: bool
   :Default: 0

   Enable feature to hide registrations when editing an event in the backend

Hide registrations in event record by limit `hideInlineRegistrationsLimit`
--------------------------------------------------------------------------

.. confval:: hideInlineRegistrationsLimit

   :type: int
   :Default: 500

   Max amount of registrations to display before event registrations will be hidden when editing an event.
