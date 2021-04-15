# Magento-actions-sample

Test for [MAD-I-T/magento-actions@master](https://github.com/MAD-I-T/magento-actions)

Source files: Magento 2.3 + Magesuite/elasticsuite

Check `.github/workflow/main.yml` for usage example.

A cleaner & lighter example using magento2 official src is found [here](https://github.com/seyuf/m2-dev-github-actions).

Reminder: 
Because a habit to follow https://12factor.net composer credentials should be set through github secret option.

1. Go to `Settings>Secrets`
2. Create variable `COMPOSER_AUTH`
3. Add you composer auth as value e.g :
   `{"http-basic":{"repo.magento.com": {"username": "xxxxxxxxxxxxxx", "password": "xxxxxxxxxxxxxx"}}}`
   
