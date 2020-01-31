# j4xdemos-admin-mod-topmenu
An experimental top menu for the Joomla Administrator atum template

Just download the mod_topmenu.zip
file and install it as any other extension. 

You need to make two changes to tha atum template:

In the index.php file add a new jdoc position above the header:

<jdoc:include type="modules" name="topmenu" style="none" />

<?php // Header ?>

And in templateDetails.xml you need to add a new position at the
bottom of the list of positions:

<position>topmenu</position>

You can then enable mod_topmenu and select the Joomla Main Menu
Preset and assign the module to topmenu position.

I think that is all. You don't need to do anything about the
existing Admin menu - just toggle it closed and use whichever
suits you.

Feedback welcome!
