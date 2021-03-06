---
title: Modernize your classic SharePoint sites
description: Steps to transform your SharePoint classic site into a modern Office 365 group-connected team site or communication site.
ms.date: 04/23/2018
ms.prod: sharepoint
---

# Modernize your classic SharePoint sites

SharePoint Online is continuously evolving and improving, which is a great thing for you as a consumer of the service. One of the key improvements is the availability of modern sites, which are modern Office 365 group-connected team sites or communication sites, combined with improved functionality that can be consumed from a beautiful modern user interface. To learn more about modern checkout the [SharePoint classic and modern experiences](https://support.office.com/en-us/article/sharepoint-classic-and-modern-experiences-5725c103-505d-4a6e-9350-300d3ec7d73f?ui=en-US&rs=en-US&ad=US) article and get inspired by the [SharePoint Look Book](https://sharepointlookbook.azurewebsites.net/) as it allows you to discover the modern experiences you can build with SharePoint in Office 365.

All of this is great, but you might ask yourself, *I have lots of classic (team) sites...how do I bring them into the modern SharePoint world?* The answer is **in-place modernization**: you can fully transform (or "modernize") a classic site into a modern Office 365 group-connected site by following the guidance in this section. Modernizing your sites involves one or more of the below steps:

![Modernization overview](media/modernize/modernize_overview_1.png)

> [!TIP]
> You can decide which steps to run and the order in which to run them. Although there's no one-size-fits-all process to modernize your site, the following is the recommended approach.

> [!IMPORTANT]
> For publishing portals (sites based upon BLANKINTERNET#0, ENTERWIKI#0, SRCHCEN#0, SRCHCENTERLITE#0, BICENTERSITE#0, POINTPUBLISHINGHUB#0, POINTPUBLISHINGTOPIC#0 or sites using the “Pages” library) it's not currently supported to connect these to an Office 365 group or to use modern pages. If you want to modernize your publishing portal it's recommended to start from a new communication site and configure that one accordingly.

## Enable your site to fully leverage the modern user interface

The most visible aspect of a modern site is its modern user interface. If you haven't turned off the modern experience at the tenant level (the **SharePoint Lists and Libraries experience** setting in the tenant admin center), certain pages appear in the modern user interface:

- List and library pages for most lists and libraries
- Site contents page
- Site usage page
- Recycle Bin pages

However, if you navigate your site, you will notice that the following pages still use the classic user interface:

- Home page and all other site pages (wiki pages and/or web part pages)
- List and library pages for certain lists and libraries

You probably already have the out-of-the-box modern user interface for lists and libraries enabled at the tenant level, so it makes sense to further maximize its use. SharePoint tries to show your lists and libraries by using the modern user interface, but you might have customizations or configurations that prevent this.

To maximize the use of the modern user interface for your site pages and list and library pages, see [Modernize the user interface](modernize-userinterface.md).

To learn more about how to unblock your lists and libraries when using the modern user interface, see [Maximize use of modern lists and libraries](modernize-userinterface-lists-and-libraries.md).

You will also need to modernize your customizations as explained in [Modernize customizations](modernize-customizations.md).

## Connect your site to an Office 365 group

Classic (team) sites are not connected to an Office 365 group, whereas modern team sites are. Connecting your site to an Office 365 group is an essential part of modernizing a site. The connection to an Office 365 group enables the site to consume other Office 365 services such as Teams, Planner, and Outlook.

There are two options to connect your sites to an Office 365 group:

- You can have each site owner do this on their behalf by using a wizard that can be launched from the user interface.
- You can perform a bulk operation (known as a **group-connection**) in which you connect an Office 365 group to a series of sites at one time. This option is preferred for enterprise customers because it enables you to control the configuration (public/private, site classification, alias name).

For more information about connecting to an Office 365 group and performing a group-connection, see [Connect to an Office 365 group](modernize-connect-to-office365-group.md).

## Switch to a modern tenant-scoped branding

Connecting your site to an Office 365 group not only gives you the benefits of a group-connected site, but also provides you with a new modern site home page. Depending on your needs, this new home page might be adequate, but you can choose to create your own modern home page. At that point, it makes sense to include other modernization tasks as well, such as switching to a modern site theme.

Using your company branding on SharePoint (team) sites is very common, and for classic sites you used one or more of the following components: site themes, alternate CSS, and master pages. However, alternate CSS and master pages are not compatible with the modern user interface, so you must evaluate whether these branding customizations are still relevant.

While classic site themes are respected in a modern user interface, we now have tenant-controlled site theming, so switching over to that model will future-proof your modernized site.

For more information, see [Modernize site branding](modernize-branding.md).

## Transform your classic site pages into modern pages

The final step in a site transformation is transforming your site pages. After you have completed the other steps, your site pages still appear in the classic user interface. Page transformation is not a simple process because there's no one-on-one mapping between the functionality offered by classic web parts and what's offered by the first-party client-side web parts on modern pages. Therefore, we recommend that you transform only the pages that are frequently used.

For more information about page transformation, see [Transform classic pages to modern client-side pages](modernize-userinterface-site-pages.md).

## See also

- [SharePoint classic and modern experiences](https://support.office.com/en-us/article/sharepoint-classic-and-modern-experiences-5725c103-505d-4a6e-9350-300d3ec7d73f?ui=en-US&rs=en-US&ad=US)
- [SharePoint Look Book](https://sharepointlookbook.azurewebsites.net/)
- [Office 365 development and SharePoint PnP solution guidance](../solution-guidance/office-365-development-patterns-and-practices-solution-guidance.md)