# Checklist: Offline Progress

**Feature:** Resource calculation while the game is closed.

## ✅ Core Checks
- [ ] "Welcome back" popup appears after reopening the game
- [ ] Offline time is calculated correctly (hours, minutes)
- [ ] Resources earned match rate × time
- [ ] Maximum offline cap is respected (e.g., 8 hours)
- [ ] "Claim" button works

## 🐛 Edge Cases
- [ ] Offline for less than 1 minute → no popup
- [ ] Offline longer than cap → resources calculated up to cap
- [ ] Offline during app update → data remains safe
- [ ] Changing device time forward by 1 hour → no abuse
