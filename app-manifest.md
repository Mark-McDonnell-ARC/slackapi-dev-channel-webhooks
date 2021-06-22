{
    "_metadata": {
        "major_version": 1,
        "minor_version": 1
    },
    "display_information": {
        "name": "channelwebhookbot",
        "description": "Bot that uses Slack APIs to generate webhooks per channel",
        "background_color": "#d32600"
    },
    "features": {
        "app_home": {
            "home_tab_enabled": true,
            "messages_tab_enabled": true,
            "messages_tab_read_only_enabled": false
        },
        "bot_user": {
            "display_name": "channelwebhookbot",
            "always_online": true
        },
        "unfurl_domains": [
            "dev.azure.com",
            "github.com",
            "trello.com",
            "teams.microsoft.com",
            "mark-mcdonnell.atlassian.net"
        ]
    },
    "oauth_config": {
        "scopes": {
            "user": [
                "links:read",
                "channels:history",
                "groups:history",
                "im:history",
                "mpim:history"
            ],
            "bot": [
                "app_mentions:read",
                "links:read",
                "channels:history",
                "groups:history",
                "im:history",
                "mpim:history"
            ]
        }
    },
    "settings": {
        "event_subscriptions": {
            "request_url": " https://americanredcross.webhook.office.com/webhookb2/0a97ebd4-49b5-4c2c-8ae1-dbd391299029@dd5b5d42-c0d3-4ad2-b5f1-60edb3af2771/IncomingWebhook/f8a38944c34546d885999a91f6f086bc/80cb2ebb-fe0c-44a4-ab9a-7fedd83c400b",
            "user_events": [
                "link_shared",
                "message.app_home",
                "message.channels",
                "message.groups",
                "message.im",
                "message.mpim"
            ],
            "bot_events": [
                "app_mention",
                "link_shared",
                "message.channels",
                "message.groups",
                "message.im",
                "message.mpim"
            ]
        },
        "org_deploy_enabled": false,
        "socket_mode_enabled": false
    }
}
