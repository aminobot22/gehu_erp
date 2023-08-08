Examples
========

Retrieve Student Details
------------------------

.. code-block:: python

   data = client.info()
   for key, value in data.items():
       print(f"{key}: {value}")

Upload Profile Image
---------------------

.. code-block:: python

   client.upload_profile(img_path="path_to_image.png")

Get Exam Summary
----------------

.. code-block:: python

   exam_summary = client.exam_Summary()
   print(exam_summary)
