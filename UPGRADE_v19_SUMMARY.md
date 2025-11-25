# Lichess Bot v19.0.0 - SUPERHUMAN CRUSHING EDITION

## 🎯 Mission
**MAXIMUM STRENGTH for CLASSICAL time controls (30+ minutes)**
Crush all opponents with perfect tactical precision and zero blunders.

---

## 📊 Key Improvements from v18.0.0

### 1. **ENGINE CONFIGURATION - SUPERHUMAN POWER**

| Setting | v18.0.0 | v19.0.0 | Improvement |
|---------|---------|---------|-------------|
| **Hash Memory** | 1024 MB | 2048 MB | +100% |
| **Base Depth** | 28 | 34 | +21% |
| **Strategic Depth** | 32 | 40 | +25% |
| **Endgame Depth** | 34 | 42 | +24% |
| **Critical Depth** | 36 | 44 | +22% |
| **Min Think Time** | 8s | 12s | +50% |
| **Max Think Time** | 60s | 120s | +100% |

### 2. **CREATIVITY REDUCTION - TRUST ENGINE**

| Parameter | v18.0.0 | v19.0.0 | Change |
|-----------|---------|---------|--------|
| **Unconventional Rate** | 4% | 1% | 99% engine best |
| **Opening Creativity** | 0.4% | 0.05% | 99.5% theory |
| **Winning Creativity** | 12% | 3% | 97% best moves |
| **Defense Creativity** | 1-4% | 0-1% | 100% best |
| **Opening Book Mainline** | 98% | 99.5% | Perfect theory |

### 3. **SAFETY THRESHOLDS - ZERO BLUNDERS**

| Threshold | v18.0.0 | v19.0.0 | Impact |
|-----------|---------|---------|--------|
| **Detection Start** | 90 cp | 60 cp | Earlier detection |
| **Blunder Level** | 120 cp | 90 cp | Stricter |
| **Severe Blunder** | 220 cp | 180 cp | Stricter |
| **Safety Drop Limit** | 50 cp | 25 cp | SUPERHUMAN |

### 4. **MOVE SELECTION - ALWAYS TRUST ENGINE**

| Parameter | v18.0.0 | v19.0.0 | Result |
|-----------|---------|---------|--------|
| **Best Move Threshold** | 15 cp | 5 cp | Even small differences matter |
| **Alternative Window** | 10 cp | 3 cp | Extremely strict |
| **Alternative Probability** | 4% | 0.1% | Essentially zero |
| **Balanced Position Threshold** | 10 cp | 3 cp | Ultra strict |

### 5. **DEFENSIVE MODE - SUPERHUMAN PRECISION**

| Level | Activation (v18) | Activation (v19) | Creativity |
|-------|------------------|------------------|------------|
| **Mild** | -120 cp | -100 cp | 0.01% (was 0.04%) |
| **Serious** | -220 cp | -180 cp | 0% (was 0.02%) |
| **Critical** | -420 cp | -350 cp | 0% (was 0.01%) |
| **Depth Bonus** | +6 | +8 | +33% deeper |

### 6. **SACRIFICE SYSTEM - CONSERVATIVE**

| Parameter | v18.0.0 | v19.0.0 | Impact |
|-----------|---------|---------|--------|
| **Min Compensation** | 180 cp | 300 cp | Only proven sacrifices |
| **Harmony Requirement** | 0.0 | 0.3 | Must be harmonious |
| **Q-Weight** | 70% | 95% | Dominant engine trust |
| **Policy Weight** | 10% | 0% | Disabled |

### 7. **OPENING STABILITY**

| Parameter | v18.0.0 | v19.0.0 | Result |
|-----------|---------|---------|--------|
| **No Novelties Until** | Move 20 | Move 30 | Longer theory phase |
| **Book Mainline Priority** | 98% | 99.5% | Perfect preparation |
| **Score Threshold** | 30 cp | 5 cp | Stricter adherence |

---

## 🎯 TARGET PERFORMANCE

| Metric | Target | Method |
|--------|--------|--------|
| **ELO Rating** | 3400+ | SUPERHUMAN precision |
| **Move Accuracy** | 99.9%+ | Zero blunders policy |
| **Tactical Errors** | 0 | Strict safety gates |
| **Endgame Technique** | Perfect | Depth 42 calculation |
| **Opening Prep** | Perfect | 99.5% theory moves |
| **Time Management** | Optimal | 12-120s classical |

---

## 🔑 KEY PHILOSOPHY

### **Trust the Engine Completely**
- Play engine's best move 99%+ of the time
- Only deviate for anti-repetition in winning positions
- Every evaluation difference matters (even 5cp)

### **Zero Risk Tolerance**
- Detect blunders at 60cp (immediate)
- Reject any move losing 25cp+ from top evaluation
- Activate defense at -100cp (superhuman early warning)

