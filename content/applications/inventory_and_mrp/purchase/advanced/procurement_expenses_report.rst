===========================
Procurement expenses report
===========================

.. |RFQ| replace:: :abbr:`RfQ (Request for Quotation)`
.. |RFQs| replace:: :abbr:`RfQs (Requests for Quotation)`
.. |POs| replace:: :abbr:`POs (Purchase Orders)`
.. |PO| replace:: :abbr:`PO (Purchase Order)`
.. |caret| replace:: :icon:`fa-caret-down` :guilabel:`(down)` icon
.. |per| replace:: procurement expenses report

With the *Purchase* application, users can monitor procurement expenses over time. This report helps
companies track and analyze spending, identify cost-saving opportunities, and ensure efficient
budget management.

Create procurement expenses report
==================================

To create a vendor costs report, first navigate to :menuselection:`Purchase app --> Reporting -->
Purchase` to open the :guilabel:`Purchase Analysis` dashboard. By default, the dashboard displays a
line chart overview of the :guilabel:`Untaxed Total` of POs (Purchase Orders) with a
:guilabel:`Confirmation Date` for the current month, or of RFQs (Requests for Quotation) with a
status of *Draft*, *Sent*, or *Cancelled*.

Add filters and groups
----------------------

On the top-right, click the :icon:`oi-view-pivot` :guilabel:`(pivot)` icon to switch to pivot view.

Remove any default filters from the :guilabel:`Search...` bar. Then, click the |caret| to open the
drop-down menu that contains the :guilabel:`Filters`, :guilabel:`Group By`, and
:guilabel:`Favorites` columns.

.. note::
   Unless otherwise specified, the report displays data from both |RFQs| and |POs|. This can be
   changed by selecting either :guilabel:`Requests for Quotation` or :guilabel:`Purchase Orders`
   under the :guilabel:`Filters` column.

Click :guilabel:`Add Custom Filter` to open a popover window.

Next, under the :guilabel:`Group by` column, select :guilabel:`Vendor`. Then, select
:guilabel:`Product`, which is also located in the :guilabel:`Group By` column.

Add measures
------------

After selecting the :guilabel:`Filters`, :guilabel:`Group by`, and :guilabel:`Comparison` settings,
click out of the drop-down menu.

By default, the report displays with the following measures: :guilabel:`Order`, :guilabel:`Total`,
:guilabel:`Untaxed Total`, and :guilabel:`Count`. Click :guilabel:`Measures` at the top-left to open
the drop-down list of available measures.

View results
============

Click :guilabel:`Insert in Spreadsheet` to add the pivot view into an editable spreadsheet format
within the *Documents* app.

.. important::
   The :guilabel:`Insert in Spreadsheet` option is **only** available if the *Documents Spreadsheet*
   module is installed.

.. note::
   The |per| is also available in *graph* view. Click the :icon:`fa-area-chart` :guilabel:`(area
   chart)` icon to change to graph view. Click the corresponding icon at the top of the report to
   switch to a :icon:`fa-bar-chart` :guilabel:`(bar chart)`, :icon:`fa-line-chart` :guilabel:`(line
   chart)`, or :icon:`fa-pie-chart` :guilabel:`(pie chart)`.

.. seealso::
   To save this report as a *favorite*, see :ref:`search/favorites`.
