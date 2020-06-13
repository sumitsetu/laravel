## Composer Installation requirements
<p>Composer requires PHP 5.3.2+ to run. A few sensitive php settings and compile flags are also required, but when using the installer you will be warned about any incompatibilities.</p>

## How to install Composer
> - First Go to this link **https://getcomposer.org/download/**
> - Copy this code from the above page
>> - **php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"**<br>
>> - **php -r "if (hash_file('sha384', 'composer-setup.php') === 'e0012edf3e80b6978849f5eff0d4b4e4c79ff1609dd1e613307e16318854d24ae64f26d17af3ef0bf7cfb710ca74755a') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"**<br>
>> - **php composer-setup.php**<br>
>> - **php -r "unlink('composer-setup.php');"**
