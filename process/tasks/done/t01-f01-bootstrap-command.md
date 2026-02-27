# Tasks for Feature F01

## T01 — Add bootstrap command to method.md
**Status**: done
**Description**: Add a `bootstrap` command description to `.j3/method.md` that instructs Claude how to scaffold the `process/` folder structure when invoked on a new project.

## T02 — Create process/ scaffold instructions in .j3
**Status**: done
**Description**: Create a scaffold instruction set within `.j3` so Claude knows exactly what folders and files to create: `process/spec.md`, `features/notdone/`, `features/done/`, `tasks/notdone/`, `tasks/done/`, and the two templates.

## T03 — Update CLAUDE.md template for new projects
**Status**: done
**Description**: Add to `.j3` a CLAUDE.md template so that when copied to a new project, it references the correct app name and points Claude to read the `process/` folder.

## T04 — Verify bootstrap end-to-end
**Status**: done
**Description**: Manually verify the bootstrap works end-to-end by simulating a fresh project with only `.j3/` copied in.

## T05 — Write tests for bootstrap
**Status**: done
**Description**: Write a test (shell script or Python) that copies `.j3/` into a temp directory, runs the bootstrap, and asserts all expected files and folders exist with correct content.
