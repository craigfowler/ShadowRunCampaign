# ENCRYPTED PAYDATA EXTRACT - FORENSIC RECOVERY

```txt
Source: Commlink SIN-Masked / Owner: [REDACTED]
Recovery Date: [CURRENT]
Decryption Status: PARTIAL / Multiple Archive Fragments
```

## FILE CLUSTER A - TRANSACTION LOGS (FRAGMENTED)

### TXN-LOG-447.dat

```txt
[2072-06-14 03:22:18] INCOMING WIRE: ¥487,000
Origin: Cayman Banking Collective (Shell Corp: "Meridian Imports Ltd")
Destination: Seattle Credit Union / Account #4478-9821-CC
Purpose Code: CONSULTING SERVICES
Processing Fee: ¥2,435 (0.5%)
Notes: Monthly payment cycle 3/12. Client ref: YAKASHIMA-PRIME
```

### TXN-LOG-451.dat

```txt
[2072-06-18 11:47:03] OUTGOING WIRE: ¥125,000
Origin: Seattle Credit Union / Account #4478-9821-CC
Destination: Hong Kong Free Enterprise Zone / Account #VK-8847-GHOST
Purpose Code: MATERIAL ACQUISITION
Processing Fee: ¥625 (0.5%)
Notes: Payment for merchandise as discussed. NO FURTHER CONTACT.
```

### TXN-LOG-468.dat

```txt
[2072-06-23 19:33:51] INCOMING WIRE: ¥2,340,000
Origin: Zurich-Orbital Gemeinschaft Bank (Shell: "Pacific Wellness Holdings")
Destination: First Seattle Independent / Account #GHOST-7741
Purpose Code: PROPERTY INVESTMENT
Processing Fee: ¥11,700 (0.5%)
Notes: URGENT - Client requires discrete handling. VIP status confirmed.
```

## FILE CLUSTER B - COMMUNICATIONS ARCHIVE

### MEMO-Internal-092375.msg

FROM: [REDACTED]  
TO: Associates (Encrypted Distribution List)  
DATE: 2072-06-23  
SUBJECT: COURIER PROTOCOL - ASSET TRANSFER; DESTINATION MCT CONTACT

Recent heat from Knight Errant downtown ops means we're implementing multi-stage courier protocol for the MCT payment transfer. Client is paranoid (rightfully so) about intercepts. Package contains encrypted certified credstick (¥850K) plus delivery instructions for final recipient.

#### OPERATIONAL SECURITY REQUIREMENTS

- No single courier knows full chain
- Each receives sealed package + instructions for next handoff only
- No matrix communication between stages
- 24-hour window from initiation to completion
- Credstick payload is encrypted, has no value without decrypt key

#### CHAIN OUTLINE:

