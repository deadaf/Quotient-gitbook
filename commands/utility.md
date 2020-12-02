---
description: >-
  Here is a list of current utility commands. You can get more information about
  a command or subcommand by using qhelp <command name>.
---

# Utility Commands

* \[ \] = optional argument
* &lt; &gt; = required argument

### UTILITY

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><code>qembed&lt;subcommand&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Send or Edit embeds sent by bot.</li>
          <li>It has two subcommands - <code>send/edit</code>.</li>
          <li>Required Permissions: <code>manage_messages</code>
          </li>
          <li>Editing embed requires you to be an <code>administrator</code>
          </li>
        </ul>
        <p>&lt;code&gt;&lt;/code&gt;</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qqe &lt;text&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>This is the legacy embed command.</li>
          <li>Aliases: <code>qquickembed &lt;text&gt;</code>
          </li>
          <li>Requires: <code>manage_messages</code> and <code>embed_links</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qsay</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Create fully customizable announcements.</li>
          <li>Required Permissions: <code>administrator</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qautorole &lt;subcommand&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Setup different autoroles for bots and humans.</li>
          <li>It has 4 subcommands: <code>humans, bots , disable , config</code>
          </li>
          <li>Use <code>qhelp autorole</code> for more info.</li>
          <li>Required permissions: <code>manage_roles</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qfont &lt;subcommand&gt; &lt;text&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Convert any text to different styles.</li>
          <li>To get info about all subcommands, use <code>qhelp font</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qsteal &lt;emoji&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Steal emojis from other servers.</li>
          <li>Required Permission: <code>manage_emojis</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qroleinfo &lt;role&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get all information about a role.</li>
          <li>Aliases: <code>ri</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>quserinfo &lt;user&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get all information about a user.</li>
          <li>Aliases: <code>whois</code>,<code>ui</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qserverinfo</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get all information about current guild.</li>
          <li>Aliases: <code>si</code>,<code>gi</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qpoll &lt;text&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Create simple or custom polls.</li>
          <li>For simple poll - <code>qpoll &lt;any text&gt;</code>
          </li>
          <li>For custom poll - <code>qpoll {title} [option1] [option2]..</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qsnipe</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Snipe last deleted message from current channel.</li>
          <li>No permission required.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qvclist</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get a list of all users in your voice channel.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qshorten &lt;url&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Shorten any long URL.</li>
          <li>Required Permissions: <code>embed_links</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qpassword</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Generate a strong password.</li>
          <li>Aliases: <code>pass</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qbotpermissions</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get bot permissions in current or any other channel.</li>
          <li>Aliases: <code>perms</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qurban &lt;query&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get definition of any query from urban dictionary.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qcolor &lt;hex code&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get all information about a hex color.</li>
          <li>Aliases: <code>colour</code>
          </li>
          <li>Required permission: <code>embed_links</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qicon</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get icon of current guild.</li>
          <li>Aliases: <code>servericon</code>, <code>guildicon</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qav &lt;user&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get download link of any user&apos;s avatar.</li>
          <li>Aliases: <code>avatar</code>,<code>avy</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qtimer &lt;seconds&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Create reverse timer of x seconds.</li>
          <li>Maximum allowed seconds - <code>300</code>
          </li>
        </ul>
        <p>&lt;code&gt;&lt;/code&gt;</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qhastebin &lt;text&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Upload any text or code to hastebin.</li>
          <li>Aliases: <code>bin</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qwiki &lt;query&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Search any query on Wikipedia.</li>
          <li>Aliases: <code>wikipedia</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qcalc &lt;equation&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Calculate any simple equation.</li>
          <li>Aliases: <code>calculator</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qisitdown &lt;website url&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Check current status like ping of a website.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qweather &lt;city/pincode&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get complete weather forecast about any city.</li>
          <li>Required Permissions: <code>embed_links</code>
          </li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><code>qlyrics &lt;songname&gt;</code>
      </td>
      <td style="text-align:left">
        <ul>
          <li>Get lyrics of any song.</li>
          <li>Required Permissions: <code>embed_links</code>
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>



