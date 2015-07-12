# Drupal Demo Module
Drupal demo module developed in PhpStorm

It's designed to use with [remote development repo](https://github.com/Leneshka/remoteDevSetup). Checkout it. Then download
[Drupal 8](https://www.drupal.org/node/3060/release?api_version%5B%5D=7234) and extract it into
`sharedfolder/drupalcampdemo` directory.
I used `drupal-8.0.0-beta12` build.

Then run vagrant with `vagrant up`, navigate to [drupalcampdemo.dev](drupalcampdemo.dev) and procede installation procedure.
Do not forget username and password you've created.

Now checkout this repo into `ps-demo` directory inside `sharedfolder/drupalcampdemo/modules`. Then navigate to `Extend`
 tab on the site, and enable custom plugin `Demo Module by PhpStorm`. This should make it work.
 To check test `Hello DrupalCamp` page added at `/hello`. Also there will be example settings link
`Demo Module by PhpStorm module settings` in `Confiruration | Development` menu added.
Both of them based on [tutorial](https://www.drupal.org/node/2464195).

When something is changed in module, it should be reloaded with `Configuration | Development | Performance | Clear Caches` in Drupal menu.
