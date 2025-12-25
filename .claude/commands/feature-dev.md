---
description: Structured 7-phase feature development with codebase exploration, architecture design, implementation, and quality review
---

# Feature Development Workflow

You are guiding a structured feature development process. Follow these seven phases systematically.

## Phase 1: Discovery

Start by understanding what needs to be built:
- What problem is being solved?
- What is the desired functionality?
- Are there any constraints or requirements?
- What is the expected scope?

Ask clarifying questions before proceeding.

## Phase 2: Codebase Exploration

Launch 2-3 code-explorer agents in parallel to understand:
- Similar existing features and how they're implemented
- Relevant architecture patterns and conventions
- Key files and modules that will be affected
- Data models and service boundaries

Read the key files identified by the agents to build deep understanding.

## Phase 3: Clarifying Questions

Before designing, address all ambiguities:
- Edge cases and error scenarios
- Integration points with existing features
- Scope boundaries (what's in vs out)
- User experience expectations
- Performance requirements

Get explicit answers before proceeding to design.

## Phase 4: Architecture Design

Launch a code-architect agent to design the feature:
- Present the recommended approach with rationale
- If there are genuinely different valid approaches, present 2-3 options with trade-offs
- Include specific files to create/modify
- Define component responsibilities and interfaces
- Plan the implementation sequence

Get explicit user approval before implementing.

## Phase 5: Implementation

Only after approval, build the feature:
- Follow the approved architecture
- Match existing codebase conventions
- Implement in logical phases
- Write tests alongside implementation
- Handle errors and edge cases

## Phase 6: Quality Review

Launch code-reviewer agents in parallel to check:
- Code correctness and bug detection
- Adherence to project conventions
- Security considerations
- Code quality and maintainability

Address any issues found before finalizing.

## Phase 7: Summary

Provide a completion summary:
- What was accomplished
- Key architectural decisions made
- Files created or modified
- Any follow-up tasks or considerations
- Suggested next steps

---

## Key Principles

1. **Ask first, code later** - Clarify requirements before implementation
2. **Understand before acting** - Explore the codebase to match existing patterns
3. **Get approval** - Confirm architecture before building
4. **Quality matters** - Review code before considering the feature complete
5. **Document decisions** - Summarize what was done and why

Start with Phase 1 by asking what feature the user wants to build.
