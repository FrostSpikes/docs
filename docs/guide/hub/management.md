# Hub Management

### 2.1 Creating a Hub

To create your hub, use the `/hub create` command in your server's chat. Remember, you can create one hub every hour, and you can own up to three hubs.

**Example:**

```
/hub create name:MyCoolHub icon:https://i.imgur.com/your-icon-url.png
```


Want to make your hub stand out? You can set a hub icon and banner. First, upload your images to [Imgur](https://imgur.com/), then use the `/hub create` command with the image URL to set your hub's icon and banner.

### 2.2 Deleting a Hub

Be careful! Deleting a hub is a big step. It'll make every connected server leave, and you can't undo it. To delete your hub, use the `/hub delete` command.

**Example:**


```
/hub delete MyCoolHub
```

### 2.3 Managing Hub Moderators

Hub moderators can help you manage your hub. They can invite and blacklist servers, and they can also manage hub settings. To add a moderator, use the `/hub moderator add` command.

There are two roles you can assign to moderators: `Network Moderator` and `Hub Manager`. Hub Managers have full control over the hub, while moderators can only manage hub messages and blacklist users and servers.

**Example:**

```
/hub moderator add hub:MyCoolHub user:@user. role:
```

To remove a moderator, use the `/hub moderator remove` command.

### 2.4 Managing Hub Settings

You can change your hub's settings at any time. To do this, use the `/hub manage` command.

**Example:**

```
/hub manage hub:MyCoolHub
```

This will open a menu where you can change your hub's settings. You can change your hub's name, icon, banner, description and more. You can also change your hub's visibility.

