# Magento-actions-sample

Test for [MAD-I-T/magento-actions@master](https://github.com/MAD-I-T/magento-actions)

Source files: Latest magento 2.4.6
When using versions under 2.4.6, please uncomment elasticsearch service and comment opensearch one in the main.yml.

Check `.github/workflow/main.yml` for usage example.
The action should download and populate a dir call magento at the root of the github repo and test the src code against basic magento tasks such as unit testing, coding standard checking, build, etc... 


Reminder: 
Because a habit to follow https://12factor.net composer credentials should be set through github secret option.

1. Go to `Settings>Secrets`
2. Create variable `COMPOSER_AUTH`
3. Add you composer auth as value e.g :
   `{"http-basic":{"repo.magento.com": {"username": "xxxxxxxxxxxxxx", "password": "xxxxxxxxxxxxxx"}}}`
   
