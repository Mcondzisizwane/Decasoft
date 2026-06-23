# Service Setup Prompts

        Use only the prompts that match selected services.

        - Auth: inspect `docs/auth-setup-notes.md`, choose a provider, and draft a least-privilege access-control plan before coding.
- PayFast: inspect `docs/payfast-setup-notes.md` and design server-side validation and notification handling before coding.
- AWS/Amplify: inspect `docs/aws-amplify-setup-notes.md` and confirm environment separation, region, permissions, hosting, and build assumptions.
- Database: inspect `docs/database-setup-notes.md`, define the data model, plan migrations, and document backup assumptions.

        ## Secret Handling Rule

        Never place real credentials in source files, generated docs, Cursor
        prompts, chat history, or committed configuration.
