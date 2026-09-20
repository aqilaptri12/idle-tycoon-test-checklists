# Checklist: Resource Generation

**Feature:** Automatic resource generation (gold, gems, wood) per second.  
**Type:** Functional, Regression  
**Priority:** P1

## ✅ Core Checks
- [ ] Resources increase automatically according to the displayed rate
- [ ] Rate increases after upgrading a building
- [ ] Numbers stop during the tutorial
- [ ] Numbers continue while any popup is open
- [ ] Number formatting is correct (1K, 1M, 1B, 1T)

## 🧮 Calculations
- [ ] Rate = base rate + upgrade bonus
- [ ] Calculations are consistent across all devices
- [ ] No overflow when numbers exceed 2 billion

## 🐛 Edge Cases
- [ ] When resource = 0, it still displays "0" (not empty)
- [ ] When rate = 0, resources do not increase
- [ ] After 1 hour offline, resources increase correctly based on time

## 📱 Mobile Specific
- [ ] When the app is in the background, the counter continues
- [ ] When the app returns to foreground, resources update immediately
