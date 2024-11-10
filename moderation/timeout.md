# Timeout

#### /timeout Command

* **Sub-commands:**
  * **Timeout add**
    * **Required:** `user`, `duration`, `duration type (seconds, minutes, hours, days)`
    * **Optional:** `reason`
  * **Timeout remove**
    * **Required:** `user`
    * **Optional:** `reason`

#### /timeout Command Usage Examples

**Timeout Add Example**

To temporarily restrict a user from participating:

```
/timeout add user:lisonyt duration:5 duration_type:m reason: Spamming
```

This command will time out the user `lisonyt` for 5 minutes for spamming.

**Timeout Remove Example**

To lift a timeout before it expires:

```
/timeout remove user:lisonyt reason: False alarm
```

This command will remove the timeout for `lisonyt`, citing "False alarm" as the reason.
