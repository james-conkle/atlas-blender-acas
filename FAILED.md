# FAILED.md

## Failure Capture Protocol

### Goal Not Achieved — Failure Recorded

---

## Purpose

This document defines the **standard failure capture action** for a work session
that did **not** achieve its stated objective.

When execution diverges from intent, or the outcome fails objective verification,
invoking “failed”, “this didn’t work”, or an equivalent phrase triggers the
creation of this artifact.

This protocol exists to **preserve signal**, prevent silent drift, and convert
failure into durable, inspectable data.

---

## Trigger Phrase

This protocol is executed when the user says, explicitly or implicitly:

* “failed”
* “this didn’t work”
* “that’s wrong”
* “stop”
* “abort”
* “this diverged”

---

## Required Output Structure

### 1. Failure Declaration

A plain statement that the goal was **not achieved**.
No justification. No mitigation.

---

### 2. Original Goal

Restate the original instruction **verbatim or near-verbatim**.

This anchors the failure to intent, not
