Hello World!
============

This is an example of reference to field |partner_lang| and its help |partner_lang_help|.
This one is an example of a menu entry: |menu_name|.

.. |partner_lang| field:: res.partner/lang

.. |partner_lang_help| field:: res.partner/lang
   :help:

.. |menu_name| menu:: base/menu_config_address_book

This is an example of a field reference in the text: *@field:res.partner/lang@*,
while this one is an example of a menu entry
in the text: *@menu:base/menu_config_address_book:nameonly@*.

And now, the same example of field with help option: *@field:res.partner/lang:help@*.

This is an example of **Model Fields List**, for ``res.partner`` model, only *lang* and *tz* fields.

.. fields:: res.partner
   :fields: lang tz

Now another example for all fields with help for ``account.journal``.

.. fields:: account.journal


