# Refactor audit

Generated 2026-10-25 18:37 UTC.

## Headline

**Code quality score 91.0%.** **0 of 274 source files are over the 100-line limit (0.0%)**; the worst file is 0 lines.

## Code quality score

| Element | Reading | Score | Weight | 0% at |
| --- | --- | --- | --- | --- |
| **Standard baseline checks** | | **95.6%** | **52** | |
| Files over the line limit | 0 in 274 files | 100.0% | 10 | 50% of files |
| Worst file, in limits over | 0 | 100.0% | 5 | 9 |
| Functions over the line limit | 0 in 305 functions | 100.0% | 8 | 25% of functions |
| Else blocks | 1 in 404 branches | 99.5% | 5 | 50% of branches |
| Duplication % | not measured | not measured | — | 20 |
| Explanatory comment lines | 25 in 8.62 thousand lines | 94.2% | 4 | 50 per thousand lines |
| Inline magic values | 5 in 8.62 thousand lines | 97.1% | 4 | 20 per thousand lines |
| Orphan components and functions | 0 in 361 components and functions | 100.0% | 4 | 10% of components and functions |
| Long member chain lines | 103 in 8.62 thousand lines | 60.2% | 4 | 30 per thousand lines |
| Deeply indented lines | 21 in 8.62 thousand lines | 91.9% | 4 | 30 per thousand lines |
| Overlong function names | 0 in 305 functions | 100.0% | 4 | 10% of functions |
| **Design pattern file count** | | **100.0%** | **10** | |
| Files the patterns predict but are missing | 0 in 31 predicted files | 100.0% | 10 | 50% of predicted files |
| Entities outside their expected file count | not measured | not measured | — | 50% of entities |
| **Prose** | | **82.1%** | **20** | |
| Conditions with calls tangled inside calls | 19 in 404 branches | 81.2% | 8 | 25% of branches |
| Conditions compared to a raw literal | 25 in 404 branches | 75.2% | 6 | 25% of branches |
| Accessor names that want to be a property | 3 in 305 functions | 90.2% | 6 | 10% of functions |
| **Widget adoption** | | **not measured** | **0** | |
| Markup written by hand where a widget should be | not measured | not measured | — | 50% of widget slots |
| **Input validation** | | **72.4%** | **8** | |
| Doors that write without checking their input against the columns | 4 in 29 write doors | 72.4% | 8 | 50% of write doors |

Each element scores 100% with no offenders and falls in a straight line to 0% when its offenders, measured against the size of the codebase, reach the figure in the last column. The score is the weighted average of the elements that could be measured; an element that could not be measured lends its weight to the rest. Weights and zero points are set in `tools/refactor/rules.json` under `score.elements`. The offenders behind every reading are in `tools/refactor/audit-output/audit.json`.

## The repository by area

| Area | Files | Of which audited source | Source lines |
| --- | --- | --- | --- |
| tooling | 101 | 0 | 0 |
| backend | 92 | 92 | 2,914 |
| frontend | 85 | 81 | 2,558 |
| shared | 59 | 58 | 1,382 |
| api | 34 | 34 | 1,339 |
| tests | 23 | 9 | 425 |
| docs | 22 | 0 | 0 |
| infrastructure | 12 | 0 | 0 |
| database | 4 | 0 | 0 |
| **whole repository** | **432** | **274** | **8,618** |

## Summary

| Check | Key figures |
| --- | --- |
| fileLength | limit: 100, filesOverLimit: 0, totalFiles: 274, totalLines: 8618, worstFileLines: 0, worstFileTimesOverLimit: 0.0 |
| functionShape | limit: 30, functionsOverLimit: 0, totalFunctions: 305, elseBlocks: 1, ifBlocks: 404, measurementIsHeuristic: True |
| functionNames | overlongFunctionNames: 0, maxWords: 5, maxLength: 40 |
| accessorNames | gluedAccessorNames: 3, measurementIsHeuristic: True |
| duplication | skipped: jscpd is not installed (npm install -g jscpd) |
| naming | bannedAbbreviationHits: 0, unprefixedBooleans: 1 |
| comments | explanatoryCommentLines: 25, filesWithComments: 9, taskMarkers: 0 |
| magicValues | inlineHexColours: 4, inlineStyleAttributes: 1, repeatedStringLiterals: 0 |
| prose | longMemberChainLines: 103, deeplyIndentedLines: 21, overlongLines: 60, measurementIsHeuristic: True |
| conditions | tangledConditionLines: 19, literalComparisonLines: 25, measurementIsHeuristic: True |
| orphans | orphanFunctions: 0, functionsExamined: 305 |
| designPatterns | roleFamilies: 14, predictedFiles: 31, predictedFilesMissing: 0, entities: 0, entitiesOutOfRange: 0, measurementIsHeuristic: True |
| inventory | pages: 17, components: 56, orphanComponents: 0, averagePageLines: 33 |
| siteDefinition | skipped: no siteDefinition catalogue in rules.json |
| inputValidation | schemaTables: 14, limitedColumns: 0, writeDoors: 29, unvalidatedDoors: 4, looserLimits: 0 |
| fileAreas | totalFiles: 432, tooling: 101, backend: 92, frontend: 85, shared: 59, api: 34, tests: 23, docs: 22, infrastructure: 12, database: 4 |

## Against the baseline

| Ratcheted figure | Baseline | Now | Verdict |
| --- | --- | --- | --- |
| code quality score | 91.0% | 91.0% | — |
| fileLength.filesOverLimit | 0 | 0 | held |
| fileLength.worstFileLines | 0 | 0 | held |
| functionShape.functionsOverLimit | 0 | 0 | held |
| functionShape.elseBlocks | 1 | 1 | held |
| duplication.duplicatedPercentage | None | None | — |
| comments.explanatoryCommentLines | 25 | 25 | held |
| magicValues.inlineHexColours | 4 | 4 | held |
| inventory.orphanComponents | 0 | 0 | held |
| orphans.orphanFunctions | 0 | 0 | held |
| prose.longMemberChainLines | 103 | 103 | held |
| prose.deeplyIndentedLines | 21 | 21 | held |
| functionNames.overlongFunctionNames | 0 | 0 | held |
| accessorNames.gluedAccessorNames | 3 | 3 | held |
| conditions.tangledConditionLines | 19 | 19 | held |
| conditions.literalComparisonLines | 25 | 25 | held |
| designPatterns.predictedFilesMissing | 0 | 0 | held |
| siteDefinition.handRolledElements | None | None | — |
| siteDefinition.boxedContentWidgets | None | None | — |
| inputValidation.unvalidatedDoors | 4 | 4 | held |
| inputValidation.looserLimits | 0 | 0 | held |

## Worst files by length

All files are within the limit.

Full detail, including every offender list, is in `audit.json`.
