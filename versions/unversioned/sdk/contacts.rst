Contacts
========

Provides access to the phone's system contacts.

.. function:: Exponent.Contacts.getContactsAsync(fields)

   Get a list of all entries in the system contacts.

   :param array fields:
      An array of field names to retrieve per contact. Each element must be one
      of ``'phone_number'`` or ``'email'``.
   :returns:
      An array of objects of the form ``{ id, name, phoneNumber, email }``
      with ``phoneNumber`` present only if ``'phone_number'`` is in the
      ``fields`` parameter and ``email`` present only if ``'email'``
      is in the ``fields`` parameter.
