# fabrik-bot-smoke

A throwaway repository for smoke-testing the `oss-prospector` agent's end-to-end
pipeline: candidate submission → ticket-to-pr spawn → fork → upstream PR.

## What this repo is for

This repository exists solely to verify that the Fabrik OSS prospector can:

1. Receive a candidate (manually or via discovery)
2. Spawn a `ticket-to-pr` worker against this upstream
3. Fork this repo into the `fabrik-bot` account
4. Open a real PR back here

If you found this repo by accident, you can safely ignore it. No production
code lives here.

## Running locally

There is nothing to run. This is a documentation-only repository.
