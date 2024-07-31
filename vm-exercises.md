# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-row-aggregator-initial.knwf'
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-row-aggregator-sol.knwf'

#### Learning Objective

*By the end of this exercise, students will be able to use the Row Aggregator node in KNIME to summarize sales data effectively.*

#### Context

*Aggregating data is a fundamental task in data analysis, allowing businesses to gain insights into their performance and make informed decisions. By using the Row Aggregator node in KNIME, you can easily aggregate data based on specific criteria, such as averaging  sales for different regions. This skill is essential for data professionals who need to present concise and accurate information to stakeholders, enabling strategic decision-making and identifying trends or anomalies in the data.*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Open the provided KNIME file: Locate and open the 'ex-1-row-aggregator-initial.knwf' file
- Execute upstream nodes: Right-click on the *String to Date&Time Node* and execute it so the traffic lights turn green.
- Add the Row Aggregator Node: Go to the Node Repository and search for the Row Aggregator Node. With the String to Date&Time Node still selected, double-click the Row Aggregator Node to add it to the workflow and connect it to the upstream nodes.
- Open Row Aggregator Node Configuration: Double-click the Row Aggregator Node (or press F6 on your keyboard).
- Configure the Row Aggregator Node: For the Category column select *Region*, as Aggregation choose *Average* and in the *Includes* box keep only the purchase_amount column. Leave everything else as default.
- Execute the Row Aggregator Node: Click *OK*. With the Row Aggregator Node still selected press F7 to execute the node and perform the aggregation.

#### Exercise question:
*What is the average purchase_amount for the APAC region?*
- 5,624.980
- 4,869.192 (correct answer)
- 4,496.438

#### End goal:

*Add an image of the final visualization here.*

## 2nd VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

*One measurable learning objective that this exercise assesses*

#### Context

*3 - 4 sentence description of why it’s important to learn how to do this task (linking back to the learning objective). Explain how this would be used in a real-life situation. Why is it useful, what problem does it solve?*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Step 1
- Step 2
- Step 3
- ...

#### Exercise question:
*This is a question presented to learners to check if the steps above were properly completed. It can be a multiple choice question or a question with a 1-3 word answer. It is often not possible to check if all the steps are completed, in this case; the priority is to check that the learner meets the learning objective.*

#### End goal:

*Add an image of the final visualization here.*

