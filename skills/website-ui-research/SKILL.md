---
name: website-ui-research
description: Research and improve a website's UX, visual design, accessibility, performance, and conversion using evidence from analytics, usability testing, competitor review, and production-quality web standards.
metadata:
  short-description: Audit and improve website UI with measurable research
---

# Website UI Research

Use this skill when the user wants to understand how to improve a website, compare it with strong competitors, plan a redesign, choose research tools, or define UI and product metrics.

## Outcome

Produce an evidence-based UI research plan or audit that connects observed problems to user impact, business impact, recommended changes, and validation metrics. Avoid recommending visual changes only because they are fashionable.

## Workflow

1. Establish context: website URL or available screens/code, target users, primary business goal, important user journeys, device mix, and known constraints. If details are missing, make explicit low-risk assumptions and proceed.
2. Baseline the current experience: capture key pages, mobile and desktop states, loading behavior, accessibility issues, navigation, content hierarchy, calls to action, forms, errors, and success states.
3. Gather evidence using the relevant combination of:
   - heuristic review and first-impression review;
   - competitor and industry-pattern comparison;
   - analytics funnels and event data;
   - session recordings, heatmaps, and search behavior;
   - interviews or usability tests with realistic tasks;
   - Lighthouse/PageSpeed, Core Web Vitals, accessibility, and SEO checks.
4. Separate observations from interpretations. For each issue record evidence, affected users, business impact, confidence, effort, and a proposed fix.
5. Prioritize with `impact × confidence ÷ effort`. Put clarity, broken journeys, major drop-offs, accessibility blockers, and performance problems ahead of cosmetic polish.
6. Recommend solutions at the right level: content, information architecture, interaction, visual system, responsive behavior, performance, accessibility, or instrumentation.
7. Define validation: task completion, conversion, errors, drop-off, satisfaction, Core Web Vitals, accessibility conformance, and before/after or A/B comparison where appropriate.

## Metrics

Choose metrics based on the site's goal rather than reporting every available number.

- Business: conversion rate, qualified leads, signup or purchase completion, revenue per visitor, retention.
- UX: task completion, time on task, error rate, abandonment, search success, satisfaction, effort, SUS.
- Behavior: CTA click-through, engagement rate, scroll depth, page exits, returning users.
- Performance: LCP, INP, CLS, TTFB, page weight, JavaScript cost, image load time.
- Accessibility: keyboard completion, focus visibility, contrast, form-label coverage, heading structure, screen-reader usability.

Use real-user data when available. Treat a single Lighthouse score, heatmap, or recording as diagnostic evidence, not as the final measure of success. For Core Web Vitals, use field data and the 75th percentile where possible; practical targets are LCP ≤ 2.5s, INP ≤ 200ms, and CLS ≤ 0.1.

## Tool selection

Suggest tools according to the question:

- Analytics and funnels: GA4 or an equivalent analytics platform.
- Behavior: Microsoft Clarity, Hotjar, FullStory, or Contentsquare.
- Usability testing: Maze, UserTesting, interviews, or moderated tests.
- Prototyping: Figma.
- Performance and technical quality: Lighthouse, PageSpeed Insights, WebPageTest, Chrome DevTools.
- Accessibility: axe DevTools, WAVE, keyboard testing, and screen-reader testing.
- Search: Google Search Console.

Do not imply that a tool's score is a universal quality grade. Explain what it measures and what it cannot prove.

## Production-quality standards

Check that the experience is consistent across responsive breakpoints and includes loading, empty, error, disabled, focus, hover, success, and reduced-motion states. Check WCAG 2.2 principles, semantic structure, keyboard access, readable content, resilient forms, secure-looking trust signals, and performance on slower mobile devices.

## Deliverable format

When producing a report, include:

1. Executive summary
2. Assumptions and target users
3. Current journey and key tasks
4. Evidence and findings, each with severity and confidence
5. Prioritized opportunity backlog
6. Recommended design direction and page/component changes
7. Metrics and instrumentation plan
8. Validation and experiment plan
9. Next 3–5 actions

If the user only asks for suggestions, provide the concise workflow and recommended metrics first, then ask for the URL or screenshots for a specific audit.
