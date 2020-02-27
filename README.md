# TEMPLATE - Joomla Module

Use this template to create an installable Joomla template. 

If you want to install your template, then you can zip your Joomla module folder and install it through the installer in the administration section of Joomla.

# STEPS todo to adjust your Joomla module

1. The files "mod_moduletemplate.php" and "mod_moduletemplate.xml" should have to same name and should be adjusted to your module name.

2. Adjust the file mod_moduletemplate.xml to your settings.

3. Add the name of your module (here it is "mod_moduletemplate") in the "require" statement in file mod_moduletemplate.php.

4. Edit the helper class file "helper.php" to your needs if it is needed.

5. Add your PHP or/and Javascript code to the file default.php.

You can also use additional files, which have to be added always to the <files> section in the file mod_moduletemplate.xml.
