# Deleting your database in Amazon Lightsail<a name="amazon-lightsail-deleting-your-database"></a>

 *Last updated: March 15, 2019* 

Delete your managed database in Amazon Lightsail if you no longer need it\. You stop incurring charges for the database as soon as it’s deleted\.

**Note**  
You can’t recover a deleted database\. You can create a final snapshot of your database as part of the steps covered in this guide, or you can create a snapshot separately from the deletion process\. For more information, see [Creating a snapshot of your database in Amazon Lightsail](amazon-lightsail-creating-a-database-snapshot.md)\.

**To delete your database**

1. Sign in to the [Lightsail console](https://lightsail.aws.amazon.com/)\.

1. On the Lightsail home page, choose the **Databases** tab\.

1. Choose the name of the database that you want to delete\.

1. Choose the **Delete** tab\.

1. Add a checkmark next to **Create snapshot before deletion** to create a final snapshot before deleting the database\. Then name your snapshot\.

1. Choose **Delete database**\.

1. Choose **Yes, delete** to confirm the deletion\.  
![\[Creating a database snapshot before deleting a database\]](https://d9yljz1nd5001.cloudfront.net/en_us/cfefe1b500656f5beb2491eaf820d8f4/images/amazon-lightsail-delete-database-with-snapshot.png)

   If you opted to create a snapshot before deleting, you can view it on the **Snapshots** tab of the Lightsail home page\.