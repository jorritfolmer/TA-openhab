# TA-openhab for Splunk

This CIM compliant TA can be used with Splunk (Enterprise Security) and provides
field extractions, aliases, eventtypes and tags for Openhab events and logs.

## Installation

Install this TA on your Splunk (Enterprise Security) search head and indexers. Make sure to
name it TA-openhab otherwise ES won't eat it. 

## Configuration

You should sourcetype the Openhab log files as follows:

1) events.log: `openhab:events`

2) openhab.log: `openhab:log`

