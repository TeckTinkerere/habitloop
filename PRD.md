# HabitLoop: Product Requirements Document (PRD) v1.0

## 1. Executive Summary
**HabitLoop** is a three-sided marketplace that turns habit-building into a trusted, sponsored challenge economy. Users join habit challenges hosted by verified **Creators** and sponsored by **Brands**. The platform replaces passive tracking with "Proof-of-Action," rewarding consistent real-world behavior with tangible brand value.

---

## 2. Product Thesis
Motivation fades, but accountability and rewards drive consistency. HabitLoop's core loop—**Join, Act, Prove, Reward**—leverages social proof and brand sponsorship to solve the retention problem in wellness and productivity apps.

---

## 3. Marketplace Pillars

### 3.1 The User (The "Player")
*   **Goal:** Build habits, join communities, and earn rewards.
*   **Core Flow:** Discover challenges → Join → Daily Proof-of-Action → Unlock Rewards → Redeem in Shop.
*   **Value Prop:** Tangible rewards for wellness; "BeReal" for habits.

### 3.2 The Creator (The "Host")
*   **Goal:** Monetize expertise and engage their audience through structured challenges.
*   **Core Flow:** Connect Socials → Apply to Brand Briefs → Host Challenge → Review Proofs → Earn Payouts.
*   **Value Prop:** High-integrity monetization beyond affiliate links.

### 3.3 The Sponsor (The "Funder")
*   **Goal:** Drive measurable engagement, brand loyalty, and product trial.
*   **Core Flow:** Create Brief → Select Creator → Fund Reward Reserve → Track ROI (Verified Actions).
*   **Value Prop:** Guaranteed user action and authentic UGC vs. passive impressions.

---

## 4. Core Features & Functional Requirements

### 4.1 Proof-of-Action (PoA) System
To maintain integrity, rewards are only unlocked via verified proof:
*   **Photo/Video:** Time-stamped visual evidence (e.g., gym selfie, healthy meal).
*   **API Sync:** Integration with Apple Health, Strava, or Wearables for fitness/sleep data.
*   **Social Proof:** Peer kudos and creator-reviewed submissions.

### 4.2 Reward Journey & Wallet
*   **Tiered Milestones:** Day 7 (15% off), Day 14 (Product Sample), Day 30 (Major Voucher/Prize).
*   **Loop Points:** Platform currency earned for streaks, redeemable in the "Loop Shop."
*   **Sponsor Vouchers:** Unique codes or deep-links for brand redemption.

### 4.3 Creator Sponsorship Hub
*   **Marketplace:** Creators browse brand briefs filtered by category (Fitness, Sleep, etc.).
*   **Trust Infrastructure:** Social OAuth verification and Stripe Connect for automated payouts.
*   **Management:** Dashboard to monitor participant completion rates and approve proof.

### 4.4 Brand Dashboard
*   **Campaign Builder:** Define duration, reward tiers, and proof requirements.
*   **Impact Analytics:** Real-time metrics on total rewards distributed, active runners, and habit completion rates.

---

## 5. Design & User Experience (UX)
*   **Visual Tone:** "Stoic Minimalism" meets "Duolingo Gamification." Warm off-whites, soft mint/blue gradients, and high-trust charcoal accents.
*   **Accessibility:** Large typography, clear status chips, and tabular numerals for data clarity.
*   **Privacy:** Proof photos are private by default; "Proof-of-Action" does not share raw health data with brands.

---

## 6. Technical Stack (Recommended)
*   **Frontend:** React Native (Mobile-first).
*   **Backend:** Supabase (Auth, Postgres, Realtime, Edge Functions).
*   **Payments:** Stripe Connect (Marketplace payouts and brand funding).
*   **Health Data:** Terra API (Unified wearable integration).
*   **Analytics:** PostHog (Event tracking and feature flags).

---

## 7. Success Metrics (KPIs)
*   **Retention:** % of users reaching the Day 14 milestone.
*   **Integrity:** % of proofs approved vs. flagged for fraud.
*   **ROI:** Cost per verified user action for brands.
*   **Liquidity:** Number of creator-brand deal matches per month.

---

## 8. MVP Roadmap
*   **Phase 1:** Core "Proof-of-Action" loop with 1 Creator and 1 Brand partner.
*   **Phase 2:** Automated Sponsorship Marketplace and Stripe Payouts.
*   **Phase 3:** Advanced API integrations (Oura, Garmin) and Loop Shop expansion.
