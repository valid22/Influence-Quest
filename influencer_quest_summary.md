## Influence Quest: Chapter, Choices, and Consequences Summary

This file summarizes the structure of **Influence Quest: My Career Simulator** – the chapters, key situations, main choice patterns, and the consequences (local and long‑term). It is written as a reference for the MGTA 459 final project.

---

## Core Stats & Global Consequences

- **Stats**
  - **Trust**: Do people feel safe with me? Do I listen, share credit, and follow through?
  - **Network**: How broad and cross‑functional are my relationships and coalitions?
  - **Reputation**: What stories circulate about me – expert, helper, politician, stalled IC?
  - **Power**: My practical leverage: formal authority, visibility, and ability to move resources.
- **Global Epilogue Archetypes** (driven by final stats)
  - **Fast‑Tracked & Promoted** (very high all four): I lead big bets; promotions and stretch roles come my way.
  - **Balanced Influence Path** (solid mix across stats): I am a credible “influence architect” with growing opportunities.
  - **Stalled Contributor** (low power + modest network/reputation): strong IC, but not tapped to lead.
  - **Over‑Leveraged Politician** (high power, low trust): visible and effective on paper; fragile when sponsors shift.
  - **Under‑Networked Expert** (high reputation, low network): smart but sidelined from big decisions.
  - **Managed Out / Fired** (all stats low ≈ 1): after missed promotions and weak influence, I am effectively managed out.

The epilogue displays a **consequence card** (green / amber / red) with a clear label for each archetype.

---

## Chapter 1 – Networks

**Theme:** Early networks, social capital, and asking good questions as a new hire.

- **Core situation**
  - I join a new company and must decide how to use onboarding time, senior intros, and peer coffees.
- **Main choice patterns**
  - **Curious connector vs. passive observer**
    - Ask thoughtful questions, map the org, follow up with peers → **Trust ↑, Network ↑**.
    - Stay heads‑down, hope work speaks for itself → **Network flat, Reputation only slightly ↑**.
  - **Broker relationships vs. stay in one lane**
    - Introduce people across functions, notice structural holes → **Network ↑, Power ↑**.
    - Only build relationships inside my immediate team → **Narrower network**, less future leverage.
- **Local consequences**
  - Strong early networks unlock more helpful mentors and allies in later chapters (e.g., Maya, Ops, Sales).
  - Weak early networks make later coalition and persuasion work harder but still recoverable.

---

## Chapter 2 – Coalitions (Project Horizon)

**Theme:** Coalition‑building vs. top‑down power, calling people in vs. calling them out.

- **Core situation**
  - I care about a cross‑functional prioritization initiative **Project Horizon**.
  - Ops and Sales push back; I must decide how to respond to resistance.

- **Key choice nodes (each with 3+ options)**
  1. **Rumors of resistance (chat)** – first response to pushback:
     - Go straight to Maya/VP for a hard **top‑down mandate** → **Power ↑, Trust ↓, Reputation slightly ↓**.
     - Ask for intros to skeptics, listen to concerns → **Trust ↑, Network ↑, Power ↑**.
     - Downplay resistance (“it will blow over”) → **Reputation ↓, later Trust ↓**.
     - Publicly call out skeptics in a group channel → **Trust ↓↓, Network ↓, Reputation ↓**.
  2. **Second‑order responses**
     - **From mandate**: repair with Ops vs. double‑down on brittle power.
     - **From listening to skeptics**: invite them into co‑design vs. keep ownership solo.
     - **From downplaying**: course‑correct with late 1:1s vs. double‑ignore complaints.
     - **From public call‑out**: accept it as a cautionary tale vs. ignore the relationship damage.

- **Chapter 2 consequence gate: `ch2_consequence`**
  - **Removed from Lead** (bad, red card)
    - If **Trust** and **Reputation** are very low after Horizon → I am quietly removed from leading future change; I can only go to Epilogue.
  - **Credible, with Room to Grow** (amber card)
    - Decent Trust/Network/Reputation → I keep some coalition credibility and **unlock Chapter 3**.
  - **Horizon as a Cautionary Tale** (amber card)
    - Mixed stats → I can still enter Chapter 3, but without a strong tailwind.

