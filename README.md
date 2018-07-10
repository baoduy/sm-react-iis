# sm-react-iis

The configuration to host React app on IIS.

The `Web.config` file is for IIS hosting purpose. When build the application this file will be copied to dist folder automatically and make the package ready for IIS.

However if you are not hosting this app in IIS just simply delete this file.or leave if there. There is no impact to the application.

## SSL Support

Hosting an SSL application on IIS is very simple and can be done via Internet Information Service Manager.
Follow the steps [here](https://www.digicert.com/csr-creation-ssl-installation-iis-10.htm) If you want to generate an test SSL
