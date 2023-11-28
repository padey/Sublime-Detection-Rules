# Sublime Detection Rules
This repo contains all my personal Sublime Security detection rules. Everything is a work in progress and should be reviewed before use in production. All these rules are in production use on our Sublime.

Rule Name | Rule Description | Rule Goal
-------- | -------- | --------
abuse_onmicrosoft_domain.yml   | Creating a new tenant on Entra will creates an "onmicrosoft.com" Domain. Now imagine, that there is a company called "abccorp", the attacker now creates a new tenant "abcorp" and uses this one for phishing. These emails are now come from "attack@abcorp.onmicrosoft.com instead of "goodguy@abccorp.onmicrosoft.com   | coming soon
info_cisco_esa_bulk_mail.yml  | coming soon   | coming soon
info_cisco_esa_marketing_mail.yml   | coming soon   | coming soon
link_adclick_doubleclick_abuse.yml   | coming soon   | coming soon
scattered_spider.yml   | coming soon   | coming soon
spam_europol_fake.yml   | coming soon   | coming soon
