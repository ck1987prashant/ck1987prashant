# Quick Start Guide: Using the Documentation System

This guide will help you quickly start using the documentation system for tracking plans and learnings.

## Creating a Plan Document

When starting a new feature, issue, or initiative:

1. **Copy the template**:
   ```bash
   cp docs/templates/plan-template.md docs/plans/YYYY-MM-DD-your-feature-name.md
   ```

2. **Fill in the details**:
   - Update the metadata (date, author, status)
   - Describe the problem and goals
   - Outline your approach
   - Document progress as you work

3. **Keep it updated**:
   - Add progress updates as you work
   - Document decisions and blockers
   - Record learnings as they emerge

## Creating a Learning Document

After completing work or gaining insights:

1. **Copy the template**:
   ```bash
   cp docs/templates/learning-template.md docs/learnings/YYYY-MM-DD-topic-name.md
   ```

2. **Document your learning**:
   - Provide context about where it came from
   - Clearly state what was learned
   - Explain how it can be applied
   - List best practices and pitfalls

## Tips for Effective Documentation

### Do:
- ✅ Write as you go, not after the fact
- ✅ Be specific and concrete
- ✅ Include examples where helpful
- ✅ Reference related documents and issues
- ✅ Update status as work progresses

### Don't:
- ❌ Wait until the end to document
- ❌ Write generic or vague descriptions
- ❌ Forget to update progress
- ❌ Skip documenting decisions and trade-offs

## Working with GitHub Copilot

When asking GitHub Copilot to help plan or implement features:

1. **Start with planning**: Ask Copilot to help create a plan document
2. **Reference existing docs**: Point Copilot to relevant plan or learning documents for context
3. **Document as you go**: Have Copilot update the plan document with progress
4. **Capture learnings**: After completion, ask Copilot to help document key learnings

## Example Workflow

Here's a typical workflow:

```bash
# 1. Create a new plan document
cp docs/templates/plan-template.md docs/plans/2025-12-03-new-feature.md

# 2. Edit and fill in the plan
# (Open in your editor and complete the sections)

# 3. Work on the feature, updating the plan as you go

# 4. After completion, create a learning document
cp docs/templates/learning-template.md docs/learnings/2025-12-03-new-feature-insights.md

# 5. Document key learnings from the work

# 6. Commit everything to the repository
git add docs/
git commit -m "Add documentation for new feature"
git push
```

## Benefits

By using this system consistently, you'll:

- 🎯 Have clear direction and plans
- 📝 Maintain institutional knowledge
- 🔄 Enable easier handoffs and continuity
- 🚀 Speed up future work with documented learnings
- 💡 Help others (and future you) understand decisions

## Questions?

See the [main docs README](README.md) for more information about the documentation system structure and purpose.
