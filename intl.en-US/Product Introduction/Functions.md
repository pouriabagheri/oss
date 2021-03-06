# Functions {#concept_ilc_x31_tdb .concept}

Before you start to use OSS, we recommend that you have basic familiarity with some important OSS concepts, including buckets, objects, regions, endpoints, and AccessKey.

For more information about these concepts, see [Basic concepts](../intl.en-US/Developer Guide/Basic concepts.md#).

OSS provides the following functions to address your business needs in different scenarios.

|How do I…?|Function description|Reference|
|:---------|:-------------------|:--------|
|Upload files|Before you can upload any data to OSS, you must create a bucket in one of Alibaba Cloud regions to store your data. After you create a bucket, you can upload an unlimited number of data objects to the bucket.| -   [Create a bucket](../intl.en-US/Developer Guide/Bucket Management/Create a bucket.md#)
-   [Create a folder](../intl.en-US/Console User Guide/Manage objects/Create a folder.md#)
-   [Simple upload](../intl.en-US/Developer Guide/Upload files/Simple upload.md#)

 |
|Search files|You can search for files in buckets or folders.|[Search for files](../intl.en-US/Console User Guide/Manage objects/Search for objects.md#)|
|View and download files|You can use the object URL to view and download the object, or share the object with others.|[Obtain the object URL](../intl.en-US/Console User Guide/Manage objects/Get object URL.md#)|
|Delete files and folders|You can delete a single or multiple objects and folders. You can also delete fragments generated by multipart upload to save your storage space.| -   [Delete objects](../intl.en-US/Developer Guide/Managing Objects/Delete an object.md#)
-   [Delete folders](../intl.en-US/Console User Guide/Manage objects/Delete a folder.md#)
-   [Delete fragments](../intl.en-US/Console User Guide/Manage fragments.md#)

 |
|Control access permissions for my OSS resources|OSS provides Access Control Lists \(ACLs\) for permission control. ACLs are access policies that grant access permissions to buckets and objects. You can configure the ACL when creating a bucket or uploading an object, and modify the ACL anytime after the bucket is created or the object is uploaded.| -   [Set ACL bucket permissions](../intl.en-US/Developer Guide/Bucket Management/Set bucket read and write permissions.md#)
-   [Set ACL object permissions](../intl.en-US/Console User Guide/Manage objects/Change object ACL.md#)

 |
|Record the detailed information of requests made to my bucket|You can enable logging to automatically record the detailed information of requests made to a bucket.|[Set access logging](../intl.en-US/Developer Guide/Security management/Set access logging.md#)|
|Prevent data on OSS from being stolen by others|You can configure a referer whitelist for a bucket and configure whether to allow access requests with an empty referer field.|[Set anti-leech](../intl.en-US/Developer Guide/Security management/Anti-leech settings.md#)|
|Use my own domain to access the data stored in my OSS bucket|You can bind a custom domain to your OSS bucket. Then you can use the custom domain to access data stored in the bucket. You can also enable Alibaba Cloud CDN to speed up the access to the data stored in the bucket.|[Bind a custom domain](../intl.en-US/Developer Guide/Access and control/Bind a custom domain name.md#)|
|Enable my client web applications that are loaded in one domain to interact with resources in another domain|OSS provides Cross-Origin Resource Sharing \(CORS\) settings in the HTML5 protocol. CORS allows client web applications that are loaded in one domain to interact with resources in another domain.|[Configure CORS rules](../intl.en-US/Developer Guide/Security management/Cross-origin resource sharing.md#)|
|Automatically delete objects in batches at specific time|You can configure lifecycle rules to define actions you want OSS to take during the lifetime of specific objects, for example, transition objects to another storage class, archive them, or delete them after a specified period of time.|[Manage object lifecycle](../intl.en-US/Developer Guide/Managing Objects/Manage object lifecycle.md#)|
|Synchronize newly created objects, object updates, and object deletions from one bucket to another bucket in a different region|Cross-region replication is the automatic, asynchronous copying of objects across buckets in different regions. Cross-region replication replicates newly created objects, object updates, and object deletions from a source bucket to a destination bucket in a different region.|[Create Cross-region replication rules](../intl.en-US/Developer Guide/Managing Objects/Cross-region replication.md#)|
|Fetch content from the origin store|You can create back-to-origin rules to define whether to fetch origin data by mirroring or redirection. Back-to-origin rules are usually used for hot migration of data and redirect of specific requests.|[Create back-to-origin rules](../intl.en-US/Developer Guide/Managing Objects/Manage origin retrieval settings.md#)|
|Modify HTTP headers|You can set a single or multiple HTTP headers.|[Set object HTTP headers](../intl.en-US/Console User Guide/Manage objects/Set an HTTP header.md#)|
|View resource usage|You can view the real-time information about OSS service usage, such as basic system operation statuses and performance.|[Monitoring service overview](../intl.en-US/Developer Guide/Monitoring Services/Monitoring service overview.md#)|
|Process images stored in OSS|You can perform different operations on the images stored on OSS, such as format conversion, cropping, scaling, rotation, watermarks, and style encapsulation.|[Image processing](../intl.en-US/Image Processing Guide/Image processing.md#)|
|Use APIs and SDKs| OSS provides RESTful APIs and SDKs for the most popular programming languages.| -   [API Reference](../intl.en-US/API Reference/OSS API documentation overview.md#)
-   [SDK Reference](https://www.alibabacloud.com/help/doc-detail/52834.htm)

 |

