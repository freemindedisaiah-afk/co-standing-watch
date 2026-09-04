# Colorado standing watch

Miss: a Colorado entity skips its Periodic Report.

What that costs: Noncompliant → Delinquent, **$50 late penalty** on top of the **$25** report, then **$100** to cure. After 400 days the name can get `delinquent` tacked on and become available to someone else.

This repo is not a filing service and not legal advice. It is a watch.

## What the bot does

Once a day it looks up each ID in `entities.txt` on the public Colorado SOS business search. It pings only if:

- status is not Good Standing, or
- the filing window is inside 30 days

Otherwise: quiet.

It does not file. It does not log into SOS.

## Add an entity

One 11-digit SOS ID per line in `entities.txt`.

## Charge (when someone wants this)

Square, **$49 / year / entity**. One alert stream. They still file the $25 report themselves.
