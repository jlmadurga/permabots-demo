Permabots-Demo
==============================

.. image:: https://github.com/jlmadurga/permabots/raw/master/docs/images/demo.gif
    :target: http://www.permabots.com

Just a demo for Permabots.

Permabots is a Django App to build chat bots and connect then to your app APIs. 

Repository: https://github.com/jlmadurga/permabots/

Official implementation: http://www.permabots.com


Deploy with Heroku
----------------------

.. image:: https://www.herokucdn.com/deploy/button.svg
    :target: https://heroku.com/deploy?template=https://github.com/jlmadurga/permabots-demo/tree/master


Usage
--------------

Permabots do not have dashboard (yet) you must create bots using the API or Django admin::

	$ python manage.py createsuperuser
	
Grab token to use it with the API or manage all from admin.

.. note:: You can use swagger docs generated to use API
		 <your_domain>/docs/

Permabots uses Django Site to generate webhooks. Set site domain through admin before start creating bots.
