---
title: Installation
taxonomy:
    category: docs
    tag: [gantry5]
gravui:
    enabled: true
    tabs: true
process:
    twig: true
---

The Gantry framework itself is independent of any template. Each Gantry-enabled template relies on the Gantry framework to provide the underlying base and extensive functionality that enables the creation of such powerful sites. While a Gantry-powered template does require the Gantry framework to work properly, Gantry is not inherently built in to the template, itself.

Downloading Gantry
------------------

Gantry has three available download types:

{% set tab1 %}

* **Bundle**: This includes the Framework (library, component & plugins), the Gantry template and associated extensions such as RokNavMenu.
* **Framework**: This contains only the Framework (library, component & plugins).
* **Template**: This contains just the Gantry template.

The installation process is exactly the same for all three. The only difference is the file you are installing. Select the download option best for you. We recommend the bundle for first-time installs.

[Download](http://www.gantry-framework.org/download#joomla)

{% endset %}
{% set tab2 %}

>>> WordPress support is coming soon.

* __Framework__: This contains only the Framework plugin.
* __Theme__: This contains just the Gantry theme.
* __RocketLauncher__: This includes the full WordPress installation, Framework (plugin) and the pre-configured Gantry template (only for NEW installations).

The package you choose to install makes a difference in terms of where you'll be installing the files. **Gantry Framework for WordPress** should be installed like a standard WordPress plugin. The **Gantry Default Theme for WordPress** should be installed the same way you would install any other theme. 

>>>>> Keep in mind that you will need the Gantry framework installed for any Gantry themes to work.

If you don't have WordPress installed on your server yet, you can use the **RocketLauncher** package. It contains the full pre-configured Gantry environment, and is essentially a complete WordPress installation. Choose whichever download option is best for you. We recommend the **RocketLauncher** for first-time WordPress installations.

[Download](http://www.gantry-framework.org/download#wordpress)

{% endset %}
{{ gravui_tabs({'Joomla':tab1, 'WordPress':tab2}) }}

Installing Gantry
-----------------

{% set tab1 %}

Install at **Extensions → Extensions Manager → Install**. Select the **Choose File** button, locate the downloaded ZIP and click **Upload & Install** to begin the installation.

![Installation](install-template_joomla.jpeg) {.border .shadow}

The Gantry template will appear in the **Template Manager**, the Gantry plugins will appear in the **Plugin Manager**, and RokNavMenu will be available from the **Module Manager** (Click **New** to create a new instant of RokNavMenu). The component/library will be hidden, and only accessible from the **Extensions Manager** for uninstallation/upgrading purposes.

{% endset %}
{% set tab2 %}

>>> WordPress support is coming soon.

To install the Gantry template, you'll need to navigate to **Plugins → Add New** in the admin area of WordPress. From here, select the **Browse** button, locate the downloaded ZIP file, and click **Install Now** to begin installation.

![](install-upload_wp.jpg) {.border .shadow}

The Gantry template will appear in **Themes**, the Gantry plugins will appear in **Plugins**.

{% endset %}
{{ gravui_tabs({'Joomla':tab1, 'WordPress':tab2}) }}

Setting the Gantry Template as Default
--------------------------------------

{% set tab1 %}

If you are using the Gantry template, you will want to set it as the default template so it loads on the front end. Go to **Extensions → Template Manager**, select the **gantry** checkbox, and click **Default** in the button toolbar.

![](install-upload_joomla.jpeg)

{% endset %}
{% set tab2 %}

>>> WordPress support is coming soon.

If you are using the Gantry framework, you'll want to use a Gantry-compatible template. After uploading your template, simply go to the **Appearance → Themes** area in the admin area of WordPress and click **Activate** next to your template.

![](install-template_wp.jpg)

{% endset %}
{{ gravui_tabs({'Joomla':tab1, 'WordPress':tab2}) }}