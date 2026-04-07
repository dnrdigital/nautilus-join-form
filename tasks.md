# Tasks

## Previous tasks (Marketing & profile tweaks)

### Payment step (NL only)
- [ ] Replace SWZ section: remove digital option, replace print dropdown with two checkboxes:
  - "Physical copy of Telegraph" (checkbox)
  - "Physical copy of SWZ Maritime — additional €3.95/month" (checkbox)
- [ ] When SWZ checkbox is toggled, dynamically update the membership cost card to show the additional €3.95/m

### Profile form
- [ ] Remove `PreferredMethodofContact` dropdown (contact checkboxes already replace it)
- [ ] Telegraph checkbox: show as "Telegraph" for UK, "SWZ Maritime" for NL (no Compass for Swiss — remove)
- [ ] Default telegraph checkbox to ticked (opted in)
- [ ] UK only: Nautilus Plus checkbox with benefits text
- [ ] UK only: Third party marketing checkbox with text
- [ ] Add salary field to profile (working members only)
- [ ] Ship field: only show if user is "at sea"
- [ ] Cadet start/end dates: only show for UK or NL students

### CRM panel
- [ ] Update source tags for any new/changed fields

### Before go-live
- [ ] Re-enable form validation

---

## Feedback Round 2 — Email responses (27-31 Mar 2026)

### Martyn Gray (Director of Organising) — 27 Mar

- [ ] **MG-1**: Add a "Shore-based" option — Martyn flagged something is missing (screenshot not viewable). Likely a question flow option. "Shore-based" already exists in RANK_OPTIONS so this may refer to a question step instead.

### Richard Moti & Arianne Neijenhuis (NL branch) — 30 Mar

- [ ] **NL-1**: Replace the rank list for NL members with NL-specific ranks (⏸ waiting for list)
- [x] **NL-2**: Pre-select "Netherlands" in Country of Residence if user already indicated NL employer
- [x] **NL-3**: Remove "Bank Transfer" payment tab for NL branch
- [x] **NL-4**: SWZ Maritim — two checkboxes: digital (€3.95) and physical (€4.13)
- [x] **NL-5**: Add "Quarterly" payment frequency option
- [ ] **NL-6**: Fix "other country" routing (⏸ skipped for now)
- [ ] **NL-7**: Member area — remove "Post" from communication options for NL members (⚠ question: is branch-specific field visibility feasible, or do we need separate forms per branch?)
- [ ] **NL-8**: Member area — check and fix duplicate communication options question (⚠ same question as NL-7)
- [ ] **NL-9**: Member area — remove annual salary question for NL members (⚠ same question as NL-7)
- ~~**NL-10**: Member area — remove "Perks & Benefits" tab for NL members~~ (ignored per Duncan)

### Piet Doerflinger (Swiss branch) — 31 Mar

#### Contact details
- [x] **CH-1**: Replace hero subtitle with lorem ipsum filler (all branches)
- [x] **CH-2**: Show fees in CHF and EUR on outcome cards
- [x] **CH-3**: Change address placeholder to "Street and number" (all users)

#### Personal details
- [x] **CH-4**: Default "I live in / I'm a resident of" to country from contact details
- [x] **CH-5**: Make employer name mandatory for CH memberships
- [x] **CH-6**: Swiss-specific rank dropdown with "Other" free-text option
- [x] **CH-7**: Updated reduced rate text with "gross salary" and "supply evidence" wording
- [x] **CH-8**: Reduced rate section hidden for CH Apprentice
- [x] **CH-9**: File upload for monthly payslip (normal CH reduced rate)
- [x] **CH-10**: File upload for apprenticeship contract (CH apprentice)

#### Payment
- [x] **CH-11**: Bank transfer header renamed for CH: "Bank transfer to Nautilus International Swiss Branch"
- [x] **CH-12**: Bank details, standing order instructions, and SEPA note added for CH
- [x] **CH-13**: CH bank transfer only shows Currency and Payment frequency (no account holder, sort code, etc.)
- ~~**CH-14**: Payment frequency reorder~~ (ignored — keeping same order for all branches)

#### Confirmation
- ~~**CH-15**: Thank-you text~~ (ignored)

---

## Questions to resolve

1. **MG-1**: ⏸ Duncan will check with Martyn — skip for now.
2. **NL-1**: ⏸ NL rank list not yet received — skip NL-1 until it arrives.
3. **NL-4**: ✅ Two separate checkboxes (user can opt into either or both).
4. **NL-6**: ⏸ Skip for now — leave "other country" routing as-is.
5. **CH-9/CH-10**: ✅ Prototype file upload (basic file input).
6. **CH-14 vs NL-5**: ✅ Use "Quarterly" as the label for both branches.
