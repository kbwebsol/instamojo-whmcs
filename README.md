# instamojo-whmcs
1.Fix Trancation List Wrong Ammount issue. 
2.Unpaid Inovice Fix. 
3.Now You can set any other default currency.  
4.Get Invoice Refernce Number in Portal against Payment.


# Instamojo WHMCS 7.X.X Payment Gateway Addon


## Download:

Download the zip from [latest release](https://github.com/kbwebsol/instamojo-whmcs/releases/latest) section.

##  Installation:

Copy the contents of `modules` directory into your <WHMCS installation directory>/modules/ directory.

## Configuration

1. Navigate to `Setup -> Payments -> Payment Gateways` 
2. Click on All Payment Gateways tab.
3. Click on Instamojo.
4. You will get success message saying module activated then fill following fields:
    - **Client ID** and **Client Secret** - Client Secret And Client ID can be generated on the [Integrations page](https://www.instamojo.com/integrations/). Related support article: [How Do I Get My Client ID And Client Secret?](https://support.instamojo.com/hc/en-us/articles/212214265-How-do-I-get-my-Client-ID-and-Client-Secret-)

    - **Test Mode:** If enabled you can use our [Sandbox environment](https://test.instamojo.com) to test payments. Note that in this case you should use `Client Secret` and `Client ID` from the test account not production.
## KBWebsol is a Instamojo Partner,So We are providing a Gatway Solution to Instamojo's User as well as.
 
For any issue send us an email to support@kbwebsol.com.
 
## Support

For any issue send us an email to support@instamojo.com and share the `imojo.log` file. Location of `imojo.log` file is `modules/gateways/instamojo/logs/imojo.log`.

