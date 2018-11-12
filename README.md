# Cloud-Backup-to-Amazon-S3-using-CloudBerry-Backup

## Scenario
This document guide you the step of backup solution which provided by APN Storage partner-CloudBerry built for Amazon S3 and Glacier.

## Prerequisites
> An AWS account.
> CloudBerry Backup License (The license fee depends on the OS you use, and is per computer, one time fee) or using 15-day free trial.

## Tutorial
### Install CloudBerry Backup
1.1. Download the product from CloudBerry website: https://www.cloudberrylab.com 

1.2. Follow the installation steps to install.

### Start your Cloud Backup process
2.1. Open the CloudBerry Backup software

2.2. Click **Back up Files**.

2.3. Click **“+”**, and select **Amazon S3 & Glacier**.

2.4. In Display Name, give a specific name that you can identify the cloud storage.

2.5. Go to **Amazon Web Services** console and click on the name of your account (it is located in the top right corner of the console). Then, in the expanded drop-down list, select **My Security Credentials**.

2.6. Click **Continue to Security Credentials**.

2.7. Expand the **Access keys (access key ID and secret access key)** option. You will see the list of your active and deleted access keys.

2.8. To generate new access keys, click the **Create New Access Key button**.

2.9. Click **Show Access Key** to have it displayed on the screen. You can download it to your machine as a file and open it whenever needed. To download it, just click the **Download Key File** button. 

***Remember!** If you do not write down the key or download the key file to your computer before you click ”Close”, you will not be able to retrieve the secret key in the future. Then you’ll have to delete the keys which you created and start to create new keys.*

2.10. Go back to CloudBerry backup, and insert the **Access Key** and **Secret Key**.

2.11. Select the **Bucket** that you want to backup to, then click **OK**. The cloud storage which you just create will be display in the Cloud storage list.

2.12. Click **Continue**.

2.13. Specify backup plan name, and check the **Save backup plan configuration to the backup storage**, and click **Continue**.

2.14. Specify files and folders you want to backup in this step, and click **Continue**.

2.15. Specify file types to backup or to skip, there are three options in this step: **Backup all files in selected folders**, Backup files of these types, and Do not backup files of these types. You can choose to backup empty folders, and/or not to backup system and hidden files, then click **Continue**.

2.16. Specify compression and encryption options, you can enable compression and encryption in this step. Choose **Use Standard-IA Storage**, then click **Continue**. About S3 Transfer Acceleration, please look at: https://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html 

2.17. Specify retention policy, you can let the default or customize your retention policy in this step. And you can decide whether to delete files that have been deleted locally after how many days, then click **Continue**.

2.18. Schedule your backup plan in this step. You can customize the frequency and timing, or just backup at a specific date, and if the plan runs overtime, stop it as your need, then click **Continue**.

2.19. Specify notification options, select whether you want to receive a notification via email or not, and choose when plan fails or in all cases. Insert your **Email** and **User name**, then click **Continue**.

2.20. Review all the customize option in Backup plan summary step, make sure all correct, check run plan now if needed, or directly click **Done**.

2.21. The backup plan information, schedule, source, and destination will be displayed.

2.22. And if you have chosen to receive the notification, you will receive the email of your backup plan status and information.

## Conclusion

Congratulations! You now have learned how to:
* Find your AWS access key and secret key
* CloudBerry backup features and solution

