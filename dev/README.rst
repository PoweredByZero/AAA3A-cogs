.. _dev:
===
Dev
===

This is the cog guide for the 'Dev' cog. This guide contains the collection of commands which you can use in the cog.
Through this guide, ``[p]`` will always represent your prefix. Replace ``[p]`` with your own prefix when you use these commands in Discord.

.. note::

    Ensure that you are up to date by running ``[p]cog update dev``.
    If there is something missing, or something that needs improving in this documentation, feel free to create an issue `here <https://github.com/AAA3A-AAA3A/AAA3A-cogs/issues>`_.
    This documentation is auto-generated everytime this cog receives an update.

--------------
About this cog
--------------

Various development focused utilities!

--------
Commands
--------

Here are all the commands included in this cog (19):

* ``[p]bypasscooldowns [toggle=None]``
 Give bot owners the ability to bypass cooldowns.

* ``[p]debug <code>``
 Evaluate a statement of python code.

* ``[p]eval <body>``
 Execute asynchronous code.

* ``[p]mock <user> <command>``
 Mock another user invoking a command.

* ``[p]mockmsg <user> [content]``
 Dispatch a message event as if it were sent by a different user.

* ``[p]repl``
 Open an interactive REPL.

* ``[p]replpause [toggle=None]``
 Pauses/resumes the REPL running in the current channel.

* ``[p]setdev``
 Commands to configure Dev.

* ``[p]setdev ansiformatting <ansi_formatting>``
 Use the `ansi` formatting for results.

* ``[p]setdev autoimports <auto_imports>``
 Enable or disable auto imports.

* ``[p]setdev getenvironment [show_values=True]``
 Display all Dev environment values.

* ``[p]setdev modalconfig [confirmation=False]``
 Set all settings for the cog with a Discord Modal.

* ``[p]setdev outputmode <output_mode>``
 Set the output mode. `repr` is to display the repr of the result. `repr_or_str` is to display in the same way, but a string as a string. `str` is to display the string of the result.

* ``[p]setdev resetlocals``
 Reset its own locals in evals.

* ``[p]setdev resetsetting <setting>``
 Reset a setting.

* ``[p]setdev richtracebacks <rich_tracebacks>``
 Use `rich` to display tracebacks.

* ``[p]setdev sendinteractive <send_interactive>``
 Send results with `commands.Context.send_interactive`, not a Menu.

* ``[p]setdev showsettings [with_dev=False]``
 Show all settings for the cog with defaults and values.

* ``[p]setdev uselastlocals <use_last_locals>``
 Use the last locals for each evals. Locals are only registered for `[p]eval`, but can be used in other commands.

------------
Installation
------------

If you haven't added my repo before, lets add it first. We'll call it
"AAA3A-cogs" here.

.. code-block:: ini

    [p]repo add AAA3A-cogs https://github.com/AAA3A-AAA3A/AAA3A-cogs

Now, we can install Dev.

.. code-block:: ini

    [p]cog install AAA3A-cogs dev

Once it's installed, it is not loaded by default. Load it by running the following command:

.. code-block:: ini

    [p]load dev

---------------
Further Support
---------------

Check out my docs `here <https://aaa3a-cogs.readthedocs.io/en/latest/>`_.
Mention me in the #support_other-cogs in the `cog support server <https://discord.gg/GET4DVk>`_ if you need any help.
Additionally, feel free to open an issue or pull request to this repo.

------
Credit
------

Thanks to Kreusada for the Python code to automatically generate this documentation!
