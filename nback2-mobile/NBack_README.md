# 2-Back Task (Persian)

This is a translated and technically adapted version of the **2-back working memory task**, based on the original design by **Gijsbert Stoet, PhD**, developer of [PsyToolkit](https://www.psytoolkit.org/). The task has been translated into **Persian** and optimized for both **mobile and desktop platforms**.

## Purpose

The 2-back task measures **working memory**, requiring participants to respond only when the current stimulus matches the one from two steps earlier.

## Attribution

Original experiment design and script by **Gijsbert Stoet, PhD** (PsyToolkit developer)  
**Translated and adapted into Persian by Sepehr Moraghebi** for mobile and desktop compatibility.

## Output Data Format

The output contains **12 columns** per trial. Here's what each column represents:

| Column | Description |
|--------|-------------|
| 1 | Block number |
| 2 | Trial counter |
| 3 | Score of current trial (`1` = correct, `0` = wrong) |
| 4 | Correct match response (`1` = correctly detected a 2-back match) |
| 5 | Miss (`1` = failed to respond to a match) |
| 6 | False alarm (`1` = responded to a non-match) |
| 7 | (Blank) – empty for formatting purposes |
| 8 | Reaction time in milliseconds |
| 9 | Matching trial indicator (`1` = current trial is a match) |
| 10 | Current stimulus number (1–15) |
| 11 | Stimulus on previous trial (n–1) |
| 12 | Stimulus two trials ago (n–2) |

## Notes

- The 7th column is blank and can be ignored. This spacing improves readability of reaction times.
- Accuracy is calculated based on columns 3–6.
- The task excludes the first two trials from matching logic, as required for n-back structure.

## License

This task is part of the (https://github.com/killouto/cognitive-tasks-persian-mobile-desktop) repository and licensed under the MIT License. See the [LICENSE](../LICENSE) file for more information.
