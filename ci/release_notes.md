# Updates for Mattermost 4.1

## BOSH changes

- fixed the load test errand to run properly

## Changes to support Mattermost 4.1

### Added the following attributes

- mattermost.ServiceSettings.EnableEmojiPicker
- mattermost.ServiceSettings.EnableChannelViewedMessages
- mattermost.ServiceSettings.EnableAPIv3
- mattermost.ServiceSettings.EnableUserAccessTokens
- mattermost.TeamSettings.TeammateNameDisplay
- mattermost.SqlSettings.QueryTimeout
- mattermost.FileSettings.AmazonS3SignV2
- mattermost.FileSettings.AmazonS3SS
- mattermost.FileSettings.EnableMobileUpload
- mattermost.FileSettings.EnableMobileDownload
- mattermost.EmailSettings.EnableSMTPAuth
- mattermost.EmailSettings.EmailNotificationContentType

### Mattermost 4.0 and later use a different set of cluster configurations

- mattermost.ClusterSettings.ClusterName
- mattermost.ClusterSettings.UseIpAddress
- mattermost.ClusterSettings.UseExperimentalGossip
- mattermost.ClusterSettings.GossipPort
- mattermost.ClusterSettings.StreamingPort

### Mattermost 4.0 also introduced the job runner concept

- mattermost.JobSettings.RunJobs
- mattermost.JobSettings.RunScheduler
- mattemrost.ElasticsearchSettings.ConnectionUrl
- mattermost.ElasticsearchSettings.Username
- mattermost.ElasticsearchSettings.Password

### Mattermost 4.0 includes elastic search support

- mattermost.ElasticsearchSettings.EnableIndexing
- mattermost.ElasticsearchSettings.EnableSearching
- mattermost.ElasticsearchSettings.Sniff
- mattermost.ElasticsearchSettings.PostIndexReplicas
- mattermost.ElasticsearchSettings.PostIndexShards

# mattermost
Bumped https://github.com/starkandwayne/mattermost-releases to v4.1.0

# load-test
Bumped https://github.com/starkandwayne/mattermost-releases to v4.1.0
