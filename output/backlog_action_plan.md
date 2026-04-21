# Backlog Action Plan

This document defines how the EAST team should act on backlog items
based on ticket age and first response time.

---

## 1. Backlog Aging Rules

| Age Bucket | Definition | Required Action |
|-----------|------------|----------------|
| NEW | 0–7 days | No action required, monitor |
| AGING | 8–30 days | Actively work and update ticket |
| STALE | 31–60 days | Follow up with requester or internal team |
| OLD | >60 days | Escalate or close as stale |

---

## 2. First Response Time Guidelines

| First Response Time | Action |
|-------------------|-------|
| ≤ 24 hours | ✅ Good |
| 24–48 hours | ⚠️ Needs attention |
| > 48 hours | ❌ SLA risk – immediate update needed |
| No response | ❌ Must update immediately |

---

## 3. Ticket Closure Rules

A ticket can be closed when:
- Access has been provided and confirmed
- Requester has not responded after 2 follow‑ups in 7 days
- Ticket is no longer valid per latest business rules

---

## 4. Daily Expectations for Team

- First response must be added within 24 hours
- Aging tickets (>30 days) should be reviewed daily
- No ticket should remain untouched for more than 2 working days

---

## 5. Reporting Reference

- **Data source:** Excel in `/data`
- **Daily report:** `backlog_report_<date>.md`
- **This file:** Action rules only (no ticket data)
