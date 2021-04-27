# First Jenkins Job

After[ installing Jenskins successfully](./), we logged in Jenkins by the admin we setted up earlier.   
Now, we're going to create our first Jenkins job.

![](.gitbook/assets/image-2.png)

### 1. Create a Free-Style Job

There are different project styles we can choose. Here we choose **Freestyle project** which we can do mich more customization settings**.**

Enter the item name and tap OK.

![](.gitbook/assets/image%20%2814%29.png)

### 2. Add shell script for the Jenkins job

Leave all the sections blank and scroll to **Build Environment**.  
Choose the `Execute shell` as a build step.

![](.gitbook/assets/image%20%2810%29.png)

Here, we simply add `Hello Jenkins` for the terminal to execute and save this settings.

![](.gitbook/assets/image%20%2813%29.png)

After settings, we will come back to this Project page. Press the**`Build Now`** button to have our first Jenkins job going!

![](.gitbook/assets/image%20%2835%29.png)

Soon, we can see the console output of the job we just created!  
It successfully executed the script we added, and printed `Hello Jenkins` in the console! 

![](.gitbook/assets/image%20%2820%29.png)



