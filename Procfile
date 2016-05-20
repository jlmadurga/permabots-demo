web: gunicorn permabots_demo.wsgi:application
worker: celery worker -A permabots_demo --loglevel=info --without-gossip --without-mingle --without-heartbeat
