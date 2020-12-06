---
description: >-
  Here is a list of current moderation commands. You can get more information
  about a command or subcommand by using qhelp <command name>.
---

# Moderation Commands

* \[ \] = optional argument
* &lt; &gt; = required argument

### MODERATION 

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>qpurge &lt;amount&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Delete &lt;amount&gt; of messages.</li>
          <li>Requires you and bot to have manage messages permission.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qnick &lt;user&gt; &lt;name&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Change nickname of any user.</li>
          <li>Requires you and bot to have manage nicknames permission.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qkick &lt;user&gt; [reason]</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Kicks a user from current guild.</li>
          <li>Requires you and bot to have kick members permission.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qban &lt;user&gt; [reason]</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Bans a user from the current guild.</li>
          <li>Requires you and bot to have ban members permission.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qsoftban &lt;user&gt; [reason]</code>
      </td>
      <td style="text-align:left">
        <p></p>
        <ul>
          <li>Softbans a user from the current guild.</li>
          <li>Requires you and bot to have ban members permission.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qprune &lt;subcommand&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Prune only - user/reactions/emojis/files/images/embeds etc from a channel.</li>
          <li>Use <code>qhelp prune</code> to get a list of all sub commands.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qnick &lt;user&gt; &lt;name&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Change nickname of any user.</li>
          <li>Requires <code>manage_nicknames</code> permissions.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qlockdown &lt;subcommand&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Enable lockdown for a category or for the whole guild.</li>
          <li>It has two sub commands - server/category</li>
          <li>Required permissions: <code>manage_channels</code>
          </li>
          <li>Use <code>qhelp lockdown</code> to know more.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qchannel &lt;subcommand&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Create/delete/clone/rename/slowmode/lock/unlock /hide/unhide and more
            any channel.</li>
          <li>To get a list of all sub commands , use <code>qhelp channel</code> 
          </li>
          <li>Required Permissions: <code>manage_channels</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qcategory &lt;subcommand&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Create/delete/hide/unhide/lock/unlock and more any category and all its
            channels.</li>
          <li>Use <code>qhelp category</code> command to get more information on its subcommands.</li>
          <li>Required Permissions: <code>manage_channels</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qlock</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Lock current or any other channel.</li>
          <li>Required Permission: <code>manage_channels</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qunlock</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Unlock any locked channel.</li>
          <li>Required Permission: <code>manage_channels</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qmaintenance &lt;subcommand&gt;</code> 
      </td>
      <td style="text-align:left">
        <ul>
          <li>Enable or Disable maintenance mode for current guild.</li>
          <li>It has 2 sub commands- <code>enable/disable</code>
          </li>
          <li>Required Permissions: <code>administrator</code>
          </li>
          <li>Use <code>qhelp maintenance</code> to know more.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qslowmode &lt;channel&gt; &lt;seconds&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Enable or disable slowmode for any channel.</li>
          <li>Required Permissions: <code>manage_channels</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qmute &lt;user&gt; [reason]</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Mute any user.</li>
          <li>Required permission: <code>manage_roles</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qunmute &lt;user&gt; [reason]</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>unmute any muted user.</li>
          <li>Required permission: <code>manage_roles</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qtempmute &lt;user&gt; [reason]</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Tempmute any user for desired duration.</li>
          <li>Duration can only be in s|m|h|d.</li>
          <li>Required Permission: <code>manage_roles</code>
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>



