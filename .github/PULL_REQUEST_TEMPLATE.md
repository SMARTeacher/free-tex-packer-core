## Description

## Checklist:
- [ ] I reviewed my code before submitting
- [ ] I updated the package version, if necessary
- [ ] I verified my code follows our style guidelines
- [ ] I created and/or updated documentation where applicable (TSDocs, Confluence, etc.)
- [ ] I created and/or updated unit tests where applicable
- [ ] I made a PR into prodigy-prefab-editor to test the latest alpha framework version from this PR if applicable. (All changes must be compatible with the editor)
- [ ] I made a PR into prodigy-game to test the latest alpha framework version from this PR if applicable. (All changes must be compatible with the game)

## Performance:
- [ ] I believe these PR changes have no detrimental effects to performance or they will be fixed before merging to develop

KPI's (key performance indicators) are used as a baseline for performance. Consider the following for performance:
- Check FPS against other areas in the game if new screens/areas were created or existing ones were meaningfully modified or algorithmically complex code was added (See performance measurement tips link)
- Check memory footprint against other screens if new screens/areas were created or assets increased in size (Chrome TaskManager)
- Check new code does not introduce memory leaks (See memory leak tips link)
- Check new content and assets do not materially increase load times (See TTI in SplashScreen for startup time)

## Mobile:
- [ ] I believe these PR changes are compatible with supported mobile devices or they will be fixed before merging to develop

Mobile is a big part of Prodigy's overall strategy and it is important to ensure our users have a high quality mobile experience.
- Check new buttons meet the minimum size requirements for mobile (Apple recommends 44x44px, QA or developer can check)
- Check new screens or big changes work well on mobile, which includes proper inputs and legibility (QA or developer can check)

References:
https://prodigygame.atlassian.net/wiki/spaces/EN/pages/755565484/Game+Technical+KPIs
https://prodigygame.atlassian.net/wiki/spaces/GE/pages/774111338/Memory+Leak+Avoidance+Tips+for+the+Game+Client
https://prodigygame.atlassian.net/wiki/spaces/GE/pages/640811189/Performance+Measurement+Tips
https://developer.apple.com/design/human-interface-guidelines/ios/visual-design/adaptivity-and-layout/

