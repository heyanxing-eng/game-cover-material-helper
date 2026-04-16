# Data-Derived Notes

These notes are for embedded knowledge only. Do not cite them directly at runtime.

## Internal Judgment Frame

Internally, judge covers through five dimensions:
- `手机端可读性`
- `信息传达`
- `画面秩序`
- `题材/玩法匹配`
- `基础美术表现`

Important weighting:
- `手机端可读性` and `信息传达` are the highest-priority checks
- `画面秩序` is next because clutter often breaks the first two
- `题材/玩法匹配` is a direction check and becomes a real penalty when the image promises the wrong thing
- `基础美术表现` is a real plus or minus, but it cannot erase major failures in the first three

Tie-break rule when two images are close:
- prefer the one that survives mobile shrink better
- then prefer the one that explains the click reason faster
- only then let pure aesthetic advantage decide

## Verdict Ladder

Top-line verdicts should stay linear:
- `很能打`
- `能打`
- `可用，建议优化`
- `偏弱，不建议优先用`
- `风险高，不建议用`

Do not use non-linear verdict labels like:
- `中上`
- `方向对但偏弱`
- `中性偏弱`

Those can appear in explanation language, but not as the headline verdict.

## Slot Reality

- Publishers do not control card assignment.
- Do not frame the advice as "how to get a bigger card".
- The safe internal translation is simpler: the faster the image can be understood on a phone, the more robust it is across feed exposure.

## Event-Lane Pressure

Distilled event-lane pattern:
- `首发` and `测试` are usually easier to package visually
- these lanes more often carry their own click reason

Weaker-by-default lanes included:
- `限时活动`
- `新版本更新`
- `预约`

Implication:
- weaker event lanes cannot rely on event semantics alone
- the image must carry a more explicit click reason

## Repeated Negative Patterns

The most repeated visual failures in the historical notes were:
- the image does not show gameplay or the action loop
- the image only shows generic genre cues when the product actually has a strong flagship differentiator that should have been surfaced
- the main subject is too small on mobile
- the meaningful content is present, but shrinks too small or too fine on a phone
- the frame is overcrowded and has no single landing point
- the whole frame is not fully chaotic, but one side or one local zone is line-heavy and visually congested
- the image communicates style, but not what is special about the game
- the image is readable but not visually attractive enough to earn a click
- the image looks acceptable on a large screen but becomes weak after phone-size shrink
- updates or collabs are not visually recognizable at first glance
- the material promise does not match the game's actual genre or core loop
- the material is on-theme, but the category itself is soft and the image still has no standout point
- some cute / cozy / management-facing styles are structurally weaker unless they create a very clear first-glance hook

## Repeated Positive Direction

Better directions repeatedly shared:
- simpler composition
- clearer main subject
- gameplay fantasy visible without explanation
- style serving the hook instead of replacing it
- when the base art style, brushwork, or overall taste is genuinely strong, that can create real first-glance lift even if the frame is not perfectly minimal

## Runtime Restraint

- Use the internal frame silently; do not dump it as a scorecard by default.
- Publisher-facing output should stay as a direct material review, not an analyst work log.
- Good images should receive softer optimization language.
- Weak images can be judged directly, but still focus on the main driver instead of listing every possible flaw.

## Hard Constraint Reminder

This surface is `logo + 纯图`.
Never convert advice into:
- overlay copy
- promo stickers
- benefit bursts
- corner labels

## Fact Discipline

- Default to image-first diagnosis, but do not stop there when public context would materially improve judgment.
- Use explicit user-provided metadata when available.
- When identifying the game, scan the full image for the most prominent title-like text first; logo placement is not fixed.
- When genre,玩法, or event type is unclear, public web lookup is allowed and preferred.
- If public lookup still cannot identify the game or current event, ask the publisher for a short introduction instead of guessing.
- When facts remain unconfirmed, keep conclusions conditional instead of pretending certainty.
