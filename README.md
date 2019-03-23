### thumbor
---
https://github.com/thumbor/thumbor

```
```

```
HBASE_STORAGE_SERVER_HOST = 'localhost'
HBASE_STORAGE_SERVER_PORT = 9000
HBASE_STORAGE_TABLE = "storage-table"
HBASE_STORAGE_FAMILY = "storage-family"

LOADER = "thumbor_hbase.loader"

STORAGE = "thumbor_hbase.storage"

LOADER = 'thumbor_mongodb.loader'
MONGO_LOADER_CNX_STRING = 'mongodb://mongodbserver01,mongodbserver02:27017'
MONGO_LOADER_SERVER_DB = 'thumbor'
MONGO_LOADER_SERVER_COLLECTION = 'images'
MONGO_LOADER_DOC_FIELD = 'content'

STORAGE = 'thumbor_riak.storage'
RIAK_STORAGE_BASEURL = "http://my-riak-install-base-url"

RESULT_STORAGE = 'thumbor_rackspace.result_storages.cloudfile_storage'
RACKSPACE_PYRAX_CFG = /var/thumbor/.pyrax.cfg

RACKSPACE_RESULT_STORAGE_EXPIRES = True
RACKSPACE_RESULT_STORAGES_CONTAINER = "cloundfile-container-name"
RACKSPACE_RESULT_STORAGES_CONTAINER_ROOT = "/"

STORAGE = 'thumbor_ceph.storages.cepth_storage'
CEPTH_STORAGE_POOL = 'thumbor'
UPLOAD_PHOTO_STORAGE = 'thumbor_ceph.storages.ceph_storage'
RESULT_STORAGE = 'thmbor_ceph.result_storages.ceph_storage'
CEPH_RESULT_STORAGE_POOL = 'thumbor'

RESULT_STORAGE = 'xxx'
SPACES_REGION = 'xxx'
SPACES_KEY = 'xxx'
SPACES_SECRET = 'xxx'
SPACES_BUCKET = 'your-bucket-name'

METRICS + 'tc_prometheus.metrics.prometheus_metrics'
PROMETHEUS_SCRAPE_PORT = 8000
```

```
```
