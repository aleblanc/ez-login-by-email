# eZ Login by Email
With this bundle users will be able to login with their email or login Without restriction to kernel ezplatform 1

Tested on eZ Platform version 2.0
## Install Package
```bash
composer require aleblanc/ez-login-by-email
```

```php
// app/AppKernel.php

class AppKernel extends Kernel
{
    ...
    public function registerBundles()
    {
        ...
        $bundles = array(
            ...
            new Matthewkp\EzLoginByEmailBundle\MatthewkpEzLoginByEmailBundle(),
            ...
        );
        ...
    }
}
```

## More information
Initially made by https://github.com/matthewkp/ez-login-by-email. This (matthew/ez-login-by-email) bundle uses compiler passes to override default eZ Platform classes.

