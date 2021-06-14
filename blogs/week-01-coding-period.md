## Coding Period- Week 1 

The approach of the automation system was discussed with the mentors and was formed by combining the two proposals (Ritik & mine).

We would be using YML files that would be the main source of input information. The processing of the required files would be done in a tree-like structure with a hierarchy involving working groups, focus areas, and metrics. Thanks to Georg for suggesting these ideas!

The YML files render data in the form of a dictionary when interpreted through Python. This gives us a key-value pair that can be used as raw input and forms the base of the automation system. 

Using this information we can determine the files that need to be included/excluded from the final report. I explored this structure and tried to divide the project into mini-tasks and used YML information to perform them. These tasks include the management of metrics, images, focus area tables. Ritik had already done some great work on this so it was easy to understand.

Since the implementation requires us to collaborate, I explored through Ritik's approach and gain an understanding of it. I was successfully able to replicate the required results. 

I am mainly focussing on the translated metrics hence I decided to run some tests. There was an issue with Chinese translations since the writing characters are different. More details - [chaoss-workspace/issues/2](https://github.com/yash2002109/chaoss-workspace/issues/2)

We plan to use [Pandoc](https://pandoc.org/) for converting markdowns to PDF. I noticed that the tables do not wrap. The text overflows out from the page. I found a workaround for this was to specify the column width of tables in LaTeX. 

```latex
\begin{tabular}{|p{0.35\linewidth} | p{0.6\linewidth}|}
```

This will require further investigation and feedback from the mentors.
