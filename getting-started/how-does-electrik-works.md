# How Does Electrik Works?

Electrik is a Laravel package that takes out the pain of building SaaS applications. Under the hood it installs and configures your existing Laravel installation. To do this it installs composer packages, node packages, updates migrations, and so on.

{% hint style="info" %}
Please note that Electrik is only supposed to be installed on top of a fresh Laravel installation. Installing it on an existing Laravel application is not supported and is out of the scope of this project. If you install it on an existing page, unwanted results will happen.
{% endhint %}

When you install Electrik following things happen:

### Step 1

After you install Electrik using the composer command, it does the following things:

* It registers views and routes from the package to the Laravel installation
* It registers `electrik:install` and `electrik:make` commands
* It registers `plans.php` config file from the package to the Laravel installation

### Step 2

After the Electrik is installed it provides you with two commands viz. `electrik:install` and `electrik:make`

Out of which `electrik:install` is an important command. This command is responsible for installing the migrations, tailwindcss, composer, and nodejs packages, publishing of third-party publishable, updates third-party config files to refer to Electrik's models.

After the installation is done, you can start building your SaaS straight away!
