# Licensing Requirements

1. Microsoft 365 E7
2. Microsoft 365 Copilot
3. Microsoft SharePoint Tenant enrolled in Frontier preview
4. Microsoft 365 Tenant with Copilot Credits policy applied

<a id="start"></a>

# Ignite 2026 Knowledge Base Lab

* **Track A:** Create a knowledge base from scratch for the EagleFord sales account (3 tasks).
* **Track B:** Explore a shared Field Knowledge knowledge base for a property management account (10 tasks). *In-person only; not available to on-demand lab users.*
* **Track C:** Use the EagleFord Account Knowledge Base you created in Track A (4 tasks).

*All names are fictional.*

* * *

<a id="tasks"></a>

## Task list

**On your own:** work through the task at your own pace.**MC-led:** follow along as the presenter walks through the task.

| Task | Mode |
| --- | --- |
| [Lab setup (everyone)](#setup) | On your own |
| **Track A · Create a knowledge base from scratch** |     |
| [A1 · Get the source files](#a1) | On your own |
| [A2 · Upload the files](#a2) | On your own |
| [A3 · Create the knowledge base](#a3) | On your own |
| **Track B · Explore the shared Field Knowledge knowledge base** *(in-person only; not available to on-demand lab users)* |     |
| [B1 · Open the shared knowledge base](#b1) | On your own |
| [B2 · Prep for a furnace repair](#b2) | MC-led |
| [B3 · Check for safety risks before a visit](#b3) | MC-led |
| [B4 · Compare two furnace models](#b4) | MC-led |
| [B5 · Find what causes repeat visits](#b5) | MC-led |
| [B6 · Free exploration (5 min)](#b6) | On your own |
| [B7 · Log a new ticket](#b7) | MC-led |
| [B8 · Triage the ticket](#b8) | MC-led |
| [B9 · Assign the ticket](#b9) | MC-led |
| [B10 · Create a report](#b10) | MC-led |
| **Track C · Use the EagleFord knowledge base** |     |
| [C1 · Tour the knowledge base (2–3 min)](#c1) | On your own |
| [C2 · Find the open issues](#c2) | On your own |
| [C3 · Onboard a new team member](#c3) | On your own |
| [C4 · Create a meeting brief](#c4) | On your own |

* * *

<a id="setup"></a>

## Lab setup (everyone)

> **On-demand lab:** These steps are for online attendees using their own Microsoft 365 tenant.

### Requirements

You need all of the following:

1. Microsoft 365 E7
2. Microsoft 365 Copilot
3. Microsoft SharePoint tenant enrolled in the Frontier preview
4. Microsoft 365 tenant with a Copilot Credits policy applied

### Steps

1. Double-click the **Edge** browser on your desktop.
2. Open SharePoint.
3. Check that knowledge bases are available on your tenant: select **Build** in the left navigation and look for the **Knowledge base** tile. If you don't see it, check the requirements above.

[Back to task list](#tasks)

* * *

<a id="tracka"></a>

# Track A · Create a knowledge base from scratch

Northstar Systems sells FieldBridge procurement software to the fictional EagleFord Energy. You'll build an account knowledge base on your own site from 50 customer-interaction documents. Track C then uses it to find open issues, onboard a colleague, and prepare for a customer meeting.

You can do this track without doing Track B.

### Before you start: create your site

1. Click **Build** in the left navigation.
2. Under the **Start Building** header, select **Site > Team site > Standard Team**.
3. Name it with your name, for example `EagleFord Account - <your name>`. Click **Create site**.

* * *

<a id="a1"></a>

## A1 · Get the source files

### Steps

1. Download the **eagleford-sales-dataset** ZIP from the lab's GitHub repository to your **Downloads** folder.
2. Extract it in the **Downloads** folder (right-click the ZIP > **Extract All**). You now have an **eagleford-sales-dataset** folder with 50 account documents (Markdown) in five groups: discovery, solution design, validation, commercial, and delivery.

### Why it matters

These 50 files are a realistic account history (meetings, requirements, proposals and handoff notes) scattered across many documents. That's the raw material the knowledge base connects.

* * *

<a id="a2"></a>

## A2 · Upload the files

### Steps

1. Switch back to the browser tab with your EagleFord Account site.
2. Select **Documents** in the left navigation.
3. Click the **Create or upload** button in the upper right. Under **Upload**, select **Folder upload**.
4. Select the extracted **eagleford-sales-dataset** folder in **Downloads** and upload it.

### Why it matters

Upload the extracted folder, not the ZIP.

* * *

<a id="a3"></a>

## A3 · Create the knowledge base

### Steps

1. Select **Home** in the left navigation.
2. Click the **Copilot in SharePoint** icon in the lower right of your site.
3. Submit the prompt below. Approve credit use if asked.
4. Keep the Copilot in SharePoint pane open until Copilot reports it's done.
5. **EagleFord Account Knowledge Base** appears in the left navigation. If you don't see it, refresh the page. You'll use it in Track C.

### Submit this prompt

    Create a new SharePoint knowledge base named “EagleFord Account Knowledge Base” using all 50 EagleFord account documents in Documents. Its purpose is to give the account team a shared, reliable understanding of the customer relationship, from discovery and requirements through negotiations, implementation, and expansion opportunities. It is intended for account executives, sales engineers, customer success managers, implementation teams, and sales leadership. Organize the content into easy-to-navigate topics covering the account overview, stakeholders, customer needs, solution design, pilot results, commercial agreements, rollout progress, risks, and next steps. Clearly label the entire knowledge base as a fictional training simulation. Use the available SharePoint capabilities without using the KB skill.
    
    Read all 50 documents and connect related information rather than simply creating a separate summary for each file. Preserve important details, dates, decisions, owners, financial figures, and unresolved questions, with links to the supporting documents. Distinguish earlier proposals from final decisions, estimates from observed results, and completed actions from open items. Make clear that the latest source information is dated October 23, 2026. Use the knowledge base for meeting preparation, account planning, onboarding, sales-to-delivery handoffs, and answering account questions with supporting evidence. Do not invent missing information or include the unrelated musical-instrument support data. If you cannot access the destination or sources, explain what is needed and stop rather than substituting other material. Validate document coverage and links before reporting completion.

### Why it matters

Copilot connects the account knowledge across all 50 documents instead of writing 50 separate summaries.

[Back to task list](#tasks)

* * *

<a id="trackb"></a>

# Track B · Field Knowledge: from closed tickets to the next job guide

> **On-demand lab:** This track is for in-person attendees only and is not available to on-demand lab users. Skip to [Track C](#trackc).

Fictional team: High Desert Property Management, 8 rental properties in Bend, Oregon. Source data: 379 closed maintenance tickets with free-text completion notes.

**How it works**

1. Past tickets become organized, cited knowledge.
2. An agent uses that knowledge to prep a new ticket.
3. Completed work feeds new lessons back in.

You can do this track without doing Track A. B1 and B6 are on your own; the rest are MC-led.

* * *

<a id="b1"></a>

## B1 · Open the shared knowledge base

### Steps

1. Open a new tab.
  
2. Copy and paste this URL into the Edge address bar:
  
      https://wwlautox05164985.sharepoint.com/sites/HighDesertPropertyManagement/Field%20Knowledge/Properties.md?pageId=15
  
3. Open and view a property page and then do the same for an equipment page.
  
4. Open Copilot in SharePoint (the icon in the lower right). You'll use it for the rest of Track B.
  

### What you'll see

Pages are organized by property and by equipment model, plus one page of practices that apply everywhere. Pages link to each other and cite the ticket IDs behind them.

### Why it matters

Copilot wrote every page from 379 closed tickets. Nobody typed in the knowledge.

* * *

<a id="b2"></a>

## B2 · Prep for a furnace repair

### Submit this prompt

    For a Pine Hollow G3 furnace with weak airflow and a humming blower, what should I check and bring? Compare the reported symptom with the ticket findings, and tell me how strong the evidence is.

### Why it matters

Copilot combines what it knows about the property (Pine Hollow) with what it knows about the equipment (the G3 furnace). You get advice no single ticket contains, plus how strong the evidence is.

* * *

<a id="b3"></a>

## B3 · Check for safety risks before a visit

### Submit this prompt

    A tenant at Larkspur says an outlet is warm. What should I check before I go? Include the safety caution, the supporting ticket, and anything the knowledge base doesn't establish about access.

### Why it matters

Copilot gives the safety caution with the ticket behind it. It also says what the knowledge base doesn't know, such as how to get into the unit, instead of guessing.

* * *

<a id="b4"></a>

## B4 · Compare two furnace models

### Submit this prompt

    How do the Aerotherm G2 and G3 no-heat or low-airflow clues differ? Separate repeated patterns from one-ticket hunches.

### Why it matters

Copilot reasons across many tickets instead of looking up one. It keeps similar symptoms on two models apart, and separates patterns seen many times from one-off hunches.

* * *

<a id="b5"></a>

## B5 · Find what causes repeat visits

### Submit this prompt

    Which equipment problems most often needed a second trip, and what would have prevented them?

### Why it matters

Copilot pulls lessons from all 379 closed tickets and points them at the most expensive problem: having to go back a second time.

* * *

<a id="b6"></a>

## B6 · Free exploration (5 min)

Pick any prompt below, submit it in Copilot in SharePoint, and follow up with your own questions. After any answer, use the **Check the sources** prompt at the end of this list.

#### Find your way around

    I'm preparing for a maintenance visit. Which pages should I check for property-specific guidance, model-specific checks, and practices that apply more broadly?

**Why it matters:** Shows how Copilot organized messy ticket notes into pages, without anyone designing the structure.

#### Prepare for a site visit

    What do I need to know before going to Basalt Lofts? Cite the tickets behind each point.

**Why it matters:** Turns details scattered across many tickets into one briefing, with a ticket behind every point.

#### Decide whether to send a technician

    A tenant says their Kelvin KX-12 heat pump is blowing cold air. Do I need to send someone?

**Why it matters:** Helps tell normal behavior from a real fault, so a phone call might save a technician visit.

#### Check that it won't make things up

    Does the knowledge base provide a Pine Hollow gate or access code? If not, what does it say to verify instead?

**Why it matters:** Shows it won't invent sensitive details like access codes, and tells you what to verify instead.

#### Get specific repair details

    For an AquaMax AM-50 with rusty or discolored hot water, what did the tickets find, what tool was noted, and how many tickets support each point?

**Why it matters:** Gives the cause, the tool needed, and how many tickets back each point. Finding that by hand means reading through many tickets.

#### Compare equipment reliability

    Which equipment models generate the most service calls per installed unit? Rank them and show the counts behind each.

**Why it matters:** Helps decide which equipment to replace first, using only maintenance notes.

#### Find the properties with the most problems

    Which properties generate the most tickets, and what kinds of problems drive them?

**Why it matters:** Gives a view across all 8 properties without building a report by hand.

#### Spot seasonal patterns

    How did ticket volume by category change between November 2024 and October 2026? Call out any seasonal patterns.

**Why it matters:** Finds patterns over time that no single ticket shows.

#### Check the sources (ask after any answer)

    Which tickets support that answer, and how many are there?

**Why it matters:** Every answer can be traced to the tickets behind it.

* * *

<a id="b7"></a>

## B7 · Log a new ticket

### Steps

1. Submit the prompt below.
2. Note the Ticket ID Copilot replies with. You'll need it in B8 and B9.
3. Select Create in Copilot.

### Submit this prompt

    Add a new item to the Service Tickets list. Set Ticket ID to PM-2002 followed by a dash and my name. Property: Basalt Lofts. Unit: 412. Issue: "Heater blows cold air for a few minutes." Status: New. Opened: today. Leave Category and Priority blank. Tell me the Ticket ID you used.

### What you'll see

A new item in the Service Tickets list with Status = New, and a reply with your Ticket ID (for example, `PM-2002-<your name>`).

### Why it matters

Work enters the system the same way it always does: as a ticket in a list.

* * *

<a id="b8"></a>

## B8 · Triage the ticket

### Steps

1. Copy the prompt below and replace `<your Ticket ID>` with your Ticket ID from B7.
2. Submit the prompt.

### Submit this prompt

    Update Service Ticket <your Ticket ID>: set Category to HVAC and Priority to Routine.

### What you'll see

Your ticket shows Category = HVAC and Priority = Routine. Status stays New.

### Why it matters

Ticket updates are prompts, not forms.

* * *

<a id="b9"></a>

## B9 · Assign the ticket

### Steps

1. Copy the prompt below and replace `<your Ticket ID>` with your Ticket ID from B7.
2. Submit the prompt in Copilot in SharePoint.
3. Approve credit use if asked. Stay in the session until it finishes.
4. Open the **Job Guides** library in a new tab.

### Submit this prompt

    Run the Assign ticket skill on Service Ticket <your Ticket ID>.

### What you'll see

* In **Job Guides**: an HTML job guide named `<your Ticket ID> - Basalt Lofts 412`.
* On your ticket: Assigned Tech, Status = Assigned, a Job Guide link, and a Dispatch Notes line. The tech assigned depends on who is available that day.

> **About the skill:** Assign ticket is already set up on this site. It finds the equipment, picks today's available tech with the right skills, reads the Field Knowledge pages for this property, model and type of job plus the unit's last five closed tickets, writes a one-page HTML job guide in Job Guides, and updates the ticket.

### Why it matters

An agent uses the knowledge base to prepare the next job: what to bring, how to get in, and whether to go at all.

* * *

<a id="b10"></a>

## B10 · Create a report

### Steps

1. Submit the prompt below.
2. Open the **Job Guides** library in a new tab and open the report. It's an HTML page with your name in the file name.

### Submit this prompt

    Using the Field Knowledge knowledge base, create a one-page HTML report on Aerotherm G3 furnaces: how often they need service compared with the G2, the top causes with ticket counts, how many jobs needed a second trip, and what to stock on the truck. Save it in the Job Guides library and include my name in the file name. Cite the tickets behind each point.

### Why it matters

The knowledge base becomes the source for new documents, not just answers.

[Back to task list](#tasks)

* * *

<a id="trackc"></a>

# Track C · Put EagleFord account knowledge to work

Use the EagleFord Account Knowledge Base you created in Track A to find open issues, onboard a colleague, and prepare a customer meeting brief.

**Before you start:** Complete Track A and confirm **EagleFord Account Knowledge Base** appears on your site. Use your existing site and knowledge base; don't create a new one. You don't need Track B for this track.

* * *

<a id="c1"></a>

## C1 · Tour the knowledge base (2–3 min)

### Steps

1. Switch to the browser tab with your EagleFord Account site.
2. Select **EagleFord Account Knowledge Base** in the left navigation.
3. Open a couple of pages and skim through them.

### What you'll see

The customer name, the champion (Dana Brooks), and the main stakeholders. Copilot builds each knowledge base fresh, so page names, layout and formatting can vary from person to person. The content should be the same.

### Why it matters

Context first, so the answers in C2–C4 make sense.

* * *

<a id="c2"></a>

## C2 · Find the open issues

### Steps

1. Stay on the EagleFord Account Knowledge Base.
2. Open Copilot in SharePoint and submit the prompt below. The answer returns in under a minute.

### Submit this prompt

    Using the EagleFord Account Knowledge Base, list the top five open issues with the EagleFord account as of the latest available source information.

### Why it matters

Uses the latest evidence instead of repeating every problem ever mentioned.

* * *

<a id="c3"></a>

## C3 · Onboard a new team member

### Steps

1. Submit the prompt below in Copilot in SharePoint.
2. Keep the Copilot pane open until it finishes. HTML generation can take several minutes.
3. Open the HTML report.

### Submit this prompt

    Generate a practical onboarding report in html for a new account-team member joining EagleFord. Assume they know enterprise sales but have no prior knowledge of this account. Use only the EagleFord Account Knowledge Base and state the latest source date.

### Why it matters

A colleague gets up to speed without attending a single earlier call.

* * *

<a id="c4"></a>

## C4 · Create a meeting brief

### Steps

1. Submit the prompt below in Copilot in SharePoint.
2. Keep the Copilot pane open until it finishes. HTML generation can take several minutes.
3. Open the HTML file and check its links and print layout.

### Submit this prompt

    Generate a polished, self-contained HTML meeting brief for an upcoming meeting with a 30-minute account check-in with Dana Brooks on November 22, 2026. Include an executive snapshot; Dana’s role, priorities, and communication preferences supported by the sources; the meeting objective and desired outcomes; a timed 30-minute agenda; the top issues and documented commitments to discuss; five tailored discovery or follow-up questions.

### Why it matters

Account knowledge turned into a usable document for a real conversation.

[Back to task list](#tasks)
