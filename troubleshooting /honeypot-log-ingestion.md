# Honeypot Log Ingestion Troubleshooting

## Problem

Cowrie honeypot activity was being written to the log source but was not consistently generating alerts within Wazuh.

## Investigation

- Verified honeypot log generation
- Confirmed Wazuh Agent monitoring
- Tested manager connectivity
- Validated rule processing using wazuh-logtest

## Root Cause

A custom rule configuration issue prevented expected event processing.

## Resolution

The custom detection logic was corrected and validated through repeated testing.

## Result

Honeypot events successfully flowed from source logs into the SIEM and generated alerts within the dashboard.