Stage 1: Dead drop retrieval (Downtown)  
Stage 2-4: Physical handoffs (locations TBD by each courier's instructions)  
Stage 5: Final delivery (destination known only to final courier)

#### STAGE 1 DETAILS:

- Pickup Location: Downtown Seattle, Westlake Avenue & Pine Street, third floor parking garage, level 3, space 3-47J (maintenance closet, false panel behind cleaning supplies rack)
- Pickup Window: 2072-06-25, 22:00-23:00 hours
- Courier Assigned: Marcus "Slim" Toivonen (BTL runner, reliable, owes us)
- Recognition: Package wrapped in brown synthleather, sealed with red wax, marked with Yakuza mon
- Payment: ¥5,000 (already transferred to his account)
- Next Handoff: Instructions enclosed in package (Slim only knows his drop-off point: Tacoma docks, Pier 47, 0200 hours, handoff to "Red")

Do NOT contact Slim directly. He's been briefed by cutout already. If he doesn't show, package auto-incinerates after 24 hours.

Client contact reports increased Shotozumi-gumi surveillance in Tacoma sector. Advise all couriers to vary routes and stay off main arterials.

### MEMO-Internal-091875.msg

FROM: [REDACTED]  
TO: V. Kowalski  
DATE: 2072-06-18  
SUBJECT: RE: Discrepancies in Horizon Account

Viktor,

The Horizon Media shell account shows a ¥340K shortfall from last month's expected throughput. I've reviewed the subsidiary transactions and found three payments that were coded incorrectly - they went through the wrong processing chain and got flagged by their internal audit algorithms.

This is exactly the kind of sloppiness that gets people disappeared. Fix the routing and get me a clean report by Friday, or find yourself another accountant.

The Finnigans also want to know why their monthly take is down 15%. I told them market conditions, but they're not buying it. Prepare a breakdown showing the increased Knight Errant activity in their territories is cutting into street-level operations.

## FILE CLUSTER C - CLIENT PROFILES (PARTIAL)

### CLIENT-PROFILE-YAK-PRIME.enc

```txt
Organization: Yakashima-rengo (Yakuza, Seattle Branch)
Primary Contact: [ENCRYPTED]
Account Status: PLATINUM
Monthly Volume: ¥2.4M - ¥3.8M average
Services Rendered: Wire transfers, credstick certification, property acquisition (front companies), offshore accounts
Risk Assessment: HIGH - Major syndicate, significant Knight Errant attention
Notes: Demand absolute discretion. Never use matrix for sensitive comms. Prefer physical transfers for amounts >¥500K. Extremely punctual with payments.
```

### CLIENT-PROFILE-FINNIGAN.enc

```txt
Organization: Finnigan Family (Irish Mob, Tacoma/Downtown)
Primary Contact: [ENCRYPTED]
Account Status: GOLD
Monthly Volume: ¥800K - ¥1.2M average
Services Rendered: Standard laundering, casino front operations, BTL distribution network support
Risk Assessment: MEDIUM - Well-connected but increasingly volatile
Notes: Colm Finnigan getting paranoid about internal security. Third audit request this quarter. Consider increasing service fees due to extra work involved.
```

### CLIENT-PROFILE-SHEN-LOGISTICS.enc

```txt
Organization: Shen Logistics Network (Triad-affiliated, Hmong operations)
Primary Contact: [ENCRYPTED]
Account Status: SILVER
Monthly Volume: ¥400K - ¥650K average
Services Rendered: Import/export documentation, customs bribery coordination, smuggling route finance
Risk Assessment: LOW-MEDIUM - Discrete operations, minimal law enforcement profile
Notes: Always pay on time. Never complain. Good client. Recommend maintaining relationship.
```

## FILE CLUSTER D - MISCELLANEOUS NOTES

### NOTES-Personal-092275.txt

- Remind Viktor about the Aurora Club receipts - need those categorized as "marketing expenses" for the Meridian shell
- Check with Kenji about the Redmond warehouse property - Yakashima wants clean title by end of month
- URGENT: KE forensic accountant (Badge #4477) asking questions about Pacific Wellness Holdings. Might need to burn that shell and create new structure. Consult lawyer.
- Casino night Thursday - Don't forget to comp Big Eddie's table (owes us for last month's work on his Barrens operation)
- New credstick certification machine arrives Monday - should speed up the high-value physical transfers
- Consider increasing fees across the board - too much heat lately, not worth standard rates

### NOTES-Operational-092075.txt

#### SECURITY CONCERNS

- Increased matrix surveillance on known accounts (likely corp or gov)
- Two clients reported suspicious tails last week
- Recommend all face-to-face meetings move to randomized locations
- Consider temporary suspension of new client intake

#### UPCOMING HIGH-VALUE TRANSFERS

- MCT credstick package (¥850K) - multi-stage courier scheduled
- Finnigan casino skim (¥220K) - standard wire transfer to Cayman shell
- Shen import payment (¥180K) - routed through three intermediaries, finalizes 09-28


## FILE CLUSTER E - LOW-TIER CLIENT TRANSACTIONS

### TXN-LOG-512.dat

```txt
[2072-06-08 14:23:47] INCOMING CASH DEPOSIT: ¥18,500
Origin: PHYSICAL DEPOSIT (Dead Drop Charlie-7, Redmond)
Destination: Seattle Credit Union / Account #4478-9821-CC
Client Code: CRIMSON-CRUSH-STREET
Processing Fee: ¥925 (5% - high risk surcharge)
Notes: Weekly BTL distribution take. Cash quality poor (small denominations, heavy coin mix). Deposit processed through three intermediary accounts before integration.
```

### TXN-LOG-524.dat

```txt
[2072-06-12 09:15:33] OUTGOING WIRE: ¥15,200
Origin: First Seattle Independent / Account #GHOST-7741
Destination: Aztechnology Trade Credit Union / Account #RED-BARRENS-447
Purpose Code: EQUIPMENT PURCHASE
Client Code: CRIMSON-CRUSH-STREET
Processing Fee: ¥760 (5%)
Notes: Payment to weapons dealer (verified via cutout). Buyer wanted clean wire to avoid physical meet. Delivered as requested.
```

### TXN-LOG-531.dat

```txt
[2072-06-15 22:47:19] INCOMING CASH DEPOSIT: ¥24,300
Origin: PHYSICAL DEPOSIT (Dead Drop Charlie-7, Redmond)
Destination: Seattle Credit Union / Account #4478-9821-CC
Client Code: CRIMSON-CRUSH-STREET
Processing Fee: ¥1,215 (5%)
Notes: Biweekly protection/extortion collection. Usual Redmond Barrens territory take. Contact reports Crush expanding operations into Touristville fringe areas - expect volume increase.
```

### TXN-LOG-547.dat

```txt
[2072-06-19 16:33:08] INCOMING WIRE: ¥8,900
Origin: Hong Kong Free Enterprise Zone / Account #ANON-774-KK
Destination: First Seattle Independent / Account #GHOST-7741
Client Code: HALLOWEENERS-RDM
Processing Fee: ¥445 (5%)
Notes: Return payment from explosives supplier. Client overpaid last month, supplier actually honest (surprising). Forwarding to gang lieutenant's credstick.
```

### TXN-LOG-556.dat

```txt
[2072-06-21 11:08:52] OUTGOING CREDSTICK CERT: ¥6,500
Origin: Seattle Credit Union / Account #4478-9821-CC
Destination: CERTIFIED CREDSTICK #CS-8847-RED
Client Code: SPIKES-DT
Processing Fee: ¥325 (5%)
Notes: The Spikes (Downtown go-gang) paying off gambling debts to Finnigan casino operation. Credstick certified and ready for pickup at usual location (Big Rhino bar, back office).
```

## FILE CLUSTER F - CRIMSON CRUSH OPERATIONAL FILES

### MEMO-Client-060572.msg

FROM: [REDACTED]  
TO: Collections Team  
DATE: 2072-06-05  
SUBJECT: Crimson Crush - Payment Schedule Adjustment

The Crush are actually getting their drek together lately. Their new lieutenant (some ork named "Sledge" who supposedly ran with real shadowrunners before going gang-side) has been pushing them to be more professional about their business.

#### UPDATED PROTOCOLS

- Weekly BTL distribution deposits (Thursdays, Dead Drop Charlie-7)
- Biweekly protection collection deposits (alternating Mondays, same dead drop)
- They want faster turnaround on wire transfers (down from 72hrs to 48hrs)
- Requesting credstick certification services for amounts >¥10K

I'm adding 5% surcharge for gang-tier clients (up from 3%) due to increased KE gang task force activity in Redmond. If Sledge complains, remind him we're the only game in town that doesn't ask questions and doesn't keep records that can be subpoenaed.

Also - they're asking about bulk novacoke processing payments. Apparently they've got a new supplier pipeline and want to move ¥50K+ monthly. I told them we'd consider it but need 10% fee for that volume from street-level operators. Waiting on response.

#### RISK ASSESSMENT UPDATE

The Crush have been hitting Touristville businesses pretty hard. Lone Star is basically non-existent out there, but if they push into areas where actual corps have property, we might see Knight Errant intervention. Keep monitoring. If heat gets too intense, we suspend services temporarily.

### MEMO-Client-061872.msg

FROM: [REDACTED]  
TO: V. Kowalski  
DATE: 2072-06-18  
SUBJECT: RE: Crimson Crush Credstick Request

Viktor,

Sledge came through with the novacoke processing agreement. Starting next month, we're handling ¥50-75K monthly from their distribution network. This is actually decent money for a gang-tier client.

He also requested something unusual: wants us to set up a "legitimate" front company for the Crush. Something about cleaning up their image and running some actual legal businesses as cover. I think he's trying to move them from street gang to organized crime tier.

I quoted him ¥25K setup fee plus 7% monthly on all transactions through the company. He didn't flinch. Either the Crush are making serious bank, or Sledge has ambitions.

#### FRONT COMPANY PROPOSAL

- Name: "Redmond Security Solutions LLC"
- Business Type: Private security contractor (perfectly legal in the Barrens)
- Shell Structure: Standard single-layer (should be sufficient for gang-level scrutiny)
- Banking: Seattle Credit Union business account
- SIN Registration: Using our usual forged corporate SIN service

Set this up by end of month if Sledge confirms payment.

One concern: If the Crush are getting this sophisticated, they might attract attention from bigger players. Yakuza won't like a gang getting delusions of grandeur in territory adjacent to their interests. Keep this compartmentalized from our other clients.

## FILE CLUSTER G - CORPORATE CLIENT (DEEP COVER)

```txt
File integrity: Insecure deletion
Shred protocol: Failed
```

### TXN-LOG-489.dat

```txt
[2072-06-03 08:44:21] INCOMING WIRE: ¥1,840,000
Origin: Swiss Collective Banking / Account #ZURICH-PHANTOM-8847-CC
Intermediary: Cayman Banking Collective / Shell Corp: "Pacific Microsystems Ltd"
Intermediary: Singapore Free Trade / Shell Corp: "Helix Advanced Materials Inc"
Final Destination: First Seattle Independent / Account #SHADOW-PRIME-001
Purpose Code: RESEARCH & DEVELOPMENT INVESTMENT
Processing Fee: ¥9,200 (0.5% - premium tier)
Notes: HIGHEST CONFIDENTIALITY. Monthly installment 6/12. Client reference: MITSUHAMA-GHOST-BIOTECH. Three-layer shell structure maintained. NO DIRECT CONTACT.
```

### TXN-LOG-503.dat

```txt
[2072-06-10 19:27:44] OUTGOING WIRE: ¥780,000
Origin: First Seattle Independent / Account #SHADOW-PRIME-001
Destination: Denver Banking Consortium / Account #GHOST-RESEARCH-447
Purpose Code: CONTRACTOR PAYMENT
Processing Fee: ¥3,900 (0.5%)
Notes: Payment to research facility (unregistered biotech lab, per client specs). Facility operating outside standard regulatory framework. Client insists on complete paper trail elimination.
```

### TXN-LOG-521.dat

```txt
[2072-06-14 03:15:37] INCOMING WIRE: ¥340,000
Origin: Singapore Free Trade / Shell Corp: "Helix Advanced Materials Inc"
Destination: First Seattle Independent / Account #SHADOW-PRIME-001
Purpose Code: EQUIPMENT ACQUISITION
Processing Fee: ¥1,700 (0.5%)
Notes: Additional funding for specimen procurement and containment systems. Client reference: MCT-GHOST-BIOTECH. URGENT processing required.
```

### MEMO-Internal-EYES-ONLY-060172.msg

FROM: [REDACTED]  
TO: [ENCRYPTED - NO DISTRIBUTION]  
DATE: 2072-06-01  
SUBJECT: CRITICAL - MITSUHAMA GHOST OPERATION

This memo exists in physical backup only. Destroy after reading.

We have been retained by Mitsuhama Computer Technologies via an extremely complex cutout structure. This is far beyond our usual scope, but the fees are extraordinary (¥9-10K monthly just in processing fees, plus ¥50K retainer).

#### CLIENT STRUCTURE

- Ultimate Client: Mitsuhama Computer Technologies (MCT) - Mega-corporate, AAA-rated
- Controlling Division: Parashield Genetics Division (subsidiary, 87% MCT-owned)
- Operational Cover: "Helix Advanced Materials Inc" (Singapore shell, two layers deep)
- Financial Cover: "Pacific Microsystems Ltd" (Cayman shell, primary payment routing)
- Final Processing: Our standard shadow accounts

#### PURPOSE

MCT is funding an illegal biotech research operation in the Denver Free Zone. The facility is conducting research that violates UCAS bioethics regulations and multiple international treaties. They're using our services to create an untraceable financial pipeline from MCT corporate funds to the black lab.

#### WHY THIS IS DANGEROUS

If this connection is ever exposed, MCT would face:

- UCAS federal investigation and potential AAA rating challenge
- International sanctions
- Massive stock devaluation
- Criminal charges against executives

For us, exposure means:

- Certain corporate retaliation (MCT has zero tolerance for loose ends)
- UCAS federal prosecution
- Every other client dropping us immediately

#### OPSEC REQUIREMENTS

- NO matrix communication regarding this client (physical meetings only)
- NO documentation stored on matrix-connected systems
- ALL records triple-encrypted with self-destruct protocols
- NO mention of "Mitsuhama" or "MCT" in any standard files (use code: GHOST-BIOTECH)
- Monthly security audit of all related accounts and shells
- Maintain plausible deniability at ALL times

#### FINANCIAL DETAILS

Monthly flow: ¥1.8-2.2M from MCT → Black lab operations
Processing occurs 1st-5th of each month
Payment chain: Zurich → Cayman → Singapore → Our accounts → Denver facility
Shell companies refreshed every 6 months (next refresh: August 2072)

#### SHELL COMPANY DETAILS - COMPLETE CHAIN

Layer 1: "Pacific Microsystems Ltd"

- Registration: Cayman Banking Collective, Corporate Registry #CM-8847-TECH
- Stated Business: Technology consulting and equipment sales
- Directors: Three ghost SINs (maintained by our Hong Kong forger)
- Banking: Cayman Corporate Credit Union, Account #CC-PACIFIC-8847
- Tax Status: Zero-tax jurisdiction, annual filing fee ¥15K
- Ownership: Nominee shareholders (untraceable to MCT)

Layer 2: "Helix Advanced Materials Inc"

- Registration: Singapore Free Trade Zone, Corporate Registry #SG-HELIX-4477
- Stated Business: Industrial materials research and development
- Directors: Two ghost SINs plus one legitimate (bribed) Singapore resident
- Banking: Singapore International Trust, Account #SG-HELIX-RESEARCH
- Tax Status: Free trade zone benefits, minimal reporting requirements
- Ownership Structure: 100% owned by Pacific Microsystems Ltd (creating separation from MCT)
- Additional Cover: Maintains small legitimate materials import business (annual revenue ¥200K) to justify existence

Layer 3: Parashield Genetics Division (MCT Subsidiary)

- Parent Corporation: Mitsuhama Computer Technologies (87% ownership)
- Stated Business: Legitimate genetic research and pharmaceutical development
- Public Profile: Well-known MCT subsidiary, publicly traded component
- Hidden Connection: Parashield executive VP (name encrypted in separate file) personally authorizes ghost payments
- Payment Authorization: Routed through "R&D discretionary fund" (¥50M annual budget, our payments buried in legitimate expenses)

#### COMPLETE MONEY FLOW

1. Parashield Genetics "discretionary R&D budget" → Swiss Collective Banking (¥2M monthly average)
2. Swiss account → Pacific Microsystems Ltd / Cayman (appears as "consulting payment")
3. Pacific Microsystems → Helix Advanced Materials / Singapore (appears as "materials research investment")
4. Helix Advanced Materials → Our shadow accounts (appears as "contractor payment")
5. Our accounts → Denver black lab facility (final destination, untraceable to MCT)

#### CRITICAL EVIDENCE IN OUR POSSESSION

- Complete transaction logs showing full payment chain (this file system)
- Corporate registration documents for both shell companies
- Ghost SIN details for nominee directors
- Banking access credentials for Cayman and Singapore accounts
- Encrypted communications with MCT handler (stored offline)
- Facility location and operational details for Denver lab
- Names of three Parashield executives involved in authorization chain

#### THREAT ASSESSMENT

This information, if exposed, represents a COMPLETE and IRREFUTABLE connection between MCT and illegal biotech research. Any competent investigator (corporate, federal, or shadowrunner) could use this data to:

- Prove MCT's illegal activities beyond reasonable doubt
- Identify specific executives for prosecution
- Seize assets from shell companies
- Shut down the Denver facility
- Trigger AAA rating review and international sanctions

MCT would pay EXTRAORDINARY amounts to recover or destroy this evidence. They would also eliminate anyone who possessed it with extreme prejudice. We are sitting on a potential ¥50-100M payday if sold to MCT competitors (Renraku, Shiawase, or Aztechnology would all be interested), but also a death sentence if we're exposed.

#### SECURITY PROTOCOL

- This memo stored on air-gapped system only
- Physical backup in secure location (safety deposit box, Singapore)
- Dead man's switch: If I disappear, encrypted copies auto-release to three major news organizations and DocWagon legal department
- Monthly verification that switch is still armed
- NO discussion of this client with anyone, including Viktor

The money is incredible, but this is the most dangerous client we've ever handled. One mistake and we're all dead.

## FILE CLUSTER H - GANG CLIENT MISCELLANEOUS

### NOTES-Collections-061272.txt

GANG TIER CLIENT UPDATES:

Crimson Crush (Redmond):

- Reliable payments, improving organization
- New lieutenant "Sledge" is professional (for a ganger)
- Expanding operations, increasing volume
- Requested front company setup - approved, in progress
- Watch for: Potential conflict with Yakuza if they expand too far west

Halloweeners (Redmond):

- Chaotic but consistent
- Mostly small-time (¥5-15K monthly)
- Explosives purchases make me nervous, but they pay on time
- Multiple contacts, no clear leadership (typical)

The Spikes (Downtown):

- Go-gang, moderate volume (¥10-20K monthly)
- Primarily gambling debts and bike part purchases
- Professional enough for gang-tier
- Good relationship with Finnigan operations (we broker some of their payments)

Ancients (Various):

- Approached us last month, declined service
- Too high-profile, too much elf poser politics
- Don't need the attention they'd bring

Brain Eaters (Redmond/Puyallup):

- Contacted via dead drop, requesting services
- DECLINED - cannibals are bad for business image
- Also, just... no.

### MEMO-Internal-061572.msg

FROM: [REDACTED]  
TO: Collections Team  
DATE: 2072-06-15  
SUBJECT: Crimson Crush Expansion - Monitoring Required

Sledge's ambitions are becoming clearer. The Crush aren't just hitting Touristville anymore - they're systematically taking over every racket in a six-block radius of their core territory.

Latest intelligence (from street contacts):

- Pushed out three smaller gangs in past two months
- Recruited or eliminated rival BTL dealers
- Established protection racket covering 40+ businesses
- Running novacoke distribution network with actual supply chain management

This is either very good (professional client with growing revenue) or very bad (they're going to attract attention that spills onto us).

I want weekly updates on Crush activity. If Knight Errant Gang Task Force starts sniffing around their operations, we suspend services immediately and distance ourselves.

Also - Sledge asked if we handle "wetwork" payments. I told him no, that's not our specialty, but I gave him a contact reference (someone else's problem). He said he might need "corporate-quality cleanup" for their expansion. This ork is thinking way above street-gang level.

Keep eyes on this situation.

## END OF RECOVERED DATA

## Forensic Analysis Notes

- Multiple encrypted layers suggest high-value criminal financial operations
- Data recovery approximately 60% complete
- Owner appears to be professional money launderer serving multiple criminal organizations
- Geographic focus: Seattle metroplex
- Time period: June 2072

### Exposure of MCT

- Critical corporate connection identified (Mitsuhama Computer Technologies)
- Evidence suggests high-value intelligence compromise
- Recommendation: Secure data immediately, assess potential threats
- Criminal exposure risk: EXTREME for multiple parties
