# Database Design

## Table list

### Lookup tables

The following tables contain a set of values or mappings that other tables reference to ensure data consistency, reduce redundancy, and improve data normalization.

#### Achievements

The user achievement table in a database is designed to track and manage the achievements or milestones users reach within an application.&#x20;

<table>
  <thead>
    <tr>
      <th width="240">Field</th>
      <th width="658">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>acid</td>
      <td>Achievement ID, primary key</td>
    </tr><tr>
      <td>name</td>
      <td>Names of achievements</td>
    </tr><tr>
      <td>description</td>
      <td>Detail description of achievements</td>
    </tr><tr>
      <td>xp</td>
      <td>Experience point of achievements</td>
    </tr>
  </tbody>
</table>

#### Authentications

The Authentications table lists supported authentication methods (e.g. SSO, LDAP, Local user/password).

<table>
  <thead>
    <tr>
      <th width="240">Field</th>
      <th width="658">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>auid</td>
      <td>Authentication ID, primary key</td>
    </tr><tr>
      <td>name</td>
      <td>Names of authentication methods</td>
    </tr><tr>
      <td>active</td>
      <td>A Boolean flag indicates whether the selected authentication method is active.</td>
    </tr>
  </tbody>
</table>

#### Priorities

Lookup table for all priorities assigned to tickets (e.g. "low", "medium", "high").

<table>
  <thead>
    <tr>
      <th width="240">Field</th>
      <th width="658">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>prid</td>
      <td>Priority ID, primary key</td>
    </tr><tr>
      <td>name</td>
      <td>Priority label</td>
    </tr>
  </tbody>
</table>

**Status**

Status which describes ticket lifecycle (e.g. "new", "in progress", "resolved", "reopened").

<table><thead><tr><th width="281">Field</th><th>Description</th></tr></thead><tbody><tr><td>stid</td><td>Status ID, primary key</td></tr><tr><td>name</td><td>Status label</td></tr></tbody></table>

#### Tags

Keyword tags that categorize tickets and knowledge base articles.

<table><thead><tr><th width="280">Field</th><th>Description</th></tr></thead><tbody><tr><td>tgid</td><td>Tags ID, primary key</td></tr><tr><td>name</td><td>Tags' names</td></tr></tbody></table>

#### Teams

Group structure that handles specific functions and roles to efficiently manage services and resolve incidents.

<table><thead><tr><th width="280">Field</th><th>Description</th></tr></thead><tbody><tr><td>teid</td><td>Teams ID, primary key</td></tr><tr><td>name</td><td>Teams' names</td></tr></tbody></table>

### User related tables

#### Users

The users' table for **ticketopia**.

<table>
  <thead>
    <tr>
      <th width="240">Field</th>
      <th width="658">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>uid</td>
      <td>User ID, primary key</td>
    </tr><tr>
      <td>user</td>
      <td>Users' accounts</td>
    </tr><tr>
      <td>stuID</td>
      <td>Student ID</td>
    </tr><tr>
      <td>empID</td>
      <td>Employee ID</td>
    </tr><tr>
      <td>name</td>
      <td>Users' names</td>
    </tr><tr>
      <td>xp</td>
      <td>User gamification experience</td>
    </tr><tr>
      <td>level</td>
      <td>User gamification level</td>
    </tr><tr>
      <td>password</td>
      <td>User password, optional, only for locally logged in users</td>
    </tr><tr>
      <td>auth</td>
      <td>User login method, foreign key to "itsm"."authentications"."auid"</td>
    </tr><tr>
      <td>img</td>
      <td>User profile image url</td>
    </tr><tr>
      <td>disabled</td>
      <td>If user account is disabled</td>
    </tr><tr>
      <td>registered</td>
      <td>If user account has been successfully registered</td>
    </tr>
  </tbody>
</table>

#### Brag

The user achievement table records the timestamp when users earn any achievements.

<table><thead><tr><th width="281">Field</th><th>Description</th></tr></thead><tbody><tr><td>acid</td><td>Achievement ID. Foreign key "achievements"."acid"</td></tr><tr><td>uid</td><td>User ID. Foreign key "users"."uid"</td></tr><tr><td>completed</td><td>Timestamp when achievement is completed</td></tr></tbody></table>

Members

The members table records the assignments of users and teams.

<table><thead><tr><th width="282">Field</th><th>Description</th></tr></thead><tbody><tr><td>teid</td><td>Teams ID, composite primary key, foreign key "teams"."teid"</td></tr><tr><td>uid</td><td>User ID, composite primary key, foreign key "user"."uid"</td></tr></tbody></table>

