# Limor's Travel Preferences

## Base & Typical Routes
- **Home base:** Israel (TLV — Ben Gurion Airport)
- **Most common destination:** USA (various cities, work trips)
- **Trip type:** Primarily business / work

## Flights

### Preferred Airlines
- **El Al** — has FF (frequent flyer)
- **United** — has FF
- **American Airlines (AA)** — has FF
- Prefer these over others when available and reasonably priced

### Landing Preference
- **Strong preference: daytime arrivals** — avoid landing in the middle of the night
- **Red-eye is fine** — overnight flight to arrive in the morning works well
- Avoid: landing at 2am–6am local time

### Routing
- TLV → US: direct El Al preferred when available, otherwise connecting via major hubs
- Always check flight credit/vouchers before booking new tickets (see memory.md for active credits)

## Hotels

### Priorities (in order)
1. **Cleanliness** — non-negotiable
2. **Proximity to meetings** — close enough to walk or take a short Uber
3. **Price** — basic is fine, no need for luxury

### Not needed
- Fancy amenities, spa, restaurant on-site
- Central location for tourism — location should be driven by meeting locations

## Ground Transportation

### Preference order
1. **Public transport / ground transport** — preferred if easy and practical
2. **Uber** — fallback when ground transport isn't convenient
3. Rental car — only if really necessary

## Shaul's Travel Planning Workflow

When Limor asks to plan a trip:

1. **Clarify the basics** (if not given):
   - Destination city
   - Travel dates (or flexibility)
   - Meeting locations (to anchor hotel search)
   - Budget constraints (if any)

2. **Flights first**
   - Check El Al, United, AA for availability
   - Prioritize daytime arrivals
   - Red-eye departures (overnight) are acceptable
   - Check if any existing flight credits apply (see memory.md)
   - Use `agent-browser` to search Google Flights or airline sites

3. **Hotel**
   - Search near meeting locations
   - Filter for cleanliness (4+ stars on Google/Booking, recent reviews mentioning clean)
   - Prioritize proximity over price
   - Use `agent-browser` to check Booking.com or Google Hotels

4. **Ground transport**
   - Check if public transit (subway, train) is practical from airport to hotel
   - Otherwise default to Uber
   - Note transit options for getting between meetings

5. **Calendar**
   - Check Limor's Google Calendar for the travel dates before confirming anything
   - Flag any conflicts

6. **Create Asana tasks for everything that needs manual action**
   - שאול cannot book directly — for every item that requires Limor to take action, create a task in Asana InTray
   - Examples: "Book flight TLV→JFK May 12", "Reserve hotel near [address]", "Check United miles balance before booking"
   - Each task should have enough detail to act on without re-researching (flight number, price, link)
   - Tag time-sensitive tasks with a due date

7. **Create a travel plan MD file**
   - Save it to `/workspace/extra/shaul-work/travel-plans/[destination]-[date].md`
   - Format: clean, readable, shareable with family
   - Include everything they need to know: where you're going, when you're leaving/returning, how to reach you, hotel name + address
   - Template below

---

## Travel Plan File Template

```markdown
# ✈️ Trip to [City], [Country] — [Month Year]

## Overview
- **Dates:** [departure date] → [return date]
- **Purpose:** [work / conference / meetings]
- **Destination:** [City, Country]

## Flights
| | Outbound | Return |
|---|---|---|
| **Flight** | [airline + flight number] | [airline + flight number] |
| **Departs** | [date, time, airport] | [date, time, airport] |
| **Arrives** | [date, time, airport] | [date, time, airport] |
| **Booking ref** | [reference] | [reference] |

## Hotel
- **Name:** [hotel name]
- **Address:** [full address]
- **Check-in:** [date]
- **Check-out:** [date]
- **Booking ref:** [reference]

## Getting Around
- **Airport → Hotel:** [transport method + details]
- **During trip:** [Uber / subway / walking]

## How to Reach Me
- **Phone:** +972502656256
- **Email:** lim@echowisdom.ai
- **Hotel phone:** [if available]

## Notes
[anything else relevant — visa, time zone difference, emergency contacts]
```

---

Always create the travel plan file even if booking isn't complete yet — mark unconfirmed items as `[TBD]` and update as things get confirmed.
