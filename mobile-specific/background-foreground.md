# Checklist: Background / Foreground

## ✅ Core Checks
- [ ] Press Home → game goes to background
- [ ] Reopen → game continues from last state
- [ ] Idle timer keeps running
- [ ] Notifications appear while in background

## 🐛 Edge Cases
- [ ] Background for a long time (>30 min) → no crash
- [ ] Background during ad → ad resumes or refreshes
- [ ] Background while popup is open → popup remains
