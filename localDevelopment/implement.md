Based on the build gap analysis you created, now implement the minimum ABC-compatible build path.

Instructions:

1. Do not make large refactoring changes unless required.
2. First create a working build using approved ABC runtime, base image, package registry, and CI/CD standards.
3. Replace unavailable dependencies only with approved internal alternatives.
4. Where approval is required, do not bypass controls. Add a clear TODO with governance action.
5. Update or create:

   * Dockerfile using approved base image
   * Build script
   * Test script
   * GitHub Actions workflow or ABC CI template
   * README build section
   * Dependency gap report
6. Validate the build command locally or through the available CI workflow.
7. For every file changed, explain:

   * Why it changed
   * What ABC standard it aligns to
   * Any remaining risk
8. Keep changes small, reviewable, and PR-ready.
