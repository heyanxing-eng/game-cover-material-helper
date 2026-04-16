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

## Genre / Experience Archetypes

Use the same five-dimension frame, but shift weighting by primary experience archetype.

Recommended archetypes:
- `可爱治愈 / 软萌 / 家园 / 装扮`
- `模拟经营 / 建造 / 种田 / 开店 / 生活模拟`
- `二次元角色向 / 抽卡 / 角色养成`
- `二次元动作向 / ARPG / 共斗`
- `动作 / ACT / ARPG / 射击 / 格斗`
- `武侠 / 仙侠 / 国风冒险`
- `叙事 / AVG / 剧情 / 悬疑 / 解谜`
- `恐怖 / 生存 / 末日 / 废土`
- `策略 / 塔防 / SLG / 国战`
- `肉鸽 / 构筑 / 卡牌策略`
- `平台跳跃 / 像素动作 / 独立冒险`
- `休闲益智 / 派对 / 合成 / 轻竞技`

Archetype reminders:
- soft / cute / healing-facing materials deserve extra weight on `浏览舒适度`, `主体明确`, and `第一眼讨喜`
- character-driven anime materials deserve extra weight on `角色魅力`, `脸`, `气质`, and who actually wins first glance
- action-facing materials deserve extra weight on `动作张力`, `敌我冲突`, and `正在发生什么`
- narrative-facing materials deserve extra weight on `故事感`, `关系张力`, `悬念`, and `线索钩子`
- management-facing materials deserve extra weight on `经营对象`, `经营结果`, and `循环感`
- strategy-facing materials deserve extra weight on `博弈感`, `阵营对抗`, and `机制辨识度`

Classification discipline:
- do not classify only by art style or wrapper theme
- prefer what the user expects to *do* in the game over what world the image appears to inhabit
- `二次元` and `国风` are not enough by themselves; split by actual experience type
- in hybrid products, prioritize what the current asset is trying to sell now

## Recognition Modifier

Recognition can be part of the click reason.

Especially relevant for:
- strong IPs
- famous character casts
- long-running titles with established affection for specific faces or heroes

Constraint:
- recognition is a real positive
- but it cannot erase severe clutter, weak mobile readability, or lack of focal point

## Multi-Image Comparison Notes

When comparing multiple candidate covers:
- do not treat the task as independent single-image judgments
- normalize the comparison to the same phone browse surface and same approximate display size
- choose the relative winner first, then explain why

Comparison weighting:
- `clearer focal point / stronger mobile readability / lower reading cost` are harder advantages
- `richer theme detail / fuller atmosphere / more specific setting flavor` are softer advantages
- do not let `信息更具体` automatically beat `更顺眼、更轻松、更容易被接住`

Special reminder for soft categories:
- for cute / cozy / healing / life-sim / decoration-facing materials, `浏览舒适度` and `主体明确` deserve extra weight in side-by-side comparison
- a cleaner and more immediately likable image can beat a more theme-specific but more fragmented one

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
