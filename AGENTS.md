<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Portfolio architecture
- Keep the single-page portfolio at the index route with section anchors; all content is one coherent résumé-led experience.
- Store career and work-highlight data in a browser-safe shared module, and keep illustrative charts in a reusable visual component for consistent cards and factual content.
- Use an explicit mailto contact workflow without storing submissions; the portfolio does not have a connected email delivery service.
- Keep theme and all visual styles in the global semantic design system; the theme toggle switches the document theme after hydration.
