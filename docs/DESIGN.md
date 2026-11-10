# Pazy Treasury — unaware audience

## Audience and persuasion

Business owners and finance teams familiar with FDs but not necessarily familiar with mutual funds or digital corporate investing. Use the awareness principle associated with Breakthrough Advertising: begin with a familiar situation and desire, then explain the problem, category, mechanism and commitment. No quotations from the book.

Revised sequence: direct FD-to-liquid-fund introduction → recognisable Pazy finance customers → benefits and balanced FD comparison → institutional category adoption → digital onboarding benefits → interactive product preview → named customer stories → verifiable registration, security and ownership → four-step process → direct pricing → objections → register.

This page must make category discovery possible without an account. The landing page assumes visitors already invest surplus. It does not make them complete a cash-planning calculator before learning about the category. Registration captures their surplus and timing.

## Claims and evidence

- User specifies digital documents, fund discovery and portfolio visibility, with a new registration → INR 199 → KYC approval → INR 5,000 setup funnel.
- Exact linked source inspected in connected Chrome on 10 November 2026: https://www.pazy.io/lp/treasury. It currently advertises INR 5,000 once, not the new INR 199 payment. The design intentionally uses the user's new proposal, with both payments disclosed together.
- Source lists an AMFI distributor ARN-364831, BSE StAR MF execution, units in the company's name, company document checklist, a INR 5 lakh surplus starting point and a distributor commission disclosure. Do not imply SEBI endorsement, guaranteed returns or that Pazy holds invested principal.
- Source's 500+ business proof is Pazy-wide, not demonstrated Treasury adoption. Prefer verifiable process and registration proof; no invented customer quotes, logos, AUM or conversion statistics.
- AMFI risk information: https://www.amfiindia.com/investor/knowledge-center-info?zoneName=riskInMutualFunds. Mutual funds can lose principal and returns are not guaranteed.
- AMFI KYC guide: https://www.amfiindia.com/kyc. Corporate requirements depend on entity type and additional declarations may be needed.
- AMFI investor service information: https://www.amfiindia.com/investor/become-mf-distributor?zoneName=InvestorService. Show latest available NAV and a data date, not an intraday price feed.
- Do not repeat blanket instant corporate redemption, no-exit-charge, FD lock-in, FD underperformance or universal T+1 promises. Redemption timelines, exit loads, cut-offs and deposit conditions vary.

## Funnel

Native full-page transitions, not a modal signup or payment popup. Four-step progress indicator: Account / INR 199 / KYC / Setup.

Registration: name, work email, company and mobile; role, surplus and horizon use concise choices and reuse landing-page inputs. The linked offer starts at INR 5 lakh surplus; below-threshold visitors receive an inline explanation before payment.

INR 199: explicit onboarding payment, separate from investment principal and the later INR 5,000 setup fee. Both proposed charges total INR 5,199 before confirming tax treatment. No invented refund or credit policy.

KYC: sample-only digital checklist of bank proof, entity PAN, entity authorisation/board resolution, signatories and account-opening form. Demonstrate submission, review pending, correction requested, resubmission and approval. Actual uploads, verification and approval are not connected. Setup fee remains gated on approval.

Setup: show already-paid INR 199, INR 5,000 due now, total proposed fees INR 5,199 and investment principal separate. Final state has zero invested, with a next step to compare scheme information. No investment transaction is executed.

## Launch questions

Confirm the purpose and refund/credit treatment of INR 199, tax treatment, setup-fee inclusions, entity-specific KYC requirements, actual review timelines, current distribution disclosures and redemption information before a live launch. These do not block building a truthful private design prototype.

## Visual implementation and checks

Matched the section concepts' true-white, forest, pale-green and lime system; cash-calendar hero; cash-allocation bar; FD comparison; three-step digital explanation; interactive product tabs; custody flow; fee ledger; and native full-page forms. The unrequested notebook photography and invented mark in one concept were intentionally omitted. The Pazy wordmark remains text-based. All diagrams, icons and values are code-native rather than rasterized UI.

Reviewed the rendered desktop hero against the concept for typography, line breaks, palette, spacing, CTA hierarchy, calendar geometry and trust-strip placement. No horizontal desktop overflow. Mobile CSS stacks sections, preserves the timeline and comparison, uses native full-page onboarding, and adds a compact bottom CTA.

Functional checks in shared Chrome:

