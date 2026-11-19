# Fitrofy for Gemini CLI

Indian food data and a diet brain from [Fitrofy](https://apiportal.fitrofy.com), inside
[Gemini CLI](https://github.com/google-gemini/gemini-cli). Use it to:

- search 25K Indian foods;
- scan a meal photo, a nutrition label or a barcode;
- log a user's meals in plain words, and get insights for the day;
- get a daily diet plan, or a "can I eat this?" answer for the user's own conditions.

## Install

```console
gemini extensions install https://github.com/Fitrofy/fitrofy-gemini-extension
```

You also need:

1. **A Fitrofy account.** Create one at https://apiportal.fitrofy.com; ₹500 is added to it.
2. **A key** under **API keys**, with this computer's public IP address added to it. Every Fitrofy key accepts calls only from the addresses it lists.
3. **[uv](https://docs.astral.sh/uv/).** The extension runs the connector with `uvx fitrofy-mcp`.
4. **Your key in your shell:**

   ```console
   export FITROFY_CLIENT_ID=fit_live_all_...
   export FITROFY_CLIENT_SECRET=fsk_...
   ```

## Prices

Each tool states its price, in Indian rupees, before GST. The price is charged to your Fitrofy balance. See the [pricing](https://apiportal.fitrofy.com/portal/pricing) and the [docs](https://apiportal.fitrofy.com/portal/docs).

## No personal data

A user is named only by `user_ref`, your own pseudonymous ID. Never put a person's name, email address or phone number in a request. Fitrofy's answers are food information, not medical advice.

Fitrofy is a brand of Appneurons Technologies Private Limited.
