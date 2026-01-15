# Planning-with-Files Workflow

A structured, file-based planning methodology for complex tasks and projects.

## Overview

The planning-with-files methodology uses three core documents to manage complex tasks:

1. **`task_plan.md`** - Initial planning and approach
2. **`findings.md`** - Research findings and analysis
3. **`progress.md`** - Ongoing progress tracking

## Why Use This Methodology?

✅ **Knowledge Retention** - Findings and decisions are documented  
✅ **Structured Approach** - Consistent format across projects  
✅ **Transparency** - Clear visibility into planning and progress  
✅ **Collaboration** - Easy to share and review  
✅ **Version Control** - Track changes over time with Git  

## Workflow

### 1. Planning Phase

Create `task_plan.md`:
- Define goals and scope
- Outline approach
- Identify risks
- Set timeline

### 2. Research Phase

Create `findings.md`:
- Document research findings
- Analyze options
- Make recommendations
- Provide evidence

### 3. Execution Phase

Create `progress.md`:
- Track completed work
- Monitor blockers
- Update timeline
- Document decisions

## File Structure

```
project/
├── task_plan.md      # Initial planning
├── findings.md        # Research findings
└── progress.md        # Progress tracking
```

## Templates

Templates are available in `templates/`:
- `task_plan.md` - Planning template
- `findings.md` - Findings template
- `progress.md` - Progress template

## Usage Examples

### Example 1: Feature Development

```
feature-x/
├── task_plan.md      # Feature requirements and approach
├── findings.md        # Technical research and options
└── progress.md        # Development progress
```

### Example 2: Integration Assessment

```
integration-assessment/
├── task_plan.md      # Assessment scope and approach
├── findings.md        # Integration findings and recommendations
└── progress.md        # Assessment progress
```

### Example 3: Bug Investigation

```
bug-investigation/
├── task_plan.md      # Investigation approach
├── findings.md        # Root cause analysis
└── progress.md        # Fix progress
```

## Best Practices

1. **Start with Planning** - Always create `task_plan.md` first
2. **Document Findings** - Capture research and analysis in `findings.md`
3. **Update Progress** - Regularly update `progress.md`
4. **Link Documents** - Reference related documents
5. **Version Control** - Commit changes regularly
6. **Review Regularly** - Update status and timeline

## Integration with Repositories

This methodology can be adopted in any repository:

1. Create a `planning/` directory (or use root)
2. Create task-specific subdirectories
3. Use templates to get started
4. Commit planning documents to version control

## Resources

- Original methodology: [planning-with-files](https://github.com/ahmad-adi/planning-with-files)
- Templates: See `templates/` directory
- Examples: See repository-specific planning directories

## License

MIT License - Free to use and adapt for your projects.
