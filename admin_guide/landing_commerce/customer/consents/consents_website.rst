.. _admin--guide--commerce--configuration--customers--consents--enable--website:

Enable Consents per Website
---------------------------

.. start_enable_consents_website

In OroCommerce, you can enable consents for the storefront if :ref:`consents have been enabled globally <admin--guide--commerce--configuration--customers--consents--enable--globally>`.

To enable consents for the storefront on the website level:

1. Navigate to **System > Websites** in the main menu.
#. For the necessary website, hover over the |IcMore| **More Options** menu to the right of the necessary website, and click |IcConfig| to start editing the configuration.
#. Select **Commerce > Customers > Consents** in the menu to the left.

   .. note:: For faster navigation between the configuration menu sections, use :ref:`Quick Search <user-guide--system-configuration--quick-search>`.

   The following page opens:

   .. image:: /admin_guide/img/configuration/customer/consents/create_consents_website_level.png
      :class: with-border
      :alt: Enable consents checkbox on the website level

#. Next to the **Enabled User Consents**, clear the **Use System** check box.
#. Click **Add Consent** and select the consent(s) from the list.

   Alternatively, click on the hamburger menu and select the consent(s) from its list.

#. If more than one consent is added to the **Enabled User Consents** list, you can drag and drop them to set the order in which these consents will be displayed in the storefront.

   .. note:: Keep in mind that on the website level you can add only those consents that have been created on the global level. You cannot create new consents on the website level.

#. To delete a consent from the list of enabled consents, click **x** next to it.
#. Click **Save Settings** on the top right.

.. finish_enable_consents_website

**Related Topics**

* :ref:`Data Protection and Consent Management <user-guide--consents>`
* :ref:`Data Protection in the OroCommerce Storefront <frontstore-guide--profile-consents>`
* :ref:`Configure Consents <configuration--guide--commerce--configuration--consents>`
* :ref:`Enable Consents Globally <admin--guide--commerce--configuration--customers--consents--enable--globally>`

.. include:: /img/buttons/include_images.rst
   :start-after: begin