SISANDA'$ STOKVEL — CONNECTED APP STARTER

Supabase project: Sisanda'$ Stokvel
Monthly contribution: R200 per approved member
Due date: 1st of every month
Payment methods: EFT proof upload or cash submission
Membership: registration requires treasurer approval
Privacy: members see shared monthly payment status; personal payment history and EFT proof are restricted

PUBLISH ON GITHUB PAGES
1. Create a new GitHub repository, for example: sisanda-stokvel.
2. Extract this ZIP on your phone/computer.
3. Upload the CONTENTS of this folder to the repository root. index.html must be at the root, not inside another folder.
4. In GitHub: Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. Wait for the HTTPS Pages URL, open it in Chrome, then use Chrome menu > Install app or Add to Home screen.

FIRST TREASURER SETUP — IMPORTANT
1. Open the published app and register using the email address that should own the treasurer account.
2. Confirm the email if Supabase asks you to.
3. Sign in once. The account will appear as a pending member.
4. The first treasurer must be promoted once in the Supabase SQL Editor. Do not share your password or service-role key. Ask ChatGPT to promote the exact email you used; the project is already connected there.
5. After the first treasurer is approved, they can approve the rest of the family from the app.

SECURITY NOTES
- The publishable key in index.html is designed for frontend use. Never put a Supabase service-role or secret key in this file.
- Keep the payment-proofs storage bucket private.
- This is an early version. Test registration, approvals, proof uploads, payment verification, withdrawals, and member visibility with test accounts before recording real family money.
- The app records stokvel transactions; it does not hold or transfer actual money.
