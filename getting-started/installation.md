# Installation

Electrik is meant to be installed on a fresh Laravel project. Installing it on an existing project will lead to unwanted results.

Installing Electrik is super easy.

To install Electrik run the below commands in your terminal

{% code title="Create a new Laravel project" %}
```shell
composer create-project laravel/laravel electrik-project --prefer-dist
```
{% endcode %}

{% code title="cd to new project" %}
```
cd electrik-project
```
{% endcode %}

{% code title="Require Electrik" %}
```
composer require electrik/electrik
```
{% endcode %}

{% code title="Install Electrik" %}
```
php artisan electrik:install
```
{% endcode %}

{% code title="Start local server" %}
```
php artisan serve
```
{% endcode %}

That's all! Electrik is now installed on your system. Goto [https://localhost:8000](https://localhost:8000/) to see the magic

After installation, you should update your .env file to update the new config values that Electrik installs.
