# Tasks for Feature F02

## T01 — Add LICENSE template to .j3/
**Status**: done
**Description**: Add an MIT `LICENSE` template file to `.j3/` for use when bootstrapping new projects.

## T02 — Add README.md template to .j3/
**Status**: done
**Description**: Add a `README.md.template` to `.j3/` with placeholder sections: app name, description, install instructions, and usage.

## T03 — Add .gitignore template to .j3/
**Status**: done
**Description**: Add a `.gitignore.template` to `.j3/` appropriate for Python/uv projects (covers `.venv/`, `__pycache__/`, `*.pyc`, `.pytest_cache/`, `dist/`, etc.).

## T04 — Update bootstrap.md and method.md
**Status**: done
**Description**: Update `.j3/bootstrap.md` and `.j3/method.md` to include `LICENSE`, `README.md`, and `.gitignore` as required files in the scaffold steps.

## T05 — Add open-source files to j3 repo itself
**Status**: done
**Description**: Ensure the j3 repo has its own `LICENSE`, `README.md`, and `.gitignore` files — not templates, but the real files.

## T06 — Write tests for open-source scaffold
**Status**: done
**Description**: Write pytest tests verifying that bootstrapped projects contain `LICENSE`, `README.md`, and `.gitignore` with expected content (MIT license text, app name placeholder, .venv in gitignore).
