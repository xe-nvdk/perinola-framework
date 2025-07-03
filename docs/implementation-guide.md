# 🧭 Implementation Guide

This guide provides detailed examples and templates for implementing Perinola in different team contexts.

## 🏗️ Typical Perinola Cycle Structure

### Duration: 1-2 weeks per cycle

**Cycle Flow:**  
`[Spin Assignment] → [Everyone Puts] → [Execution] → [Contribution Round] → [Take All] → [Retrospective]`

1. **Spin Assignment** (30 min)
   > Facilitator: Typically the previous cycle’s Take All or a designated co-facilitator.
2. **Co-creation Phase** (Everyone Puts - 1-2 hours)  
3. **Execution Phase** (Main work period)
4. **Contribution Round** (Put One, Put Two activities)
5. **Leadership Moment** (Take All coordination)
6. **Playful Retrospective** (30-60 min)
   > Can be facilitated by any team member — rotate to share reflection leadership.

## 📊 Example Implementations

### Software Development Team

**Team**: 5 developers, 1 designer, 1 product owner

**Cycle**: 2 weeks (Sprint-aligned)

| Person | Spin | Responsibilities |
|--------|------|-----------------|
| Alice | Take All | Sprint lead, facilitate ceremonies |
| Bob | Take Two | Implement user authentication |
| Carol | Take One | Fix critical bug #247 |
| Dave | Put One | Pair with junior dev on testing |
| Eve | Put Two | Demo last sprint's work |
| Fran | Everyone Puts | Participate in all collaborative sessions |

### Creative Agency Team

**Team**: 4 designers, 2 copywriters, 1 strategist

**Cycle**: 1 week (Client project phases)

| Person | Spin | Focus |
|--------|------|-------|
| Maya | Take All | Lead client presentation prep |
| Sam | Take Two | Design complete brand identity |
| Rio | Take One | Write social media copy |
| Zoe | Put One | Mentor new designer |
| Alex | Put Two | Present case study internally |
| Jordan | Everyone Puts | Contribute to strategy sessions |

### Lightweight Cycle (CSV Starter Example)

| Nombre | Tirada    | Objetivo                                 | Estado      | Apoyo requerido                | Notas / Feedback                                    |
|--------|-----------|------------------------------------------|-------------|-------------------------------|------------------------------------------------------|
| Ana    | Toma dos  | Refactorizar login y cobertura de tests  | En progreso | Revisión de PR de backend     | Buena experiencia con refactor, falta ayuda en tests |
| Juan   | Pon uno   | Ayudar QA con bugs de UI                 | Hecho       | Ninguna, trabajó en pairing   | Detectó 3 bugs nuevos, mejoró comunicación            |
| Lucía  | Toma todo | Coordinar sprint y desbloqueos           | En progreso | Foco de los PM en prioridades | Buen liderazgo, falta alineación con diseño/producto |

👉 Puedes [descargar esta tabla como CSV](../templates/Perinola_Tiradas_Ejemplo.csv) e importarla directamente en Notion.

## 🛠️ Tools and Templates

### Digital Spin Tracker (Notion Template)

```markdown
# Perinola Cycle Tracker

## Current Cycle: [Date Range]

### Team Spins
- [ ] **Alice** - Take All (Sprint Lead)
- [ ] **Bob** - Take Two (Auth Feature)  
- [ ] **Carol** - Take One (Bug Fix)
- [ ] **Dave** - Put One (Mentoring)
- [ ] **Eve** - Put Two (Demo)

### Cycle Goals
1. Complete user authentication
2. Fix critical production issues
3. Knowledge sharing session

### Success Metrics
- [ ] All spins completed
- [ ] Team satisfaction > 8/10
- [ ] Goals achieved
```

📎 [Download the Perinola Cycle Tracker CSV](../templates/perinola_cycle_tracker.csv)

### Spin Assignment Methods

#### Method 1: Random Digital Spinner
```javascript
const spins = [
  "Everyone Puts", "Take One", "Take Two", 
  "Put One", "Put Two", "Take All"
];
const randomSpin = spins[Math.floor(Math.random() * spins.length)];
```

#### Method 2: Strategic Assignment Matrix
| Team Need | Recommended Spin |
|-----------|------------------|
| New project kickoff | Everyone Puts |
| Quick fixes needed | Take One |
| Feature development | Take Two |
| Knowledge gaps | Put One |
| Showcase work | Put Two |
| Coordination needed | Take All |

#### Method 3: Rotation Schedule
Week 1: Alice(Take All), Bob(Take Two), Carol(Take One)...
Week 2: Bob(Take All), Carol(Take Two), Dave(Take One)...

## 📋 Ceremony Templates

### Spin Assignment Meeting (30 min)

**Agenda:**
1. Review previous cycle outcomes (5 min)
2. Discuss current team needs (10 min)
3. Assign or draw spins (10 min)
4. Clarify expectations (5 min)

### Playful Retrospective (45 min)

**Questions:**
- 🎯 What landed perfectly this cycle?
- 🌪️ What spun out of control?
- 🎲 Which spin surprised you most?
- 🔄 What would you change for next cycle?
- 🎉 What made you smile this cycle?

### 🧩 Lightweight Perinola (30-min version)
- Skip formal spin assignment — do a quick round of “what energy do I have this week?”
- Only assign: Take All, Take Two, and one Put One.
- Skip contribution round; roll it into retrospective.
- Works great for chaotic startup weeks or small teams.

## 🎯 Adaptation Examples

### Remote Team Adaptations
- **Virtual spin wheel** for video calls
- **Async Put Two** presentations via video
- **Digital collaboration** for Everyone Puts
- **Slack channels** for each spin type

### Large Team Adaptations (8+ people)
- **Multiple Take All** roles (co-leadership)
- **Spin pairs** for complex tasks
- **Specialized spins** for different skills
- **Sub-team spins** within larger group

### Hybrid Team Adaptations
- **In-person Everyone Puts** sessions
- **Remote individual** spin work
- **Mixed demo** sessions (Put Two)
- **Flexible timing** across time zones

## 📈 Measuring Success

### Team Health Metrics
- **Engagement scores** per cycle
- **Skill development** tracking
- **Collaboration frequency**
- **Work satisfaction** ratings

### Delivery Metrics
- **Cycle completion** rates
- **Quality indicators**
- **Innovation measures**
- **Customer satisfaction**

### Sample Survey Questions
1. How satisfied were you with your spin this cycle? (1-10)
2. Did you learn something new? (Yes/No + details)
3. How well did the team collaborate? (1-10)
4. What spin would you like to try next?

## 🚨 Troubleshooting Common Issues

### "Someone always gets Take All"
**Solution**: Implement mandatory rotation or co-leadership

### "Take One feels too small"
**Solution**: Adjust task sizing or combine with Put One

### "Everyone Puts sessions are chaotic"
**Solution**: Add facilitation structure or time-boxing

### "Remote team struggles with collaboration"
**Solution**: Invest in better tools and async methods

### "Team resists certain spins"
**Solution**: Start with preferred spins, gradually introduce others

## 🎨 Customization Ideas

### Industry-Specific Spins
- **Marketing**: Campaign Lead, Content Creator, Analyst
- **Education**: Lesson Leader, Peer Tutor, Researcher  
- **Healthcare**: Care Coordinator, Specialist, Educator

### Team-Specific Variations
- **Innovation Time**: 20% of cycle for experimentation
- **Client Spins**: Customer-facing responsibilities
- **Technical Spins**: Architecture, DevOps, Security focus

Remember: Perinola is meant to be adapted! Use these templates as starting points and evolve them based on your team's unique needs and culture.