# PayFast Setup Notes

These notes are planning guidance for tesyt4. This
generator does not implement production payment code.

## Payment Safety Rules

- Treat payment setup as sensitive.
- Use server-side validation.
- Do not trust client-side payment state.
- Log payment state changes carefully.
- Keep audit trails for financial records.
- Test in sandbox or test mode before production.
- Verify provider requirements against current PayFast documentation.

## Placeholder Environment Names

- `PAYFAST_MERCHANT_ID`
- `PAYFAST_MERCHANT_KEY`
- `PAYFAST_PASSPHRASE`
- `PAYFAST_RETURN_URL`
- `PAYFAST_CANCEL_URL`
- `PAYFAST_NOTIFY_URL`
