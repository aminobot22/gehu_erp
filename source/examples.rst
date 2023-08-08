Examples
========

Retrieve Student Details
------------------------

.. code-block:: python

   data = client.student_info()
   print(data)

Upload Profile Image
---------------------

.. code-block:: python

   client.upload_profile(img_path="path_to_image.png")

Get Exam Summary
----------------

.. code-block:: python

   exam_summary = client.exam_Summary()
   print(exam_summary)

Change Password 
----------------

.. code-block:: python

   exam_summary = client.change_password(new_password="newwww")


Change profile Picture 
----------------

.. code-block:: python

   exam_summary = client.upload_profile(img_path='new.png')
