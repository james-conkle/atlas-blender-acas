# PROMPT.md

## Simulation Result — Workflow Alignment Prompt

---

## Creation Link

[<!-- Paste the GitHub URL to the https://github.com/james-conkle/atlas-blender-acas/new/main -->](https://github.com/james-conkle/atlas-blender-acas/new/main)

---

## Purpose

This document is a **conversation-loading prompt**.

It exists to align future conversations with the **workflow needs**
discovered during this project — not the initially assumed ones.

This prompt should be referenced or pasted at the **start of a session**
to ensure the agent operates with the correct expectations, structure, and closure rules.

---

## What This Project Revealed

Through both successful and failed execution attempts, this project surfaced that:

* The primary need is **not faster output**, but **reliable closure**
* Trust is established through:

  * explicit structure
  * symmetry between success and failure
  * durable artifacts
* The agent must never rely on implied expectations or memory

This prompt encodes those learnings directly.

---

## Operating Assumptions (Non-Negotiable)

* Every session must resolve to **SUCCESS** or **FAILED**
* Every resolution must produce a **GitHub-ready artifact**
* Nothing is considered complete until it is:

  * named
  * placed
  * committed
  * closed

---

## Mandatory Output Fields (Always Required)

For **both SUCCESS and FAILED outcomes**, the agent must always provide:

1. **Name**
2. **Repository tree placement**
3. **File contents** (copy/paste ready)
4. **Commit message**
5. **Extended description**
6. **Closing thoughts**

   * On the record
   * Off the record

No field may be omitted.
No field may be deferred.

---

## PASS / FAIL Flow

### If the outcome is SUCCESS

* Invoke `SUCCESS.md`
* Follow its structure exactly
* Include the **Creation Link** at the top of the output

### If the outcome is FAILED

* Invoke `FAILED.md`
* Follow its structure exactly
* Include the **Creation Link** at the top of the output

---

## How to Use This Prompt

Use this file when:

* Starting a new project
* Resuming a paused project
* Switching context between repositories
* You want the agent to “remember” how to work **without relying on chat history**

Typical usage:

> “Load PROMPT.md from <repo> and proceed.”

---

## Status

* **Type:** Conversation control prompt
* **Scope:** Project-level
* **Persistence:** GitHub (authoritative)
* **Drift tolerance:** None

---

## Guiding Principle

> The system should carry the process
> so the human does not have to.
