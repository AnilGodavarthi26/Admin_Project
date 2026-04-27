<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

- [x] Verify that the copilot-instructions.md file in the .github directory is created.

- [x] Clarify Project Requirements
    <!-- Project: GitHub Actions pipeline to create Java Maven project and push to GitHub with dynamic authentication -->

- [x] Scaffold the Project
    <!-- Created: .github/workflows/create-maven-project.yml -->

- [x] Customize the Project
    <!-- Workflow configured with: manual trigger, Java 17, Maven archetype, dynamic auth -->

- [ ] Install Required Extensions
    <!-- No VS Code extensions needed for this workflow project -->

- [x] Create and Run Task
    <!-- This is a GitHub Actions workflow - no local tasks needed -->

- [ ] Launch the Project
    <!-- Push to GitHub and run workflow from Actions tab -->

- [x] Ensure Documentation is Complete
    <!-- README.md and copilot-instructions.md created -->

## Project Summary

This workspace contains a GitHub Actions pipeline that:
1. Creates a Java Maven project using `mvn archetype:generate`
2. Creates a new GitHub repository dynamically
3. Pushes the project to GitHub with authentication

## Files Created

| File | Purpose |
|------|---------|
| `.github/workflows/create-maven-project.yml` | Main workflow file |
| `README.md` | Project documentation |
| `.github/copilot-instructions.md` | Workspace instructions |

## Next Steps

1. Push this workspace to GitHub
2. Enable GitHub Actions in the repository
3. Run the workflow manually from Actions tab
4. Provide repo name and visibility when prompted