# Starling FreeAgent Export

This uses the Starling API to generate a CSV of the 50 most recent transactions
in a form that FreeAgent can import.

## Usage

    $ STARLING_ACCESS_TOKEN='...' starling-freeagent-export > starling.csv

## Obtaining a token

1. Sign up for a [Starling developer account](https://developer.starlingbank.com).
2. Under *Settings*, Link the developer account to your business account.
3. Under *Personal Access*, create a Personal Access Token with the permissions:
    - `account:read`
    - `balance:read`
    - `transaction:read`
4. Copy the token generated.
