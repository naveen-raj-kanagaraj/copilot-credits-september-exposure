# Copilot Credits: The September 1 Exposure

A product marketing recommendation on GitHub Copilot's move to usage based billing, written as an internal memo dated August 2026 rather than a retrospective case study.

Speculative portfolio artifact. Not affiliated with GitHub or Microsoft. All figures are drawn from GitHub's public announcement of 27 April 2026 and are cited in the appendix. Assumptions are labelled as assumptions.

**[View the full deck as PDF](Copilot-Credits-September-Exposure.pdf)**

![Cover](01.png)

---

## The situation

On 1 June 2026, GitHub replaced Copilot's premium request model with metered AI Credits across every plan. Base prices did not change: Business stayed at $19 per user per month and Enterprise at $39, each including that value in credits. Code completions remained free. Chat, CLI, cloud agents and code review became metered.

Public reaction was loud and framed almost entirely as a price rise. Almost all of it came from individual developers.

## The argument

**GitHub did not raise prices. It removed the ability to forecast them.**

That distinction decides what the response should be. A cost increase is absorbed by a budget owner and negotiated at renewal. A forecasting failure is escalated to finance and triggers procurement review. GitHub produced the second and is being criticised for the first, so every proposed fix that adjusts price is solving the wrong problem.

## The findings

Two things in the announcement had not been connected in any coverage I could find.

**First, promotional credits are additive, not substitutional.** Existing Business and Enterprise customers received an extra $30 and $70 per user per month for June, July and August only, on top of the base allowance. That makes the 1 September step down 61% for Business and 64% for Enterprise, not the smaller figure implied by reading the promotional amount as a replacement.

![Exposure](05.png)

**Second, model fallback was discontinued in the same release.** Under premium requests, exhausting an allowance dropped the user to a cheaper model and work continued in a degraded state. Under credits, the organisation decides in advance whether to allow overage at published rates or cap spend. So the cap that the field is selling as the answer to unpredictability is also an off switch.

Together: three months of promotional cover trained usage against an inflated allowance, the cover ends on 1 September, and the only way an administrator can guarantee a predictable bill is to accept that their developers may stop mid task. That trade off has not been communicated.

![Mechanism](04.png)

## The recommendation

Reposition from predictable seat to governed platform. Name the cap trade off before customers find it. Ask Product for a degraded capability floor at the cap so governance does not mean stoppage.

The positioning deliberately does not claim the bill is predictable, because it is not, and claiming otherwise breaks trust a second time.

![Positioning](07.png)


## Method

Every load bearing figure traces to GitHub's announcement of 27 April 2026 and appears in Appendix A with its source. Derived numbers are marked as derived. Three inputs are stated as unverified rather than estimated: actual September consumption, budget configuration rates, and current competitor pricing.

The sensitivity model is presented as a range across three utilisation scenarios rather than a point forecast, and its assumption line notes that the June to August baseline was itself inflated by the promotional credits.

Slide 14 carries no invented targets. Two of the four metrics say the baseline is unknown, and the slide ends with the condition that would prove the diagnosis wrong.

## Two deliberate choices

**No competitor price points.** Pricing in this category moves monthly and a stale figure in a battlecard is worse than none. The competitive argument is structural: agentic coding consumes frontier inference, that cost is real for every vendor, and the only question is who absorbs the variance.

**A stated cost.** Repositioning on governance rather than predictability concedes the easier sell to flat rate competitors for at least two quarters. The deck says so on slide 13 rather than presenting a recommendation with no downside.

## Source

GitHub, *GitHub Copilot is moving to usage based billing*, 27 April 2026.
https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/

---

Written August 2026 by Naveen Raj Kanagaraj, M.S. Marketing Analysis, DePaul University, Chicago.
