---
title: "Week 6 Worklog"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---


### Week 6 Objectives:

* Focused on integrating Amazon S3 into the PHP application to manage and srote static files such as images.
* Improved scalability and reduce storage load on the EC2 server.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Created an Amazon S3 bucket <br> - Selected appropriate region and naming convention <br> - Reviewed bucket settings and storage options.                                                                                                   | 13/04/2026 | 13/04/2026      |
| 3   | - Configured bucket policy for public read access (for images) <br> - Reviewed IAM permissions for secure access.                                              | 14/04/2026 | 14/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Installed AWS SDK for PHP <br> - Configured credentials (Access Key, Secret Key) <br> - Initialized S3 client in the application. | 15/04/2026 | 15/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Implemented file upload functionality from PHP to S3 <br> - Tested uploading image files.                            | 16/04/2026 | 16/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Retrieved file URLs from S3 <br> - Displayed images in the web application <br> - Verified correct rendering and performance.                                                                                    | 17/04/2026 | 17/04/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Week 6 Achievements:

* Successfully integrated Amazon S3 into a PHP application to store static files (images, media).
* Uploaded files from the application to S3 and retrieved URLs for use in the system.
* Configured buckets, granted access permissions (public read), and managed files on S3.
* Modified the source code to store file URLs instead of directly on the server.
* Displayed image data directly from S3 on a web interface.
* Reduced load on the Amazon EC2 server, improving system performance.
* Increased scalability and stability when handling static resources.
* Understood the separation model between application server and storage in cloud architecture.