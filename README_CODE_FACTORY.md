Daily usage afterward:

- Pull latest skills from upstream: cd agent-skills && git fetch upstream && git merge upstream/main && git push origin main
- Then in code-factory: git add agent-skills && git commit -m "Bump agent-skills" to record the new pointer.
- Or one-shot: git submodule update --remote --merge agent-skills from the code-factory root.
