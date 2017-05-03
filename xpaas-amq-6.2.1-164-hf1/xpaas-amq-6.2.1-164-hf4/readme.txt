==========================================================================================================
XPAAS AMQ jboss-amq-62 image Hotfix 4

If you have any questions or feedback, please open a support request.
==========================================================================================================

Prerequisites:

XPAAS AMQ jboss-amq-62 - 6.2.1 Rollup 4 (621159)

==========================================================================================================

This patch release is an update to XPAAS AMQ jboss-amq-62 and includes the following bug fixes:

==========================================================================================================
XPAAS AMQ jboss-amq-62 image Hotfix 4
==========================================================================================================

https://issues.jboss.org/browse/ENTMQ-2060 - [A-MQ6, Producer Flow Control] only logs Producer Flow control once

==========================================================================================================

This patch is intended to be applied to XPAAS AMQ jboss-amq-62 image. 

To apply this patch, please follow the relevant steps based on the S2I (Source-to-image) feature [1]:

1. Copy patch folder inside the git directory of your application’s Git project root.
2. Add the following folder to your git directory .sti/bin, and copy assemble file inside .sti/bin/ git directory of your application’s Git project.
3. Using s2i method, you have to start a new build after updating your application’s Git Repository, 
   once the push of the image is successful, you have to start a new deployment based on the latest image that contain the HF.

==========================================================================================================

[1] https://docs.openshift.com/enterprise/3.1/using_images/xpaas_images/a_mq.html#configuring-sti
