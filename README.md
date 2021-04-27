# Install Jenkins

### 1. **Download Jenkins with Homebrew**

Jenkins have two version that we can download. One is Stable version \(LTS, Long-Term Support\) and the other one is the regular version which updates weekly.

Here, we choose to use Homebrew to download Jenkins' stable version.

**Jenkins Download Link**: [https://www.jenkins.io/download/](https://www.jenkins.io/download/)

Install the latest LTS version: `brew install jenkins-lts`

Install a specific LTS version: `brew install jenkins-lts@YOUR_VERSION`

After we succesfully download the Jenkins' stable version, if you see the log with:

```text
==> openjdk@11
For the system Java wrappers to find this JDK, symlink it with
  sudo ln -sfn /usr/local/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk
```

Then make sure you follow the instruction, otherwise you cannot start Jenkin service.

```text
$ brew services start jenkins
Error: Formula `jenkins` is not installed.
```

```text

Start the Jenkins service: brew services start jenkins-lts
Restart the Jenkins service: brew services restart jenkins-lts
Update the Jenkins version: brew upgrade jenkins-lts
```

### **2. Start Jenkins**

Start the Jenkins service: `brew service start jenkins-lts`

```text
❯ brew services start jenkins-lts
==> Successfully started `jenkins-lts` (label: homebrew.mxcl.jenkins-lts)
```

After successfully started Jenkins, head to [http://localhost:8080/](http://localhost:8080/), you will see the **Unlock Jenkins page**. Head to the path and find the default Administrator password.

![](.gitbook/assets/image%20%2834%29.png)

When you successfully unlock Jenkins, you can choose to add plugins. If you don't have specific requests, then just simply choose `Install suggested plugins`

![](.gitbook/assets/image%20%2816%29.png)

Check the plugins you need and wait till the setup is done.

![](.gitbook/assets/image%20%288%29.png)

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}

![](.gitbook/assets/image%20%2817%29.png)

![](.gitbook/assets/image%20%2829%29.png)

![](.gitbook/assets/image%20%2812%29.png)

![](.gitbook/assets/image%20%285%29.png)

