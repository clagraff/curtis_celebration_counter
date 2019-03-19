Curtis Celebration Counter
========================

This is a silly slack integration to track celebrated wins in a slack channel ran by friends.

Development Quickstart
----------------------

#. Create a virtual environment

#. Run ``setup.py develop``

   ::

     python setup.py develop

Deployment
----------

After installing via ``setup.py`` run the following:

::

  $ deploy

This will update the Lambda endpoint that the API Gateway routes Slack-integration's requests to.
