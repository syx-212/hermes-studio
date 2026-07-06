---
date: 2026-07-05
pr: pending
feature: Hide promotional sidebar entries
impact: Chat and group chat sidebars no longer render the API relay shortcut or the hardware promo badge; the new chat Agent selector only exposes Hermes; profile-facing labels are renamed from user wording to agent wording; the Add Provider preset picker hides the apikey.fun presets and no longer renders the registration link; pet UI and the main Tools group are hidden for the local package; chat runtime behavior is unchanged.
---

This local packaging customization removes promotional sidebar chrome only. The
chat run flow, session selection, settings navigation, group chat room handling,
and model/provider behavior are unchanged. New chat creation now presents only
Hermes in the Agent selector for this local packaging build. The Profile entry
is labeled as an agent selector in Chinese locales while login/account user
wording remains unchanged. The Add Provider preset picker also excludes the
Codex-apikey.fun and Claude-apikey.fun presets for this local package, and the
frontend no longer auto-routes custom apikey.fun URLs back into those hidden
presets. The local package also removes the Petdex sidebar entry, disables the
global web pet mount, hides the main Tools sidebar group, and removes the chat
header file/terminal tool panel entry.
