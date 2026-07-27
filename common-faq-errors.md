# Common FAQ / Errors

### Skins Are Not Saving After Restarting With Unlock All

If your skins reset after restarting the game, this is usually caused by Ubisoft Connect's automatic cloud save synchronization.

#### Fix

1. Open **Ubisoft Connect**.
2. Click your profile name in the top-right corner.
3. Go to **Settings**.
4. Disable:

```
Enable cloud save synchronization for supported games
```

5. Restart **Rainbow Six Siege**.
6. Select the skins you want to use.
7. Enter any match (**Online or LAN both work**).

This will force the local save file to update.

#### Online Save Data Error

When launching the game, you may see an:

```
Online Save Data Error
```

If this appears, select:

```
Use Local Save Data
```



***

### "No Response From Server" Error

This error can happen for several reasons. Try the following fixes:

* Disable your firewall temporarily.
* Make sure your **Date & Time settings are synchronized**.

#### Connection Troubleshooting Steps

Before opening a support ticket, try the following:

1. Connect to **Cloudflare WARP**.
2. Ensure WARP is running in **UDP mode**.
3. Keep WARP connected while injecting.
4. Launch **Rainbow Six Siege**.
5. Wait until you reach the **main menu**.
6. Disconnect WARP.
7. Reconnect to the game servers.

If successful, you should see:

```
Welcome to Sapphire
```

Cloudflare WARP Download

Download Cloudflare WARP here:

{% embed url="https://downloads.cloudflareclient.com/v1/download/windows/ga" %}

***

### Date & Time Synchronization

Make sure your system date and time are correct.

To sync your time:

1. Open **Windows Settings**.
2. Go to:

```
Time & Language → Date & Time
```

3. Enable:

```
Set time automatically
```

4. Press:

```
Sync now
```

Having incorrect date and time settings can prevent the loader from connecting properly.
