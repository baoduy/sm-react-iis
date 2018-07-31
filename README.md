# sm-react-iis

The configuration to host React app on IIS.

The `Web.config` file is for IIS hosting purpose. After build the SAP application to the **dist** folder you can host them as a statis file in IIS by using this config file. This required the [url-rewrite](https://www.iis.net/downloads/microsoft/url-rewrite) to be installed on IIS server.

However if you are not hosting this app in IIS just simply delete this file.or leave if there. There is no impact to the application.

## SSL Support

Hosting an SSL application on IIS is very simple and can be done via Internet Information Service Manager.
Follow the steps [here](https://www.digicert.com/csr-creation-ssl-installation-iis-10.htm) If you want to generate an test SSL