---

## Chapter 3 – Persuasion (Pricing Pilot with Elena)

**Theme:** Persuasion tools (social proof, authority, consistency, story vs. data dump) with a skeptical senior leader.

- **Core situation**
  - I pitch a **pricing/pacakging pilot** to **Elena (Ops/Finance)**.
  - Multiple steps: first framing → handling objections → shaping the ask → deciding how to celebrate/own the win.

- **Key decision steps & choices**
  1. **First framing (chat with Elena)**
     - **Social proof**: peers already run pilots (successes, learnings) → **Reputation ↑, Trust ↑**.
     - **Authority & data**: external research + internal models → **Reputation ↑↑, risk of overload**.
     - **Consistency**: small, values‑aligned pilot (foot‑in‑the‑door) → **Trust ↑↑, Power ↑**.
     - **Data dump**: send a 30‑slide deck → **Reputation slightly ↑ (competence), Trust ↓**.
  2. **Outcomes & sub‑choices** (all chat‑styled)
     - From **social proof**:
       - Follow up with a narrow pilot ask → **Trust/Power ↑**.
       - Overreach to full rollout → Elena resists; then:
         - Recover to pilot → partially repair Trust.
         - Dig in → leads toward **stalled** path, **Trust/Power ↓**.
       - Loop in a peer champion to join the conversation → **Trust/Network ↑**.
     - From **authority**:
       - Shift to a single concrete story → goes to story outcome.
       - Double down on data → routes to data‑dump failure outcome.
       - Pause to ask Elena’s top questions → deeper **Trust ↑** and better tailoring.
     - From **consistency**:
       - Co‑design scope & metrics → strong **Trust/Reputation ↑**, co‑owned pilot.
       - “Stealth” ownership (thin yes, no co‑design) → later **sponsorship is weak**.
       - Invite explicit pushback and exit criteria → safer, shared guardrails.
     - From **data dump**:
       - Recover with a one‑page story → move toward better persuasion.
       - Double down (“read the full deck”) → **Reputation/Power ↓**, stalled.
       - Withdraw the ask for now → still a missed opportunity (milder Reputation ↓).

  3. **Pilot design & credit**
     - Run it as a **true team effort**, co‑present with Ops/Finance → **Trust/Network/Power ↑**.
     - Center myself as the hero in leadership rooms → **Reputation ↑, Trust ↓**.
     - Run it quietly, only share if spectacular → low visibility, **Power/Reputation ↓**.
     - For both shared and self‑centered wins, later choices let me:
       - Log the pattern,
       - Repair trust (reach out and recognize others),
       - Get cynical/defensive (erode Trust/Reputation).

- **Local archetype in Chapter 3**
  - **“Competent but Not Convincing”**: data‑heavy, low‑story paths land in a stalled persuasion outcome – credible but not compelling, feeding into **stalled contributor** or **under‑networked expert** in the epilogue.

---

## Chapter 4 – Power & Leverage (Promotion Window with Maya)

**Theme:** Designing my power base – expert, helper, visibility, or passive – and how that affects promotions.

- **Step 1 – Identity pitch (chat with Maya)**
  - “I’m the person who…”
    - **Expert**: owns complex, high‑stakes problems → **Power ↑, Reputation ↑, Network slightly ↓**.
    - **Helper/Multiplier**: makes others better → **Trust ↑, Network ↑, Power ↑**.
    - **Visibility‑seeker**: wants big, visible wins → **Power/Reputation ↑, Trust slightly ↓**.
    - **Passive IC**: “keep my head down” → small **Reputation ↑, Power ↓**.

- **Step 2 – First consequences (all with 3 sub‑choices)**
  - **Expert path (`ch4_s1_expert_outcome`)**
    - Teach others (guild/brown‑bag) → **Trust/Network ↑**.
    - Guard the niche → **Power ↑, Trust ↓**.
    - Take on everything → **Power/Reputation ↑, Trust ↓, risk burnout**.
  - **Helper path (`ch4_s1_helper_outcome`)**
    - Set boundaries → sustainable helping.
    - Say yes to everything → loved, but **Power/Reputation ↓**.
    - Ask for healthy visibility → **Reputation/Power ↑**.
  - **Visibility path (`ch4_s1_visibility_outcome`)**
    - Anchor on substance → **Reputation/Power/Trust ↑**.
    - Spin and avoid owning mistakes → **Trust/Reputation ↓, Power ↔/↑**.
    - Step back from spotlight → **Power/Reputation ↓**.
  - **Passive path (`ch4_s1_passive_outcome`)**
    - Wake‑up call: treat power‑building as part of job.
    - Pride in being “above politics”.
    - Consider leaving for another org.

