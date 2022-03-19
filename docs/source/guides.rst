Guides
=====



Add the bot to your server
------------

To use Nexus, you'll need to first invite the Nexus to your server. You can do so by clicking `here <https://discord.com/oauth2/authorize?client_id=761036478783422484&permissions=2013785169&scope=bot%20applications.commands>`_.
Please note that all the permissions that you are asked to give to Nexus are required for the bot to work as expected.



Quick start
------------

Once you invite the bot to your server, a new channel will be created called ``#nexus-welcome``. In here, you'll find a message with instructions and a ``quickstart`` button.
If you want to start raiding right away, you can press this button and a new channel for raids will be created automatically. 

If you don't see this message or can't find it, you can always run the ``!quickstart`` command to send this message again.


Raiding
------------
General info

Joining raids
-------------

Join!

Hosting raids
-------------

Host!


Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

