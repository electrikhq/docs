# Directory Structure

Electrik is a non-intrusive package. It will not interfere with your existing structure. Most of the project is based on Laravel's directory structure. You can read more about it [here](https://laravel.com/docs/9.x/structure).

However, for the documentation here is how Electrik is structured:

* art (contains a screenshot of the dashboard you see after logging in)
* config&#x20;
* database/migrations
* resources/views&#x20;
* routes&#x20;
* src&#x20;
* stubs&#x20;
* .gitignore&#x20;
* LICENSE&#x20;
* README.md&#x20;
* composer.json&#x20;
* composer.lock

### Art Directory

Art directory contains screenshots and graphics which are used for various documentations, and readme files. They are not required or used in the application anywhere.

### Config Directory

For Electrik to work properly, it needs to modify some values in default configuration files like auth.php, livewire.php, etc. You can take a look at the files to understand what has changed.

Database/Migrations

Similar to configuration, Electrik also needs to modify the table structure of existing packages to make it compatible with some features of Electrik. For example, we need to add `team_id` to Cashier's subscription table to make sure it works for the team rather than a user in the system.
