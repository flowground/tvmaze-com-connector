# ![LOGO](logo.png) TVmaze user **flow**ground Connector

## Description

A generated **flow**ground connector for the TVmaze user API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/tvmaze.com/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:32+03:00

## API Description

Access to the user API is only possible for users with a [premium](http://www.tvmaze.com/premium) account. A user can only access their own user data.

Authentication uses HTTP Basic. Use the TVmaze username as authentication username, and the TVmaze API key as authentication password. Your API key can be found on your [dashboard](http://www.tvmaze.com/dashboard). To try out these API calls from this page, click the "Authorize" button on top and input your credentials.


## Authorization

Supported authorization schemes:
- Basic Authentication

## Actions

### List the marked episodes

*Tags:* `marked episodes`

#### Input Parameters
* `show_id` - _optional_ - Only return episodes from this specific show

### Unmark an episode

*Tags:* `marked episodes`

#### Input Parameters
* `episode_id` - _required_

### Check if an episode is marked

*Tags:* `marked episodes`

#### Input Parameters
* `episode_id` - _required_

### Mark an episode

> Set `marked_at` to `NULL` or leave it out to use the current time.

*Tags:* `marked episodes`

#### Input Parameters
* `episode_id` - _required_

### List the followed networks

*Tags:* `followed networks`

#### Input Parameters
* `embed` - _optional_ - Embed full network info
    Possible values: network.

### Unfollow a network

*Tags:* `followed networks`

#### Input Parameters
* `network_id` - _required_

### Check if a network is followed

*Tags:* `followed networks`

#### Input Parameters
* `network_id` - _required_

### Follow a network

*Tags:* `followed networks`

#### Input Parameters
* `network_id` - _required_

### List the followed people

*Tags:* `followed people`

#### Input Parameters
* `embed` - _optional_ - Embed full person info
    Possible values: person.

### Unfollow a person

*Tags:* `followed people`

#### Input Parameters
* `person_id` - _required_

### Check if a person is followed

*Tags:* `followed people`

#### Input Parameters
* `person_id` - _required_

### Follow a person

*Tags:* `followed people`

#### Input Parameters
* `person_id` - _required_

### List the followed shows

*Tags:* `followed shows`

#### Input Parameters
* `embed` - _optional_ - Embed full show info
    Possible values: show.

### Unfollow a show

*Tags:* `followed shows`

#### Input Parameters
* `show_id` - _required_

### Check if a show is followed

*Tags:* `followed shows`

#### Input Parameters
* `show_id` - _required_

### Follow a show

*Tags:* `followed shows`

#### Input Parameters
* `show_id` - _required_

### List the followed webchannels

*Tags:* `followed webchannels`

#### Input Parameters
* `embed` - _optional_ - Embed full webchannel info
    Possible values: webchannel.

### Unfollow a webchannel

*Tags:* `followed webchannels`

#### Input Parameters
* `webchannel_id` - _required_

### Check if a webchannel is followed

*Tags:* `followed webchannels`

#### Input Parameters
* `webchannel_id` - _required_

### Follow a webchannel

*Tags:* `followed webchannels`

#### Input Parameters
* `webchannel_id` - _required_

### List all tags

*Tags:* `tagged shows`

### Create a new tag

*Tags:* `tagged shows`

### Delete a specific tag

*Tags:* `tagged shows`

#### Input Parameters
* `tag_id` - _required_

### Update a specific tag

*Tags:* `tagged shows`

#### Input Parameters
* `tag_id` - _required_

### List all shows under this tag

*Tags:* `tagged shows`

#### Input Parameters
* `tag_id` - _required_
* `embed` - _optional_ - Embed full show info
    Possible values: show.

### Untag a show

*Tags:* `tagged shows`

#### Input Parameters
* `tag_id` - _required_
* `show_id` - _required_

### Tag a show

*Tags:* `tagged shows`

#### Input Parameters
* `tag_id` - _required_
* `show_id` - _required_

### List the episodes voted for

*Tags:* `voted episodes`

### Remove an episode vote

*Tags:* `voted episodes`

#### Input Parameters
* `episode_id` - _required_

### Check if an episode is voted for

*Tags:* `voted episodes`

#### Input Parameters
* `episode_id` - _required_

### Vote for an episode

*Tags:* `voted episodes`

#### Input Parameters
* `episode_id` - _required_

### List the shows voted for

*Tags:* `voted shows`

#### Input Parameters
* `embed` - _optional_ - Embed full show info
    Possible values: show.

### Remove a show vote

*Tags:* `voted shows`

#### Input Parameters
* `show_id` - _required_

### Check if a show is voted for

*Tags:* `voted shows`

#### Input Parameters
* `show_id` - _required_

### Vote for a show

> Set `voted_at` to `NULL` or leave it out to use the current time.

*Tags:* `voted shows`

#### Input Parameters
* `show_id` - _required_

## License

**flow**ground :- Telekom iPaaS / tvmaze-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
