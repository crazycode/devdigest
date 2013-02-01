# Devdigest

A script to collect activity from Github and (attempt to) compose a daily digest of what happened in your team.

## Usage

You'll need a [Github OAuth token](https://help.github.com/articles/creating-an-oauth-token-for-command-line-use).

    cp .env .env.sample
    vi .env.sample # fill in with the token and your team details
    foreman run ruby devdigest.rb