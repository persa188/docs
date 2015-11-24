.. ZotPie documentation master file, created by
   sphinx-quickstart on Mon Nov 23 17:38:05 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Description
============
ZotPie is a open source plugin for Zotero (Firefox) that was created to give members of the Zotero community several features that have been long overdue.

Welcome to ZotPie's documentation!
==================================
This is the user documentation for the ZotPie firefox plugin for Zotero. If you are a developer, you may be interested in the `developer documentation <./index_dev.html>`_.

.. toctree::
   :maxdepth: 2
	:getting started: Getting Started


Getting Started (short version)
================================

#. Download the plugin from `ZotPie Download Page <http://precision-dev.com/>`_ or `GitHub <https://github.com/CSCC01-Fall2015/team15-course-project/>`_ .
#. Install Zotero for FireFox
#. Open FireFox and Navigate to the Addons Menu
#. In settings (the gear icon w/ dropdown) select install addon from file and select the plugin
#. Restart Firefox and launch Zotero for Firefox.

.. _my-reference-label:

Installing, Testing, Usage (Longer Version)
============================================

Detailed Installation Instructions
------------------------------------
#. Download the plugin from #downloadpage (idk yet), link to git install instructions if git is installer
#. Install Firefox & the Zotero FireFox Plugin
#. Open firefox and navigate to the dropdown menu |Settings| and then click on Add-ons. 
#. Click on the settings gearbox and then ``install addon from file``
#. Navigate to the .xpi file downloaded in the earlier steps and click **OK**
#. restart Firefox, if not prompted. Zotero should now have the plugin installed.

.. |Settings| image:: _assets/settings-icon.png
.. |Addons| image:: _assets/addons-icon.png


Installing development versions
--------------------------------
ZotPie remains in development as of November 2015. Development Versions can be found on the GitHub dev branch. You
can also clone directly from a git enabled console by pasting: ``git clone http://github.com/repo``

Building Documentation
-----------------------
If you wish to build ZotPie's documentation for offline use, it can be built from the ``doc`` directory of a local git
repo by running ``make`` followed by the desired output format(s) (``html``, ``epub``, ``latexpdf``, etc.)

Batch Editing 
===================
#. Open Zotero (for Firefox)
#. todo

.. warning::
	The batch editor does not backup any data before making changes, the only way to undo changes to your library made by the batch editor are:
		(a) backup your library before using the batch editor
		(b) use the batch editor again, with the tag parameters switch 

Adding Custom Fields
===================
#. Open Zotero (for Firefox)
#. todo

.. note::
	This feature is intended for organizational and aesthetic purposes only, custom fields will not sync to your online Zotero library as all custom data is stored in a local database. If you do not use the Zotero servers for syncing your library and instead use your own then it may be possible, with some tweaking, to have the custom database sync your data. This, however, should only be attempted by a developer - interested developers should see the `developer documentation <./index_dev.html>`_ for ZotPie.

Coupling Documents
===================
#. Open Zotero (for Firefox)

Citation Editor
===================
#. Open Zotero (for firefox)

Notes
=====
The ZotPie plugin applies all changes to your local Zotero library, If you do not have automatic syncing enabled you
will have to sync before changes to your library are applied on the Zotero servers.

Liscense
=========
ZotPie is liscensed under the `MIT Liscense <http://opensource.org/licenses/MIT>`_.
