# Vibe coding: building is easy, building responsibly is not

**Handy tool or big risk?**

AI makes building accessible → which creates new opportunities → but also growing responsibility → and building it yourself is not always the best solution.

*Eric Rietveld, MSc · AI Domain Architect ServiceNow*

---

## 1. What is vibe coding?

Creating software by describing what you want in plain language. AI generates the code, interface, data models and logic.

You mainly develop by:

- describing;
- trying;
- giving feedback;
- regenerating.

**Difference from traditional programming:**

- less emphasis on writing code yourself;
- more emphasis on the problem, the desired outcome and testing.

> **Important nuance:** a working demo is not yet a secure, maintainable product.

**A question for yourself:** have you ever built a website, app, workflow or prototype with AI?

---

## 2. Why, and why now?

Generative AI now understands:

- natural language;
- software code;
- screenshots and designs;
- errors and log files;
- existing software structures.

The cost and time needed for a first prototype are dropping sharply. An entrepreneur can test an idea without immediately having to:

- put together a development team;
- free up a large budget;
- wait for months.

**The bottleneck shifts** from "can we build it?" to "are we building the right thing, and can we take responsibility for it?"

The idea is also moving closer to the build. The people who have the idea (entrepreneurs, domain experts, students) can now build a first version themselves, without handing it over to someone else first.

This lets you go through the cycle faster: idea → hypothesis → prototype → test with the target group → learn → adjust.

> **Key message:** AI democratizes software development, but also the responsibility for what you build.

---

## 3. What can you do with it?

From relatively simple to increasingly serious:

1. A landing page for a new business concept, such as a platform that bundles demand to get group discounts.
2. A clickable prototype of an app, such as one where you bet against yourself to keep your resolutions.
3. A form that collects customer information.
4. A calculator, planning tool or dashboard, for example one that shows when a battery container should charge or discharge.
5. A workflow to process requests.
6. An MVP with accounts, a database, payments, external APIs and AI functionality.
7. An internal business application that is actually used in the process.
8. An external application with intelligent workflows, used directly by customers.

### Demo 1: this presentation was vibe coded too

The slides of this talk are a web app built with AI. Live, one sentence is given to the AI:

> "Add kittens to this slide that slowly eat the whole slide."

What you see:

- the speed from idea to something that works;
- that you can make changes in plain language;
- that the first version can look convincing;
- that you still know almost nothing about what is happening technically underneath.

---

## 4. From fun demo to real use

A simple maturity ladder:

| Level | Description |
|-------|-------------|
| **Experiment** | Just for yourself, with fictional data. |
| **Prototype** | To test with potential users. |
| **MVP** | Real users and possibly real data. |
| **Product** | Customers depend on it. |
| **Business-critical solution** | Outages, errors or data breaches have serious consequences. |

With each step, the requirements increase:

- security;
- privacy;
- reliability;
- maintenance;
- support;
- cost control;
- laws and regulations.

> **Important distinction:** MVP stands for "minimum viable product", not "minimum responsible product".

---

## 5. Risks, in increasing severity

### Level 1: it doesn't work properly, and you lose control

- The AI misunderstands the assignment, or the code contains errors.
- A change breaks something else.
- The interface looks good, but exceptions are not handled.
- The maker doesn't sufficiently understand the generated code.
- No version control or backup.
- Unclear which dependencies and libraries are used.
- An external AI service or API changes, or costs rise unexpectedly.
- Nobody knows how to maintain the solution.

*Consequence:* frustration and limited damage at first, but the prototype that works today may be unusable tomorrow.

### Level 2: data and security

- Personal data is stored without need, for example sensitive personal goals in a resolution app.
- API keys or passwords are in the code.
- Users can view other people's data.
- Authentication is present, but authorization is missing.
- User input can manipulate instructions or systems.
- Data is sent to an external AI provider.

**Dutch context:**

- GDPR (AVG);
- data minimization (dataminimalisatie);
- purpose limitation (doelbinding);
- retention periods (bewaartermijnen);
- access control (toegangscontrole);
- transparency towards users.

### Level 3: customers depend on it

