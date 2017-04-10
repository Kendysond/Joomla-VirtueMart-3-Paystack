# Joomla-VirtueMart-Paystack
Paystack for Joomla VirtueMart

## Instructions
1. Install the plugin using normal Joomla extension installation
2. Go to `Extensions->Plugin Manager` and search for `VM Payment - Paystack`
3. Click on the plugin name and enable the plugin
4. Go to `Components->Virtuemart->Payment methods`.
6. Fill the form and select Payment Method: `VM Payment - Paystack` then `apply/save`. You may need to select all the available Shopper Groups.
7. Click on the `Configuration` tab, fill the parameters from your [Paystack Dashboard](https://dashboard.paystack.com/#/settings/developer) and save.
8. Please remember to set `Test Mode` to `No` when you are ready to start receiving payments.

## Change Log

Sept 25 2016 - v1.0.4
- Canceling the inline popup redirects
- Show HTML table after verification

Sept 21 2016 - v1.0.2
- Fix issues found by JEDchecker
- DS to DIRECTORY_SEPARATOR
- Use GPL license
- Use Currency code obtained and remove backticks from file

Sep 19 2016 - v1.0.0
- First Release
