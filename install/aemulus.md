---
description: Configure Aemulus Package Manager and build your mod loadout.
---

# Aemulus

**Aemulus Package Manager** is an [open-source](broken-reference) program that organizes, merges, and builds mod loadouts for many of the Persona games.

A complete copy of Aemulus is included with P5RCEP NX, pre-loaded with many popular packages. All you need to do is set it up and build your custom mod loadout!

## Configure Aemulus

We need to set up Aemulus itself before we can dive into customization.

### First Launch

* Open your **Aemulus** folder.
* Launch **AemulusPackageManager.exe**.

<figure><img src="https://58288921-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MfLyHlgiVPp3jfPg3ha%2Fuploads%2F9Jk81YRSqAUjB1IPSlvB%2Fimage.png?alt=media&#x26;token=d73c22f1-d428-463d-8bb5-b4ec16584b7c" alt=""><figcaption></figcaption></figure>

You'll be greeted with the package grid.

<details>

<summary>A window saying "Aemulus has a new update" appeared.</summary>

* If you get a prompt to update the program, select **Yes**.

<img src="https://58288921-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MfLyHlgiVPp3jfPg3ha%2Fuploads%2Fmmzuh1obmPIPef55w4GB%2Fimage.png?alt=media&#x26;token=f04619b2-550b-4e28-9f5f-9958086b180e" alt="" data-size="original">

* Once Aemulus has downloaded the update, click **OK** to restart the program.

<img src="https://58288921-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MfLyHlgiVPp3jfPg3ha%2Fuploads%2F5tjPc5otMa5OD4wFWguG%2Fimage.png?alt=media&#x26;token=6a79108b-a947-4121-9cfa-38e1506b9ce3" alt="" data-size="original">

* Once Aemulus restarts, confirm in the top-right corner of the window that the program is version **6.4.0** or higher.

<img src="../.gitbook/assets/Screenshot 2023-01-20 143839.png" alt="" data-size="original">

</details>

### Set Game and Loadout

#### Set Game to Persona 5 Royal (Switch)

* Make sure the **game** is set to **Persona 5 Royal (Switch** and the interface icons are **pink**

<figure><img src="../.gitbook/assets/Screenshot 2023-01-20 145100.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If the game isn't correct or the interface icons are not yellow, click the icon in the top-left and select **Persona 5 Royal** from the dropdown.

![](<../.gitbook/assets/Screenshot 2023-01-20 145212.png>)
{% endhint %}

#### Set Loadout to P5RCEP NX

* Make sure the **loadout** to configure in the top-left of the window is set to **P5RCEP NX**.

{% hint style="info" %}
If the loadout is set to something else, click the loadout box and select **P5RCEP NX** from the dropdown.

![](<../.gitbook/assets/Screenshot 2023-01-20 145340.png>)
{% endhint %}

### Set File Paths

Aemulus needs to know a few file and folder paths in order to function.

Click the gear icon ⚙️ (**Configure Paths and Settings**) above the grid.

![](<../.gitbook/assets/Screenshot 2023-01-20 145541.png>)

This will open the Persona 5 Royal (Switch) **Config** window:

![](<../.gitbook/assets/Screenshot 2023-01-20 145656.png>)

{% hint style="info" %}
If you want automatic updates, make sure Enable Mod Updates and Update All On Refresh are checked.
{% endhint %}

{% hint style="danger" %}
Make sure you check Delete Old Versions
{% endhint %}

Set the output folder to wherever you want, we will copy the files to the Switch later. Now click Unpack Base Files and select the folder with the CPKs (if you followed [this tutorial](../extras/dumping-the-game.md))

You can follow along by watching the Aemulus console:

![](https://58288921-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MfLyHlgiVPp3jfPg3ha%2Fuploads%2Fa7IpQsJOe5wQfeAoV15l%2Fimage.png?alt=media\&token=022015d4-9ec2-4919-9261-3c58abe4a66c)

Close the Config window to return to the package grid.

### Customize Your Loadout

Now for the fun part! It's time to choose which mods you'd like to use in P5R.

{% tabs %}
{% tab title="Package Info" %}
Click on a package to get more information about it on the right side of the grid. For even more information, click the package's **GameBanana** or **GitHub** link to open the mod page on the Web.

{% hint style="info" %}
Please confirm the packages included with P5RCEP NX are working correctly with your game before adding any more.
{% endhint %}
{% endtab %}

{% tab title="Enable/Disable Packages" %}
To **enable** a package and include it in your loadout, check its box in the grid.

To **disable** a package, uncheck its box in the grid.
{% endtab %}

{% tab title="Add Custom Packages" %}
**After you have finished setting up and testing P5RCEP NX, you can add additional mods.**

{% hint style="info" %}
Please confirm the packages included with P4G CEP are working correctly with your game before adding any more.
{% endhint %}
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
Once you start building, Aemulus will delete **EVERYTHING** in the Output Folder you defined in the Config window.

Make sure there are no important files in your CPK folder.
{% endhint %}

Once you've finished customizing your mod loadout, click the 🔨 **Build** button above the grid.

A window will appear asking you to confirm that everything in the output folder will be deleted.

If the folder in the confirmation box is your **CPK** folder, click **Yes** to start building your loadout**.**

You can follow along by watching the Aemulus console.

A window with **Finished Unpacking!** will appear when Aemulus has finished. \
Click **OK** to close it.

<details>

<summary>Can I change my mod loadout after building?</summary>

**Yes, as many times as you like!**\
Just customize your loadout to your liking, then click Build again!

</details>
