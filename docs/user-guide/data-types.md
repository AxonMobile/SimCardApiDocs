# Data Types

## SimCard

Simple representation of a single sim card in our system.

| Field            | Type             |
| :--------------- | :--------------- |
| icc              | String           |
| msisdn           | String           |
| state            | SimCardState     |
| operatorName     | String           |
| dataSessionState | DataSessionState |

## SimCardState

Enumeration, may have the following values:

* OPEN
* ACTIVE
* SUSPENDED
* TERMINATED

## DataSessionState

Enumeration, may have the following values:

* CONNECTED
* NOT_CONNECTED
* HEARTBEAT

## SimCardActions

Enumeration, may have the following values:

* SUSPEND
* ACTIVATE
* TERMINATE
* RESET_SOFT
* RESET_HARD