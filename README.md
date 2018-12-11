# digital-land-redirects
Repository of redirects from original gov.uk paas apps to heroku apps

To modify any of the redirects you'll need a user GOV.UK PAAS account and be a member
of the mhclg-digital-land organisation.

The nginx.conf files contain the actual redirect code. Documentation [here](https://docs.cloud.service.gov.uk/managing_apps.html#redirecting-all-traffic)

To deploy updates you cd into the any redirect subdirectories in this repo and enter

```
    cf push
```