- INR 50L cash minus INR 20L buffer produces INR 30L potential surplus.
- Buffer greater than total cash shows an inline error and disables carrying the plan into registration.
- Planner context carries into account creation; registration validates required fields and checks the INR 5L offer threshold before any onboarding payment.
- Payment pending disables a duplicate payment attempt. A failed INR 199 payment preserves the account; retry continues to KYC.
- Direct setup navigation before approval is blocked.
- KYC correction leaves INR 199 paid and four unaffected sample documents attached; replacing bank proof allows resubmission.
- Only approved KYC opens the INR 5,000 step. A failed setup payment preserves approved KYC and the initial receipt.
- Completion shows INR 5,199 total proposed fees and INR 0 invested; an investment order is never placed.
- Document and entity changes invalidate verification while retaining historical payment state. Changes do not silently erase a paid receipt or create a second setup charge.
- JavaScript syntax check passes. Payments, KYC and uploaded documents are simulations only; refresh starts a new preview session.


## November 10 revision: FD users discovering mutual funds

Hero: “Already use FDs? Meet liquid mutual funds.” Secondary hero CTA is Pricing; a persistent desktop/mobile dock includes Pricing and Get started. Native illustration replaces the cash calendar with fixed-tenure versus open-ended investing and partial redemption.

Three proof layers remain explicitly distinct:
- Familiar customer names and linked customer stories from https://www.pazy.io/customers establish Pazy-wide finance credibility, not Treasury adoption. Sprinto quote is the exact 22-word passage attributed to Naga Subramanya on the linked Sprinto case study. WhiteGold's linked published story reports 100+ hours saved per month in finance operations. Neither is presented as an investment outcome.
- AMFI Industry Trends August 2025, page 4: institutional investors held 89% of liquid/money-market mutual-fund assets. Denominator and historical date are explicit. Institutions include domestic and foreign institutions and banks. https://www.amfiindia.com/uploads/1_Industry_Trends_Aug_2025_aba4ae3ba6.pdf
- Registration, BSE routing, company folio ownership and published Pazy security credentials are separately visible. Security credentials do not imply investment safety. Pazy's customer page publishes SOC 2 Type II and ISO 27001.

Comparison emphasises flexible access, partial redemptions and choice. It does not assert guaranteed higher returns, penalty-free withdrawals or no FD flexibility. Operating cash is kept separate; no numerical return projection is invented. AMFI primary investor education supports the open-ended category and typical next-business-day liquid/overnight redemption, with scheme terms and cut-offs disclosed.

Pricing: “₹199 to start. ₹5,000 after KYC approval.” Total service fees ₹5,199. Tax, refund/credit and final fee inclusions remain unconfirmed prototype policies. No real checkout or verification service is connected.

Revision verification: JavaScript syntax passed. Desktop 1363px and responsive 390px iframe (375px content viewport after scrollbar) have no horizontal overflow. Hero and persistent Pricing links reach the pricing section. Interactive Documents and Compare tabs render correctly. The complete sample registration → ₹199 → company documents → pending KYC → approved KYC → ₹5,000 → completion journey passes, with ₹5,199 shown separately from ₹0 invested. The pending review correctly locks setup payment. Desktop and mobile layouts were inspected visually; the responsive check is a temporary development harness excluded from publication.


## Revision: two comparisons, concrete earnings and media proof

Company-specific hero: “Already invest company cash in FDs? Meet liquid mutual funds.”

Comparison 1 separates current account, fixed deposit and liquid mutual fund. Calculator: surplus in lakh, user-supplied illustrative FD quote, 30/90/365 days. Current-account 0%; liquid illustration uses verified HDFC Regular Growth historical one-year return 6.36%, not a forecast. Calculation is simple interest, no future return promise. The default FD input 6% is an assumption, never a bank offer. Signed delta correctly handles FD outperformance. Fees ₹5,199 remain explicit and separate. Valid surplus carries into registration.

Actual named fund examples use Regular Growth, same 30 September 2026 date:
- HDFC Liquid Fund 6.36%; HDFC September 2026 factsheet printed p74: https://files.hdfcfund.com/s3fs-public/2026-10/HDFC%20MF%20Factsheet%20-%20September%202026.pdf?VersionId=xjdQxQp4UEchOirw4TsCE9jEGenOREzw
- Nippon India Liquid Fund 6.37%: https://mf.nipponindiaim.com/FundsAndPerformance/Pages/NipponIndia-Liquid-Fund.aspx (September version verified via indexed official product page with campaign parameters; some requests retrieve an older snapshot).
- ICICI Prudential Liquid Fund 6.34%: https://www.icicipruamc.com/mutual-fund/debt-funds/icici-prudential-liquid-fund/13 . Official indexed page explicitly identifies Regular Growth, one-year CAGR, date Sep30 2026.
Rupee fund illustrations use selected amount times the rounded published one-year rate; they always describe the past one-year period, even when the upper calculator uses 30/90 days. NAV-based returns already reflect expenses. Tax, exit loads and Pazy fees are not deducted. The screenshot's category rates 6.6/6.6/6.5 are not repeated as scheme returns.

