## For Donation
1. Generate Donation Form
> lando drupal gf

2. Genarte custom service for payment
> lando drupal ges

3. _To be added_


## For subscription
1. Generate a module
> lando drupal gm

2. Generate Form For Subscription
> lando drupal gf

3. Generate Controller and user Form builder service to show different options
available to the user
> lando drupal gcon

4. Genarte a payment method configuration custom plugin type
> lando drupal gpta

5. Generate custom config entity to store payment configuration
> lando drupal gec

6. Generate custom content entity to store payment information
> lando drupal geco

7. Create Service for each payment
> lando drupal ges

8. Set queue on cron to check for subscription timestamp
> lando drupal gpqueue
> Implement _hook_cron()_

9. Create a custom permission and separate role for subscribed user

10. On end end of subscription, remove that role from the user
