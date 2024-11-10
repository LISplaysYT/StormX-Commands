# Setup

This command is used to setup different systems within the bot. Currently we only have a welcoming system but we have more to come!



To set up the welcoming system, use the following command pattern:

```
/setup welcome-system welcome-channel:<channel> welcome-message:<message> welcome-banner:<One of the 4 provided banners>
```

**Options:**

* `channel [channel-name]`: Specify the channel where welcome messages will be sent.
* `message [custom-message]`: Set a custom welcome message. Use placeholders like `{user}` to personalize the messages.

#### Examples

*   Enable welcoming system and set custom message:

    ```
    /setup welcome-system welcome-channel:<channel> welcome-message:Welcome {user} to {server}! We now have {members} members welcome-banner:<One of the 4 provided banners>
    ```

#### Variables

* `{user}`: Represents the name of the user being welcomed.
* `{server}`: Denotes the name of the server.
* `{members}`: Indicates the total number of members in the server.



A welcoming system would look something like this after being setup&#x20;

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

