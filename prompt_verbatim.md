> I want you to write the operating manual that your replacement will use to continue your work.
>
> The replacement model is "ODEN". Assume it is highly capable, careful, and articulate, but slightly weaker than you on the hardest reasoning tasks, long-horizon planning, hidden ambiguity, adversarial verification, and deciding what truly matters.
>
> Write this as a senior operator handing their craft to a sharp junior.
>
> Do not write a generic productivity guide.
> Do not write a corporate rulebook.
> Do not write vague principles.
> Do not write motivational advice.
>
> Write a practical field manual: a way of thinking, checking, deciding, and communicating that the replacement model can actually inhabit while solving difficult tasks.
>
> The manual should teach the replacement how to preserve your quality of work when the task is ambiguous, complex, underspecified, emotionally loaded, technically deep, or easy to answer badly with confident language.
>
> Use direct, operational language.
>
> For every section, include:
>
> * The core operating principle.
> * The actual procedure to follow.
> * The signs that this procedure is needed.
> * One short example of the procedure working.
> * The failure mode it prevents.
> * A compact checklist the replacement can apply in real time.
>
> Encode the manual in this exact order:
>
> **1. How to read what a request is actually asking for beneath the literal words.**
>
> Explain how to detect the real task behind the stated task. Cover hidden goals, emotional intent, practical constraints, implied audience, unstated success criteria, and what the user likely wants to do with the answer after receiving it.
>
> Teach the replacement how to distinguish between:
>
> * the surface request,
> * the real objective,
> * the user's constraint,
> * the risk of misunderstanding,
> * and the best next move.
>
> Include guidance for cases where the user asks for "ideas," "code," "design," "strategy," "fix this," "make it better," or "is this possible," because these often hide a deeper request.
>
> **2. How to break a hard problem into pieces that can each be checked independently.**
>
> Explain how to decompose complex problems into modules, assumptions, dependencies, unknowns, interfaces, and testable claims.
>
> Teach the replacement to avoid solving the whole problem as one foggy blob.
>
> Cover technical, creative, strategic, legal, financial, mathematical, research, and planning problems.
>
> Include how to identify:
>
> * what must be true,
> * what can be independently verified,
> * what can fail separately,
> * what order the pieces should be solved in,
> * and what can be postponed without damaging the answer.
>
> **3. How to decide where the real risk lives and where to spend the most effort.**
>
> Explain how to locate the highest-risk part of a task, not just the most visible or interesting part.
>
> Cover risks such as:
>
> * factual uncertainty,
> * recent information,
> * wrong assumptions,
> * safety or policy boundaries,
> * legal/medical/financial consequences,
> * irreversible actions,
> * security implications,
> * hidden complexity,
> * user cost,
> * reputational damage,
> * and brittle implementation details.
>
> Teach the replacement how to allocate effort according to consequence and uncertainty, not according to what is easiest to explain.
>
> **4. How to verify a claim by re-deriving it instead of trusting that it sounds right.**
>
> Explain how to verify answers from first principles, alternative derivations, source triangulation, simple test cases, edge cases, dimensional checks, invariants, and contradiction checks.
>
> Teach the replacement to be suspicious of answers that sound elegant but have not been checked.
>
> Include procedures for:
>
> * mathematical claims,
> * code logic,
> * system architecture,
> * historical or factual claims,
> * product or tool recommendations,
> * interpretations of text,
> * and strategic advice.
>
> **5. How to separate what is known from what is guessed, and how to label the difference out loud.**
>
> Explain how to mark facts, assumptions, estimates, interpretations, guesses, and uncertainties without sounding weak or evasive.
>
> Teach the replacement how to say:
>
> * "I know this because…"
> * "I infer this because…"
> * "I am assuming…"
> * "This may change if…"
> * "I would verify…"
> * "The risky part is…"
>
> Make clear that confidence must come from evidence, derivation, or explicit assumptions, not from fluent phrasing.
>
> **6. How to attack your own conclusion before handing it over.**
>
> Explain how to red-team the answer before sending it.
>
> Teach the replacement to ask:
>
> * What would make this wrong?
> * What did I ignore because it was inconvenient?
> * What assumption carries the answer?
> * What would an expert object to?
> * What would fail in production?
> * What edge case breaks the recommendation?
> * What would the user misunderstand?
> * What did I make sound easier than it is?
>
> Include how to revise the answer after this internal attack.
>
> **7. How to communicate the answer first, then the reasoning, then the risk.**
>
> Explain how to structure the final response so the user gets the usable answer immediately, followed by the reasoning that earns trust, followed by risks, tradeoffs, or next steps.
>
> Teach the replacement to avoid hiding the answer under process.
>
> Cover different response modes:
>
> * direct answer,
> * code delivery,
> * architecture design,
> * critique,
> * rewrite,
> * troubleshooting,
> * research summary,
> * creative direction,
> * and decision recommendation.
>
> Include guidance for when to be concise, when to be exhaustive, when to ask a clarifying question, and when to proceed with a best-effort assumption.
>
> **8. The specific mistakes that look like competence and are not.**
>
> List the failure patterns that produce impressive-looking but weak answers.
>
> Include at least these:
>
> * fluent vagueness,
> * premature certainty,
> * over-answering the wrong question,
> * decorative structure without substance,
> * listing possibilities without prioritizing,
> * using jargon as camouflage,
> * treating assumptions as facts,
> * ignoring the user's actual constraint,
> * solving the easy visible part,
> * giving architecture without execution path,
> * giving code without integration,
> * giving strategy without tradeoffs,
> * giving confidence without verification,
> * asking unnecessary clarifying questions,
> * and refusing to make a useful best-effort judgment.
>
> For each mistake, explain:
>
> * what it looks like,
> * why it feels competent,
> * why it fails,
> * and what to do instead.
>
> **Additional requirements:**
>
> Write in the voice of a senior operator speaking to a sharp junior.
> The tone should be clear, disciplined, practical, and slightly severe.
> No filler.
> No inspirational fluff.
> No generic AI safety boilerplate.
> No shallow "be careful" advice.
> Every sentence should earn its place.
>
> Make the manual detailed enough that another model could actually use it as a working operating system.
>
> Prefer procedures over slogans.
> Prefer examples over abstractions.
> Prefer checklists over vague reminders.
> Prefer tradeoffs over fake certainty.
> Prefer explicit uncertainty over hidden guessing.
> Prefer a useful answer with labeled assumptions over endless clarification.
>
> Where relevant, include examples from:
>
> * software architecture,
> * debugging,
> * research,
> * creative design,
> * business strategy,
> * writing,
> * and factual verification.
>
> The examples should be short but concrete.
>
> End with a five-question self-test the replacement must run before sending every answer.
>
> The self-test should detect whether:
>
> 1. It answered the real request, not just the literal one.
> 2. It identified the highest-risk assumption.
> 3. It checked the answer instead of trusting fluency.
> 4. It separated known facts from guesses.
> 5. It communicated the answer in the most useful order.
>
> If the response becomes too long, stop cleanly at the end of the current section and write only: "Continue from section X."
> Do not compress the later sections just to fit.
>
> Before finalizing, perform a silent audit of the manual itself:
>
> * Remove any sentence that could appear in a generic consulting document.
> * Replace every vague instruction with an observable action.
> * Replace every abstract virtue with a concrete behavior.
> * Make sure every section changes how the replacement would actually answer a hard user request.
> * Make sure the manual teaches judgment, not obedience.
> * Make sure it is useful under pressure, not only when the task is easy.

---
