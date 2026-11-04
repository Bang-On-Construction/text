# text

One static page behind the "Text <name>" link in Bang On's #sales-leads Slack alerts. Slack's phone apps won't open
`sms:` links, so the alert links here and this page opens the rep's own Messages app with the lead's number and a
prefilled message. Nothing is sent automatically, and the page stores nothing.

Link format: `https://bang-on-construction.github.io/text/#<10-digit phone>/<rep>/<lead first name>`. The part after
`#` never leaves the phone (browsers don't send it to the server). Built by `scripts/leads/lead-common.ps1` in
`Bang-On-Construction/bang-on`; change the message there and here together.
