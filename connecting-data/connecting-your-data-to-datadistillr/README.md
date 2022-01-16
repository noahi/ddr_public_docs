---
description: This section explains now to connect your data sources to DataDistillr.
---

# Connecting Your Data to DataDistillr

Connecting your data sources to DataDistillr is as easy as filling out a form.  This section will guide you through the process of connecting your data source to DataDistillr.  Once you have connected your data source to DataDistillr, it is important to remember to connect it to your project(s) otherwise you will not be able to query your data!

### Before You Begin

Before you begin, you will need to know a few things about the data source you are trying to connect to DataDistillr:

* What kind of data source are you connecting?
* Usually you will need connection information such as IP address, or hostname and port.
* Access credentials.
* A unique name for your data source.  This is how you will access the data in queries.

#### Can I use LDAP or Active Directory with DataDistillr?

DataDistillr does support integrations with single sign on (SSO) systems, as well as enterprise identification and authentication systems such as LDAP and active directory.  These require an enterprise account, so please contact enterprise sales for more information.&#x20;

## Adding Your Data Source

At the top of the screen, click on the `Data Sources` link.  This will take you to the Data Sources screen where you can view the data sources you already have connected.&#x20;

![The Data Sources Button](<../../.gitbook/assets/Screen Shot 2021-11-14 at 10.59.12 AM.png>)

Next, click on the `Add Data Source` button and you will see the window to select what type of data source to add.&#x20;

![Selecting a Data Source Type](<../../.gitbook/assets/Screen Shot 2021-11-14 at 11.06.11 AM.png>)

### Types of Data Sources

While DataDistillr supports a wide range of various data sources, for simplicity's sake, we divide them up into four categories which are:

* [Uploads](uploading-files.md)
* [Databases](connecting-databases/)
* [File Systems and Cloud Storage](connecting-to-remote-storage.md)
* [APIs and External Data Sources](connecting-to-apis-and-external-data/)

When you query the data, they will more or less all feel exactly the same, but the initial configuration differs slightly between data source types. &#x20;

The specific instructions for connecting to data sources can be found in the links above. &#x20;

### Linking Your Data With A Project

The last step in connecting your data to DataDistillr is linking your data with a project.  The project is intended to filter down your data from all available data to just those data sources you are working with. &#x20;

Here is how to [link data to your project](../linking-data-to-your-project.md).&#x20;