- **Step 3 – Second scenes (chat, 3 choices each)**
  - **Expert:** choosing incident vs strategic project vs trying to do both.
  - **Helper:** triaging help requests vs yes‑to‑all vs redirecting/connecting others.
  - **Visibility:** sharing the exec stage vs going solo vs downplaying the review.
  - **Passive:** interpreting promotion feedback (design plan vs resent vs scout other teams).

- **Chapter 4 consequence gate: `ch4_consequence`**
  - **Passed Over for People Leadership** (bad, red)
    - If **Power, Reputation, Trust** remain ≲ 1 → no manager role; I go straight to Epilogue or replay Chapter 4.
  - **Promoted to People Manager** (good, green)
    - If **Power ≥ ~2.5** and **Trust/Reputation/Network ≥ ~1.5** → clear promotion, unlocks Chapter 5.
  - **Stretch Manager Role** (mixed, amber)
    - In‑between stats → I get a smaller‑scope manager role with explicit caveats; Chapter 5 unlocked but framed as a test.

---

## Chapter 5 – Organizational Influence (Leading a Change Team)

**Theme:** Project Oxygen‑style leadership in a real change rollout; how my manager behavior shapes trust and long‑term influence.

- **Step 1 – Kickoff meeting (chat with Sam, Priya, Alex)**
  - **Coach response**: listen, ask for worries and success criteria → **Trust/Network/Reputation/Power ↑**.
  - **Pressure response**: “this is happening; just execute” → **Power ↑, Trust ↓↓**.
  - **Avoid/deflect**: hide behind the plan & deck → **Trust/Reputation ↓**.

- **Step 2 – Immediate outcomes (chat, 3 choices each)**
  - From **coach**: follow through (write commitments, revisit), over‑promise resources, or take on all shielding work alone.
  - From **pressure**: circle back and admit mistake, double‑down (“not a fit for this team”), or try to balance pressure with private support.
  - From **avoid**: compensate later with 1:1s, maintain distance, or delegate “care work” to a team member.
  - All paths feed into **`ch5_s2_checkins`**.

- **Step 3 – Mid‑rollout check‑ins (chat)**
  - Team reports uneven adoption and recognition:
    - **Model behavior**: highlight managers doing it well → **Trust/Reputation/Power ↑**.
    - **Enforce hard**: escalate non‑compliance → **Power ↑, Trust ↓**.
    - **Shrug it off**: tolerate uneven adoption → **Trust/Reputation ↓**.

- **Step 4 – Org memory (chat with Maya)**
  - `ch5_s3_orgsignal`: what the organization remembers about my leadership.
  - Choices:
    - Own the story and lessons learned → **Trust/Reputation ↑**.
    - Deflect blame upward → **Trust/Reputation/Power ↓**.
    - Advocate for better org‑wide support in future changes → **Power/Network ↑**.
  - These final moves heavily influence whether the **epilogue archetype** is:
    - Promoted/fast‑tracked,
    - Balanced but still growing,
    - Stalled,
    - Over‑political,
    - Under‑networked, or
    - Managed out.

---

## How to Use This Summary

- **For replay:** Use this file as a map to deliberately explore:
  - “Good life” paths (high trust, coalitions, story‑based persuasion, healthy power),
  - Failure modes you know you’re prone to (data dumps, avoiding conflict, over‑reliance on top‑down power, hiding from visibility).
- **For the written reflection:** You can quote or paraphrase chapter summaries and archetype labels to:
  - Connect each chapter back to course concepts (Burt, Cialdini, Made to Stick, Pfeffer, Project Oxygen, etc.).
  - Describe your own tendencies and the **if‑then rules** you want future‑you to follow in real careers.


