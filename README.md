# Marketplace Reliability Analysis

**Improving Marketplace Reliability in a Healthcare Staffing Platform**

*A Finance & Operations Case Study*

## Executive Summary

Reliability is the foundation of trust in healthcare staffing marketplaces. When a clinician cancels at the last minute—or fails to show up entirely—the impact on healthcare facilities is immediate and often unrecoverable, directly affecting patient care, operations, and long-term customer trust.

This case study analyzes reliability failures in a two-sided healthcare staffing platform, identifies the primary driver of execution failures, and proposes a targeted operational solution supported by financial impact modeling.

**Key outcomes from the analysis:**

- ~10% of booked shifts failed and were not recovered
- ~70% of failures occurred in the last mile (hours before or after shift start)
- A focused confirmation and escalation mechanism could recover ~2% of total potential net revenue in a representative market, with meaningful upside at scale

All company-specific names, locations, and proprietary terminology have been intentionally anonymized.

## Business Context

The platform connects licensed healthcare professionals (e.g., nurses, aides) with healthcare facilities that require short-notice staffing coverage.

While flexibility is a key value proposition for clinicians, facilities prioritize certainty of execution. A missed shift can result in:

- Immediate operational disruption
- Increased reliance on overtime or agency staffing
- Degraded trust in the platform

From a finance perspective, reliability failures create two layers of economic impact:

- Direct net revenue loss from shifts that go unworked
- Indirect loss from elevated facility churn and higher customer acquisition costs

As a result, reliability is not just an operational concern—it is a core financial driver.

## Data & Scope

The analysis focuses on one representative metropolitan market and uses three internal datasets:

- Shift-level operational logs
- Booking activity records
- Cancellation and no-show logs

Facility-initiated deletions were excluded to ensure the analysis focused on failures within the platform's control.

### Shift Classification Logic

| Category | Definition |
|----------|------------|
| Fulfilled | Shift was worked and verified |
| Unfulfilled | Shift was accepted but canceled or resulted in a no-show |
| Excluded | Shift deleted by the facility |

Using this framework, approximately 10% of booked shifts were classified as unfulfilled.

## Financial Impact of Reliability Failures

From a P&L perspective, the impact was material:

- Unfulfilled shifts accounted for ~9% of potential net revenue in the analyzed market

Net revenue loss was calculated using:

- Scheduled shift hours
- Hourly charge rates
- Platform take-rate assumptions

Importantly, this estimate excludes:

- Facility churn impact
- Incremental customer acquisition costs
- Long-term trust erosion

➡️ **The true economic cost of reliability failures is likely significantly higher than direct revenue loss alone.**

## Diagnostic Analysis & Key Findings

### 1️⃣ Failures Are Not Concentrated Among Specific Participants

Reliability failures were broadly distributed across:

- Healthcare professionals
- Facilities
- Shift types and roles

Even the highest-contributing worker or facility accounted for only a low single-digit percentage of total failures.

**Conclusion:** This is not a "bad actor" problem and cannot be solved through stricter enforcement alone.

### 2️⃣ Booking Timing Is Not the Root Cause

- The majority of failed shifts were booked well in advance
- Clinicians had sufficient time to plan for their shifts

**Conclusion:** Failures were not driven by poor planning or lack of intent at booking.

### 3️⃣ Failures Are Predominantly Last-Mile

A clear pattern emerged:

- ~70% of failures occurred within hours of shift start or as no-call-no-shows

These events are:

- Least recoverable
- Most disruptive to facilities
- Strongly correlated with elevated churn

**Conclusion:** The core issue is last-mile execution uncertainty, not scheduling or supply quality.

## Root Cause

The platform lacked a structured mechanism to reconfirm clinician availability close to shift start.

As a result:

- Silent disengagement went undetected
- Cancellation signals arrived too late for recovery
- Facilities bore the operational and financial impact

This represents a signal-timing failure, rather than a motivation, incentive, or policy failure.

## Proposed Solution: Proactive Confirmation & Escalation System

### Concept

Introduce a positive confirmation step several hours before shift start, paired with a graduated reassignment escalation process.

### How the System Works

- Clinicians must confirm attendance within a defined pre-shift window
- Failure to confirm flags the shift as "at risk"
- At-risk shifts open early to a backup pool of qualified clinicians
- Targeted incentives and notifications accelerate reassignment
- Facilities receive transparency into recovery efforts
- Early cancellations remain unrestricted to preserve clinician flexibility

### Expected Financial Impact

Using conservative assumptions grounded in historical data:

- ~30% reduction in last-mile failures
- Recovery of ~2% of total potential net revenue in the analyzed market

When extrapolated proportionally across the platform:

- Represents a six-figure annual revenue opportunity

Additional upside from:

- Reduced facility churn
- Avoided customer acquisition costs

### Downside Scenario

Even under a conservative downside case:

- 10–15% reduction in late-stage failures
- Partial recovery rates

The initiative remains net-positive, driven by:

- Low implementation cost
- High leverage on the most expensive failure window

### Why This Solution Works

- Targets the highest-impact reliability failures
- Converts uncertainty into early, actionable signals
- Improves recoverability without sacrificing marketplace flexibility
- Aligns operational design with financial outcomes
- Most importantly, it addresses the root cause rather than treating symptoms

## Key Takeaways

- Reliability in healthcare marketplaces is a systems design problem
- Finance plays a critical role in identifying where execution failures destroy value
- Small, well-timed process changes can unlock outsized P&L impact

## About This Case

This analysis is based on a real-world healthcare staffing marketplace scenario using historical data. All identifying details have been removed or generalized for public sharing.

**Note:** Please check the Data Processing.xlsx for Excel analysis. If you want to see more process details, please contact the Author.

## Author

**Dantong (Mia) Meng**  
FP&A | Marketplace Analytics | Financial Modeling
