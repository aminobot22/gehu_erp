Usage
=====

To start using Gehu_erp, follow these steps:

1. Import the library:

.. code-block:: python

   import erp

2. Create a client instance:

.. code-block:: python

   client = erp.Client()

3. Generate session and log in:

.. code-block:: python

   user = "your_username"
   password = "your_password"
   client.gen()
   client.login(user, password)

4. Perform various actions using the library's functions. For example:

   - Retrieve student details:

   .. code-block:: python

      data = client.info()
      for key, value in data.items():
          print(f"{key}: {value}")

   - Get exam summaries:

   .. code-block:: python

      exam_summary = client.exam_Summary()
      print(exam_summary)