- Payments are processed incorrectly, for example money staked in a bet-against-yourself app.
- The AI gives wrong medical, legal or financial advice.
- An automated decision disadvantages someone.
- The application is unavailable.
- There is no logging, monitoring or way to recover from errors.
- Nobody is formally the owner of the solution.

*Consequence:* reputational damage, financial damage or legal liability.

---

## 6. AI is not only the builder

AI doesn't only create risks, and it does more than write code. It wears many hats:

- **Building:** code, interface and data.
- **Reviewing:** finding risks and vulnerabilities.
- **Brainstorming:** generating ideas and scenarios.
- **Researching:** the market, competitors and rules.
- **Learning:** having code and concepts explained to you.
- **Testing:** test cases and edge cases.

More specifically, AI can help with:

- sharpening requirements;
- finding missing scenarios;
- generating test cases;
- explaining code;
- spotting vulnerabilities;
- recognizing personal data in a design;
- proposing access rules;
- writing documentation;
- adding logging and error handling;
- assessing whether you should build something yourself at all.

> **Key message:** don't use AI only to build faster. Use AI to think more critically and test better.

---

## 7. Build, buy or configure?

### Build it yourself

Suitable when:

- the solution is truly distinctive;
- existing software doesn't fit;
- it's a small, controllable experiment;
- knowledge, time and maintenance capacity are available.

### Buy existing software

Suitable when:

- the problem is standard;
- reliability and support matter;
- the wheel has already been invented dozens of times.

Examples:

- webshop: Shopify;
- payments: Mollie or Stripe;
- CRM: HubSpot, Salesforce or Dynamics 365;
- scheduling: Calendly or Microsoft Bookings;
- collaboration: Microsoft Teams;
- service desk and workflows: ServiceNow.

### Configure and extend a platform

The middle road:

- use standard capabilities;
- add your own process and user experience;
- benefit from built-in security, permissions, data and management;
- use AI to make the configuration or application faster.

### Demo 2: ServiceNow Build Agent, reviewing

An application built earlier with the ServiceNow Build Agent is opened (building it live takes too long). The result lives inside a managed platform, with roles, access control, data model, audit trail and workflows.

The AI is asked to review it:

> "Act as a security, privacy and product reviewer. What risks do you see before this application is used by real users?"

It assesses the solution on:

- personal data;
- authentication and authorization;
- secrets;
- error handling;
- logging;
- dependencies;
- human oversight.

A managed platform gives better building blocks. Find the risks before your users do.

> A platform doesn't take away responsibility, but it gives you better building blocks and guardrails.

---

## 8. If you can build it in a day, so can everyone else

The same speed that lets you build a prototype in an afternoon lets a competitor copy it in an afternoon. If your idea is "an app that does X", the app is not what makes you special.

When software becomes cheap, it stops being an edge. The edge moves to things that are harder to copy:

- **Customer insight:** you understand a specific group better than anyone else.
- **Access and distribution:** you can actually reach your customers, and they trust you.
- **Community and network:** users, partners and suppliers who are not on the other side of a copy-paste.
- **Data:** information you collect over time that others don't have.
- **Physical and operational parts:** hardware, logistics, contracts, permits.
- **Service, reliability and trust:** being the one that keeps working and takes responsibility.
- **Speed of learning:** testing, adjusting and improving faster than others.

**Questions worth asking:**

- If someone copied my app tomorrow, what would they still be missing?
- What do I have that doesn't live in the code?
- What do I learn from real users that a copycat can't?

*Related to this morning's lecture on protecting intellectual property: who owns what you built with AI, and what can be protected at all, is worth checking before you rely on it.*

---

## 9. Closing

Three conclusions:

1. Building is easier than ever.
2. A working prototype is not yet a responsible product.
3. When everyone can build, the software is not your edge. Your edge is what is hard to copy.

> Vibe coding gives you the power to make almost any idea tangible. Entrepreneurship is then about what you do beyond the software, and what you are willing to take responsibility for.

---

## Q&A and questions afterwards

**Eric Rietveld**  
LinkedIn: [linkedin.com/in/aieric](https://www.linkedin.com/in/aieric)

**Alex Hendrikse**  
LinkedIn: [linkedin.com/in/alexhendrikse](https://www.linkedin.com/in/alexhendrikse)
