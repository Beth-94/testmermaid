![rendered image description](relative/path/to/rendered_image.png)

<details>
  <summary>diagram source</summary>
  This details block is collapsed by default when viewed in GitHub. This hides the mermaid graph definition, while the rendered image
  linked above is shown. The details tag has to follow the image tag. (newlines allowed)

```mermaid
gantt
    title Example Gantt Chart

    section Section
    Task 1           :a1, 2024-04-01, 30d
    Task 2           :after a1  , 20d
    Final Section    : 2024-05-12  , 12d


```
</details>