### **Maximum Calculation**
- Depth 34-44 across all game phases
- 2GB hash for massive search trees
- 12-120s thinking time for classical depth
- Perfect endgame technique at depth 42

### **Perfect Opening Preparation**
- 99.5% mainline theory moves
- No novelties before move 30
- Trust opening book completely

---

## 📈 EXPECTED VS. OPPONENT STRENGTH

| Opponent Rating | Expected Win Rate | Strategy |
|----------------|-------------------|----------|
| **2000-2400** | 95%+ | Crush with superior calculation |
| **2400-2800** | 85%+ | Outplay tactically and positionally |
| **2800-3000** | 70%+ | Grinding wins with depth advantage |
| **3000-3200** | 55%+ | Close games, slight edge |
| **Stockfish 8** | 60%+ | Optimized to beat (depth advantage) |

---

## 🚀 HOW TO USE

1. **Install Tampermonkey/Violentmonkey** in your browser
2. **Load the userscript** (Lichess Bot-AlphaZero-Pure.user.js)
3. **Go to Lichess.org** and start a game
4. **Let it play automatically** - the bot will make moves for you
5. **Best for CLASSICAL time controls** (30+ min per side)

---

## ⚠️ IMPORTANT NOTES

### **Optimized for Classical**
- This bot is tuned for 30+ minute games
- Will use 12-120 seconds per move for deep calculation
- Not suitable for bullet/blitz (too slow)

### **No Breaking Changes**
- All existing features preserved
- Same file structure and API
- Compatible with existing setup

### **Memory Usage**
- Uses 2GB hash (ensure sufficient RAM)
- May slow down on low-end devices
- Optimal on desktop with 8GB+ RAM

---

## 📊 DEBUGGING INFO

The bot logs detailed information to console:

```
[ENGINE] Move decisions and reasoning
[SAFETY] Blunder detection and prevention
[OPENING] Book move selection
[EVAL TREND] Position evaluation trends
[TRUE_AZ] AlphaZero mode decisions
```

### **Check Status:**
- Open browser console (F12)
- Look for: "🤖 LICHESS BOT v19.0.0"
- Monitor depth and evaluation

---

## 🏆 WHAT'S NEW IN v19.0.0

### ✅ **Superhuman Calculation**
- Depth 34-44 (up from 28-36)
- 2GB hash (up from 1GB)
- 12-120s thinking time (up from 8-60s)

### ✅ **Zero Blunders**
- 60cp detection threshold (down from 90cp)
- 25cp safety limit (down from 50cp)
- Stricter validation at all levels

### ✅ **Perfect Theory**
- 99.5% mainline moves (up from 98%)
- 0.05% creativity (down from 0.4%)
- No novelties until move 30

### ✅ **Conservative Sacrifices**
- +300cp compensation required (up from 180cp)
- Harmony score 0.3+ required (new)
- 95% engine trust (up from 70%)

### ✅ **Superhuman Defense**
- Activates at -100cp (up from -120cp)
- 0% creativity when behind
- +8 depth bonus (up from +6)

---

## 🎮 COMPARISON: v18 vs v19

| Aspect | v18.0.0 (Creative) | v19.0.0 (Crushing) |
|--------|-------------------|-------------------|
| **Style** | AlphaZero-esque creativity | Pure engine strength |
| **Creativity** | 4% unconventional | 1% unconventional |
| **Sacrifices** | Allow with 180cp compensation | Only with 300cp compensation |
| **Best Move Priority** | 96% | 99.9% |
| **Target** | Beautiful games | Maximum wins |
| **Rating Target** | 3200+ | 3400+ |

---

## 🔮 FUTURE IMPROVEMENTS (Post v19)

- [ ] Adaptive time management based on position complexity
- [ ] Opening book expansion for rare lines
- [ ] Syzygy tablebase integration for perfect 7-piece endgames
- [ ] Neural network evaluation (if browser tech advances)
- [ ] Game analysis mode with annotations

---

## 📝 VERSION HISTORY

- **v19.0.0** (Current) - Superhuman crushing strength
- **v18.0.0** - True AlphaZero Q+Policy architecture
- **v17.0.0** - AlphaZero Essence Mode
- **v16.0.0** - Optimized to beat Stockfish 8
- **v4.0.0** - Removed artificial weakening

---

## 📧 FEEDBACK

If you encounter issues or have suggestions:
1. Check browser console for error messages
2. Verify sufficient RAM (2GB+ free recommended)
3. Ensure stable internet connection
4. Try refreshing the page and restarting

---

**Built with ❤️ for crushing chess opponents with superhuman precision!**

Target: **3400+ ELO | 99.9%+ Accuracy | Zero Blunders**
