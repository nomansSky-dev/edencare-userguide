# Manager User Guide — Eden Care CRM

---

## Referral → Client → Case → Match

### 1 — Create a referral

1. Go to **Referrals** in the sidebar.
2. Click **New Referral**.
3. Fill in the tabs: **Referrer** → **Personal** → **Contact** → **Demographics** → **Health** → **Support** → **Consent**.
4. Select a **Referral Source** (e.g. GP/Healthcare) — mandatory.
5. Click **Create Referral**.

![New Referral form - Referrer tab](../screenshots/2.1.png)

The referral appears in the **Received** column of the pipeline. Each tab shows a badge when complete. The consent tab requires GDPR data-processing consent and next-of-kin details.

### 2 — Advance referral through pipeline stages

1. Drag a referral card from one pipeline column to the next.
2. A **Move Referral** dialog opens — write a note explaining the stage transition.
3. Click **Confirm Move**.

![Move Referral confirmation dialog](../screenshots/2.12.png)

The move persists across reload. Column labels ("Client Created", "Befriender Assigned") map to status values ("Accepted", "Matched").

⚠️ If you don't confirm in the dialog, the move silently reverts on reload.

### 3 — Convert referral to client

1. Once the referral reaches the **Client Created** column, click **Convert to Client** on the card.
2. Review the pre-filled form — all referral data carries over.
3. Click **Create Client**.

![Convert referral to client](../screenshots/2.3.png)

![Convert Dialog](../screenshots/2.32.png)

The new client appears in the client directory.

### 4 — Add a client directly

1. Go to **Clients** in the sidebar.
2. Click **Add Client**.
3. Fill in the tabs: **Personal** → **Contact** → **Demographics** → **Health** → **Support** → **Consent**.
4. Required fields: First/Last name, DOB, Phone, Address, Postcode, Next-of-kin, **Support Types**, and Data Processing Consent.
5. Click **Create Client**.

![Add client form](../screenshots/2.4.png)

If any required field is missing, the form shows a **"There is a problem"** error with a jump link to the field.

### 5 — Create a case

1. Go to **Cases** in the sidebar.
2. Click **New Case**.
3. Enter a **Case Title**, the **Client Name**, and select **Case Types** (e.g. Befriending).
4. Optionally set priority, status, and a next-action note.
5. Click **Create Case**.

![Create a case](../screenshots/2.5.png)

The case appears in the cases list. Refresh the page if it doesn't show immediately.

### 6 — Find suggested matches

1. Open the client's profile.
2. In the **MATCHING** card, click **Find Matches**.
3. Select the case to find befrienders for.

![Find matches](../screenshots/2.6.png)

The matching engine returns a ranked, scored list. Factors: language match, travel distance, training/DBS status, and current caseload. The top match is shown first with their score and key attributes.

### 7 — Assign a befriender

1. In the match results, select the befriender you want.
2. Click **Assign Befriender**.

![Assign befriender](../screenshots/2.7.png)

The case profile now shows **ASSIGNED BEFRIENDER** with their name. If the befriender has valid DBS and complete training, assignment is direct.

### 8 — Book a visit

1. On the case, go to **Quick Actions → BOOK VISIT**.
2. The assigned befriender and client language preference are pre-filled.
3. Set the **date** and **times**.
4. Choose the visit type (Home visit, Phone call, Video call, Accompanied outing).
5. Click **Book visit**.

![Book a visit](../screenshots/2.8.png)

The booked visit appears under the case's **PLANNED VISITS** section.
