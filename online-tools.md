## Online TOOLs

- https://reqbin.com

- https://resttesttest.com

----

## GitHub API

- https://stackoverflow.com/questions/51584979/get-verification-object-of-release-via-github-api

- *"GitHub API - List commits"*: https://docs.github.com/en/rest/commits/commits#list-commits

### Example

- URL: https://api.github.com/repos/ytdl-org/youtube-dl/commits
- Method: `GET`

// Just the first item...

```json
[{
        "sha": "cc179df346abf34c8f77dbb221b839092007f20c",
        "node_id": "C_kwDOAA_coNoAKGNjMTc5ZGYzNDZhYmYzNGM4Zjc3ZGJiMjIxYjgzOTA5MjAwN2YyMGM",
        "commit": {
            "author": {
                "name": "dirkf",
                "email": "fieldhouse@gmx.net",
                "date": "2022-06-12T13:10:38Z"
            },
            "committer": {
                "name": "dirkf",
                "email": "fieldhouse@gmx.net",
                "date": "2022-06-12T13:10:38Z"
            },
            "message": "[XHamster] Support xhday.com alias, extract `uploader_id`\n* support xhday.com alias for xhamster.com (resolves #31023)\n  Authored by: dirkf\n* extract `uploader_id`:\n  from https://github.com/yt-dlp/yt-dlp/commit/908b56eaf7872149706dbd7fa071f838d0c786b7\n  (PR https://github.com/yt-dlp/yt-dlp/pull/844)\n  Authored by: octotherp",
            "tree": {
                "sha": "19bb67ebf3cfe1aab7de97472cb7736618798c2d",
                "url": "https://api.github.com/repos/ytdl-org/youtube-dl/git/trees/19bb67ebf3cfe1aab7de97472cb7736618798c2d"
            },
            "url": "https://api.github.com/repos/ytdl-org/youtube-dl/git/commits/cc179df346abf34c8f77dbb221b839092007f20c",
            "comment_count": 0,
            "verification": {
                "verified": false,
                "reason": "unsigned",
                "signature": null,
                "payload": null
            }
        },
        "url": "https://api.github.com/repos/ytdl-org/youtube-dl/commits/cc179df346abf34c8f77dbb221b839092007f20c",
        "html_url": "https://github.com/ytdl-org/youtube-dl/commit/cc179df346abf34c8f77dbb221b839092007f20c",
        "comments_url": "https://api.github.com/repos/ytdl-org/youtube-dl/commits/cc179df346abf34c8f77dbb221b839092007f20c/comments",
        "author": {
            "login": "dirkf",
            "id": 1222880,
            "node_id": "MDQ6VXNlcjEyMjI4ODA=",
            "avatar_url": "https://avatars.githubusercontent.com/u/1222880?v=4",
            "gravatar_id": "",
            "url": "https://api.github.com/users/dirkf",
            "html_url": "https://github.com/dirkf",
            "followers_url": "https://api.github.com/users/dirkf/followers",
            "following_url": "https://api.github.com/users/dirkf/following{/other_user}",
            "gists_url": "https://api.github.com/users/dirkf/gists{/gist_id}",
            "starred_url": "https://api.github.com/users/dirkf/starred{/owner}{/repo}",
            "subscriptions_url": "https://api.github.com/users/dirkf/subscriptions",
            "organizations_url": "https://api.github.com/users/dirkf/orgs",
            "repos_url": "https://api.github.com/users/dirkf/repos",
            "events_url": "https://api.github.com/users/dirkf/events{/privacy}",
            "received_events_url": "https://api.github.com/users/dirkf/received_events",
            "type": "User",
            "site_admin": false
        },
        "committer": {
            "login": "dirkf",
            "id": 1222880,
            "node_id": "MDQ6VXNlcjEyMjI4ODA=",
            "avatar_url": "https://avatars.githubusercontent.com/u/1222880?v=4",
            "gravatar_id": "",
            "url": "https://api.github.com/users/dirkf",
            "html_url": "https://github.com/dirkf",
            "followers_url": "https://api.github.com/users/dirkf/followers",
            "following_url": "https://api.github.com/users/dirkf/following{/other_user}",
            "gists_url": "https://api.github.com/users/dirkf/gists{/gist_id}",
            "starred_url": "https://api.github.com/users/dirkf/starred{/owner}{/repo}",
            "subscriptions_url": "https://api.github.com/users/dirkf/subscriptions",
            "organizations_url": "https://api.github.com/users/dirkf/orgs",
            "repos_url": "https://api.github.com/users/dirkf/repos",
            "events_url": "https://api.github.com/users/dirkf/events{/privacy}",
            "received_events_url": "https://api.github.com/users/dirkf/received_events",
            "type": "User",
            "site_admin": false
        },
        "parents": [{
            "sha": "0700fde6403aa9eec1ff02bff7323696a205900c",
            "url": "https://api.github.com/repos/ytdl-org/youtube-dl/commits/0700fde6403aa9eec1ff02bff7323696a205900c",
            "html_url": "https://github.com/ytdl-org/youtube-dl/commit/0700fde6403aa9eec1ff02bff7323696a205900c"
        }]
    }

]
```
