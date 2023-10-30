[![xc compatible](https://xcfile.dev/badge.svg)](https://xcfile.dev)

# template-A3-process-problem-solving

A markdown ePub template to help around "A3 Process and Problem Solving"

## Tasks

### epub
Build the epub version of the A3.

```shell
pandoc --toc\
    --metadata title="A3 LEAN Tool"\
    title.yml\
    01_background.md\
    02_current_conditions.md\
    03_target_conditions.md\
    04_analysis.md\
    05_proposed_countermeasures_implementation_verification_plan.md\
    06_follow_up_plan.md\
    07_result_checks.md\
    08_standardization_and_next_steps.md\
    -o A3_Lean_Tool.epub
```

