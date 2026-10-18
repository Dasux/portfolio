
This directory contains the source code for Dasux's personal portfolio website, showcasing projects in embedded systems, model rocketry, and Linux system administration. The site demonstrates technical skills relevant to aerospace and space-tech roles.

# Portfolio Analysis: Skeptical Engineering Hiring Manager Perspective

## Context
Evaluating portfolio of final-year B.Tech ECE student for entry-level role at Indian aerospace/space-tech startup. Portfolio URL: https://dasux.github.io/portfolio/

## First Impression
The portfolio presents as a technically competent undergraduate with hands-on aerospace-adjacent projects (model rocketry) and systems administration experience. It feels more like a serious engineering portfolio than an overdesigned student site, though some design choices distract from technical content. The rocketry project shows genuine engineering effort but has areas where claims could be more precisely framed.

## Evaluation by Criteria

### 1. Professional Credibility
**Assessment:** Between serious engineering portfolio and overdesigned student site, leaning toward credible but with room for improvement.
**Why:** 
- Strong technical project (rocketry) with clear aerospace relevance
- Systems administration project shows practical Linux skills
- Clean, functional layout appropriate for engineering
- However: animations, gradient backgrounds, and conversational tone occasionally undermine professional seriousness
- Missing formal project documentation structure (no clear methodology, results sections)

### 2. Technical Credibility
**Assessment:** Completed work is reasonably clear, but ongoing/future work blurs lines and contains vague claims.
**Issues:**
- **Ongoing work:** "Developing TVC control-system architecture" is vague - what architecture? What stage?
- **Future work:** "Closed-loop control simulation/validation" lacks specificity about tools/methods
- **Inconsistency:** Claims ESP32 remote ignition but field notes suggest WiFi range limitations weren't adequately addressed
- **Unsupported:** Thrust measurements (35-65N) noted as "nozzle-less" and "invalid for performance characterization" - yet still presented as achievement

### 3. Engineering Evidence
**Assessment:** Good evidence of hands-on building and testing, but could better distinguish personal contributions.
**Evident:**
- Personal construction of propellant motors (KNO3/sucrose/sorbitol)
- ESP32-based ignition system design (MOSFET, buck converter, pull-down)
- Static-fire test conduction and data collection
- Identification of specific failure modes (relay, launch lug, stand)
**Missing:**
- Clear statement of what was done vs. what was assisted with
- Quantitative test data beyond thrust ranges
- Documentation of design iterations or trade-offs considered
- Specific technical decisions with rationale (e.g., why IRLZ44N MOSFET?)

### 4. Recruiter Usability
**Assessment:** Understandable within 60 seconds, but requires scrolling to find key details.
**Strengths:** 
- Featured projects immediately visible
- Skills grouped logically
**Weaknesses:**
- Key limitations buried in rocketry page (need to visit specific project)
- No executive summary or bullet-point highlights
- "Field Notes" section adds narrative but delays technical assessment

### 5. Presentation
**Assessment:** Generally good but with distracting elements.
**Distracting elements:**
- Gradient background on project cards
- Hover animations on skill icons
- Conversational tone ("scrapyard PVC tubing" is charming but unprofessional)
- Inconsistent typography hierarchy
- YouTube/GitHub/LinkedIn icons compete with content for attention
**Positive:**
- Clear visual separation of sections
- Appropriate color use (not overly bright)
- Readable fonts

### 6. Hiring Relevance
**Assessment:** Strong for embedded systems/hardware testing integration roles at aerospace startups.
**Relevant:**
- Hands-on embedded systems (ESP32, Arduino, STM32)
- Hardware testing experience (static-fire tests, thrust measurement)
- Systems integration (ignition system, propellant casting)
- Linux systems administration (RHEL deployment)
**Less relevant for pure avionics:**
- Limited mention of safety-critical systems design
- No exposure to aerospace standards (DO-178C, ECSS, etc.)

### 7. Honesty and Safety
**Assessment:** Generally honest but occasional overstatement and safety presentation concerns.
**Honesty issues:**
- Presenting nozzle-less thrust tests as meaningful achievement despite noting they're invalid
- "Successful static-fire tests" qualification is buried
- Flight attempt described without clear success/failure criteria upfront
**Safety concerns:**
- Rocketry experiments near populated area (Ajwa Lake) mentioned casually
- No discussion of safety protocols, PPE, or risk assessments
- Amateur propellant manufacturing presented without adequate safety context

## Five Specific Weaknesses (Ranked by Hiring Impact)

1. **Ambiguous claims about test validity** - Presenting invalid nozzle-less thrust data as achievement without sufficient caveat upfront (High impact - questions technical rigor)
   
2. **Vague ongoing/future work descriptions** - Phrases like "developing TVC control-system architecture" without specifying what was actually done (Medium impact - makes it hard to assess current skills)

3. **Insufficient distinction between personal vs. team contributions** - No clear statement of what was individually designed/built vs. collaborated on (Medium impact - critical for entry-level assessment)

4. **Presentation elements that undermine professionalism** - Animations, gradients, overly casual language in technical contexts (Medium-Low impact - affects first impression)

5. **Limited safety/contextual awareness in rocketry documentation** - Minimal discussion of safety protocols for propellant handling and flight testing (Medium impact - important for aerospace culture)

<!-- #################################### -->
## Five Specific Changes to Make (FOR THE USER ONLY, CLAUDE IS NOT TO MAKE THESE CHANGES ITSELF) 

1. **Add technical caveats upfront**: 
   Change: "Conducted static-fire tests showing 35-65N thrust" 
   To: "Conducted nozzle-less static-fire tests showing 35-65N thrust (not suitable for performance characterization due to lack of nozzle)"

2. **Specify ongoing work with concrete actions**:
   Change: "Developing TVC control-system architecture and mathematical model"
   To: "Designing servo-based TVC mechanism using MG90S servos and developing Simulink model for actuator response"

3. **Add personal contribution statement**:
   Add under each project: "Individual contributions: Designed ESP32 ignition circuit, formulated and cast propellant grains, conducted all static-fire tests, analyzed thrust data"

4. **Professionalize tone in key sections**:
   Change: "used PVC tubing from scrapyard as casing"
   To: "utilized reclaimed PVC piping for motor casing, selected for chemical compatibility and pressure rating"

5. **Add safety/protocol section**:
   Add: "Safety Note: All propellant handling conducted with PPE (safety glasses, gloves, face shield) in isolated outdoor area. Static tests performed behind polycarbonate barrier with remote ignition."

<!-- #################################### -->