Comparison 2: a typical manual broker/dealing desk workflow vs Pazy across digital KYC, fund filtering, maker-checker roles/limits, holdings/redemption, Tally/ERP accounting, and cash/payables visibility. Pazy feature basis: https://www.pazy.io/treasury and the user-supplied reference. Do not assert all brokers lack digital controls; integration support depends on configuration. No universal instant corporate redemption promise.

Media proof: June2025 ₹6 crore pre-seed led by Inuka Capital with Gemba Capital participation. YourStory daily roundup June27 and CXOToday media coverage June25. Names/logos link to specific coverage, not implied endorsement of funds.
- https://yourstory.com/2025/06/startup-news-and-updates-daily-roundup-june-27-2025
- https://cxotoday.com/media-coverage/pazy-raises-%E2%82%B96-crore-in-pre-seed-funding-to-simplify-b2b-payments/
Logos are local copies of actual publisher/fund-house assets, not generated marks: YourStory headerV3_YS.svg, CXOToday cxo-logo.png, HDFC and ICICI assets linked from Pazy's Treasury page, Nippon logo from its official product page.

Latest checks: JavaScript syntax passes. Desktop calculator default25L/6%/365days yields FD150000 and HDFC illustration159000, delta9000. At50L/7%/90days it correctly shows FD86301 vs liquid78411, delta7890 below FD. Empty surplus shows inline error and suppresses computed gains. Changed surplus50L carries into registration. Named-fund illustrations remain explicitly one-year past-period results and update with amount only. All three fund logos and both publisher logos load locally. Desktop has no horizontal overflow. A contrast issue in the workflow table header found during browser QA was corrected.

Mobile QA: 390px iframe /375px content has no horizontal page overflow. Workflow comparison becomes two visible side-by-side cells per task, with manual and Pazy labels; no horizontal swipe required. Numeric input,30day toggle,company headline and sticky CTA render correctly. Final source excludes temporary responsive harness.


## Sharper comparison and simpler registration revision

Default company surplus is explicitly1 Crore, with a native Lakh/Crore unit selector. Converting units preserves the cash amount. Default annual gains: current0, FD600000 at assumed6%, liquid636000 using historical HDFC6.36%; positive/negative differences remain correct. Gain is the visible label; calculation assumptions remain available below. The separate fees tile under the comparison is removed.

Bright lime replaces dark green for the liquid-fund card and both comparison benefit columns. Red marks0% interest, fixed tenure/possible early-exit cost and manual desk friction. Short comparison cells replace paragraphs. A paired tenure callout prominently contrasts fixed tenure/possible early-exit cost with no fixed maturity/partial redemption. FD terms, flexi/sweep differences, scheme cutoff and settlement conditions remain a compact note. Mobile shows all three access columns and both process columns without horizontal scrolling.

Fund examples expand to six in two rows. New: Kotak Arbitrage Fund RegularGrowth6.14%1Y asof31Oct2026 (https://www.kotakmf.com/mutual-funds/hybrid-funds/kotak-arbitrage-fund/reg-g). SBI Overnight and ABSL UltraShortTerm (formerlySavings) are category-discovery cards linking to official current AMC information; no unverified scheme returns are invented. Current product names/categories verified from official AMC pages. SBI sourcehttps://www.sbimf.com/factsheets; ABSLsourcehttps://mutualfund.adityabirlacapital.com/saving-solutions/aditya-birla-sun-life-savings-fund. Different categories are not represented as interchangeable liquid funds.

Customer proof expands from five names to ten, two desktop rows: Pratilipi,Pilgrim,Inc42,Sprinto,OSMOS,Mygate,Plum,Fibe,UrbanPiper,Jar. Added logo assets are original images published on https://www.pazy.io/customers. Pazy-wide finance context remains explicit.

Registration now has five inputs:name,workemail,company,mobile,surplus. Role,evaluationtiming,registrationcheckbox,and preregistrationfee/disclaimerbox are removed. The summary sidebar is omitted only for registration; pricing remains on the landing page and fee receipts remain at payment steps. Removed timing from downstream summary and cleaned unused calculator state.

Checks: syntax passes. Browser confirms default1crore gives636000liquid/600000FD; conversion to100lakh preserves gains; changed50lakh carries into registration. New signup has no select/checkbox/fee box. Full sample registration→199→KYCpending→approved→5000→ready passes; pending approval still locks setup. Allsixfundlogosload; desktop no horizontal overflow.

Final responsive check:390pxiframe/375pxcontent has no horizontal overflow; allthree access comparison columns are visible. Registration DOM has exactlyfiveinputs,zerocheckboxes,zeroselects,zerofeeboxes. Temporary responsive harness removed before packaging.
