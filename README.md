# CPU Command Center — COA Interactive Learning Lab

A simple **HTML + CSS + JavaScript** microproject for Computer Organization and Architecture.

## Learning Flow

**01 → Instruction Cycle**
- User selects an instruction such as `ADD R1, R2, R3`.
- Every stage automatically uses that exact instruction.
- FETCH shows the instruction entering the CPU.
- DECODE identifies opcode, operation and operands.
- EXECUTE calculates/shows the operation result.
- WRITE-BACK shows where the result is stored.
- The PC/ALU/register dashboard has been removed to keep the learning focus clear.

**02 → Mystery Decoder**
- The CPU randomly generates an instruction.
- The student guesses:
  - Opcode
  - Instruction Type
  - Instruction Format
  - Operands
- The system reveals the correct answer and gives a hint.

**03 → CPU Mission Lab**
- Replaces the old format builder.
- An AI-style mission gives the student a task.
- The student assembles an instruction to solve the mission.
- The system checks the instruction.

**04 → Final Challenge**
- Five COA questions.
- Score out of 100.
- Final completion screen.

## Design

Matcha Green + Light Brown + Vanilla Cream + Black.

The project uses separate pages so each Command Center module feels like the next level in a guided learning flow.

## Files

```text
CPU_Command_Center/
├── index.html
├── cycle.html
├── decoder.html
├── mission.html
├── challenge.html
├── style.css
└── README.md
```

## Run

Extract the ZIP and open `index.html` in Chrome/Edge/Firefox.

No Node.js, backend, framework, or installation is required.


### Cycle example
For `ADD R1, R2, R3`, the flow demonstrates: `FETCH → ADD R1, R2, R3` → `DECODE → ADD + R1,R2,R3` → `EXECUTE → 10 + 20 = 30` → `WRITE-BACK → R3 ← 30`.

### Instruction Cycle interaction
The AI RUN CYCLE button starts the selected instruction at FETCH. The AI does not auto-rush through the stages. The learner controls progression with NEXT STAGE. Any stage (FETCH, DECODE, EXECUTE, WRITE-BACK) can also be clicked directly to revisit that stage and regenerate its explanation for the selected instruction.

## Deployment Link: https://cpucommandcenter.vercel.app/
## Github Link: https://github.com/Maddzweb2006/CPU_CommandCenter