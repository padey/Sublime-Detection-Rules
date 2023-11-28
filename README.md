# Sublime Detection Rules
This repo contains all my personal Sublime Security detection rules. Everything is a work in progress and should be reviewed before use in production. All these rules are in production use on our Sublime.

Rule Name | Rule Description | Rule Goal
-------- | -------- | --------
abuse_onmicrosoft_domain.yml   | Creating a new tenant on Entra will creates an "onmicrosoft.com" Domain. Now imagine, that there is a company called "abccorp", the attacker now creates a new tenant "abcorp" and uses this one for phishing. These emails are now come from "attack@abcorp.onmicrosoft.com instead of "goodguy@abccorp.onmicrosoft.com   | coming soon
info_cisco_esa_bulk_mail.yml  | The Cisco ESA (Email Security Appliance) classifies emails according to bulk, marketing, social media and spam. This classification helps to recognise emails and their meaning. This rule is only used for classification within Sublime Automation. :)    | coming soon
info_cisco_esa_marketing_mail.yml   | The Cisco ESA (Email Security Appliance) classifies emails according to bulk, marketing, social media and spam. This classification helps to recognise emails and their meaning. This rule is only used for classification within Sublime Automation. :)   | coming soon
link_adclick_doubleclick_abuse.yml   | The Google Adclick network is generally an advertising network. Attackers use Adclick links to achieve a redirect to a malicious URL.    | coming soon
scattered_spider.yml   | Scattered Spider uses separate domains for each victim. These domains can currently be found quite easily using regex. The attack pattern can of course also change. See CISA recommendation on Scattered Spider.   | coming soon
spam_europol_fake.yml   | Attackers posing as "EUROPOL" are mainly active in Europe.   | coming soon
