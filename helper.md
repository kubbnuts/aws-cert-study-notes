86400 - 1 hour expressed in seconds

# S3
* per account limit = 100
* max upload size (single upload) = 5GB.  multipart upload API available as an alternative
## fundamentals
* key (name)
* value (data)
* version control
* metadata
* ACLs

# S3 availability & durability options
* S3 standard
* S3 Infrequent Access (retrieval fee)
* S3 Infrequent access - One Zone
* not an option - RRS (Reduced Redundancy Storage) - deprecated

# S3 security &encryption
* in transit - SSL/TLS
* at rest:
  * server side
  * S3 Managed Keys (SSE-S3) - buckets individually encrypted, AWS hold the master key
  * AWS Managed Keys (SSE-KMS) - buckets individually encrypted, separate envelope key held in KMS.  KMS provides audit trail.
  * customer managed keys (SSE-C)
  * client side

# Storage Gateway
* iSCSI = SCSI over TCP/IP
 
# S3 static website hosting
 * e.g. http://staticwebsite-kubbs.s3-website.eu-west-2.amazonaws.com/
 
# revisit list
* cached volumes (Storage Gateway - Volume Gateway)
