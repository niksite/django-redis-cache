django-redis-cache
==================

Just change your

    CACHE_BACKEND = 'memcached://127.0.0.1:11211/?timeout=1500'
to

    CACHE_BACKEND = 'redis_cache.cache://127.0.0.1:6379/?timeout=1500'
and put this redis_cache folder somewhere in your PYTHONPATH.
