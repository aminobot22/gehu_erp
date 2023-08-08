Usage
=====

To start using Gehu_erp, follow these steps:

1. Import the library:

.. code-block:: python

   import erp

2. Create a client instance:

--use_config in Client to save you login details so that you won't have to login again and again

.. code-block:: python

   client = erp.Client(use_config=True)


3. Generate session and log in:

.. code-block:: python

   user = "your_username"
   password = "your_password"
   client.login(user, password)

4. Perform various actions using the library's functions. For example:

   - Retrieve student details:

   .. code-block:: python

      data = client.student_info()
      print(data)

   - Get exam summaries:

   .. code-block:: python

      exam_summary = client.exam_Summary()
      print(exam_summary)
