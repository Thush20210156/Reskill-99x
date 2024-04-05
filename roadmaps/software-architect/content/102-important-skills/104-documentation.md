# Documentation

Architectural documentation is sometimes more and sometimes less important. Important documents are for example architectural decisions or code guidelines. Initial documentation is often required before coding starts and need to be refined continuously. Other documentation can be automatically generated as code can also be documentation, e.g. UML class diagrams.

- **Clean Code**: Code is the best documentation if done right. A good architect should be capable to distinguish between good and bad code. A really great resource to learn more about good and bad code is the book “Clean Code” by Robert C. Martin.
- **Generate documentation where possible**: Systems are changing quickly and it is hard to update the documentation. Whether it is about APIs or system landscapes in form of CMDBs (Configuration management database): The underlying information often changes too fast to keep the corresponding documentation up to date by hand. Example: For APIs you could auto generate documentation based on the definition file if you are model driven, or directly from the source code. A lot of tools exist for that, I think Swagger and RAML are a good starting point to learn more.
- **As much as necessary, as little as possible**: Whatever you need to document, e.g., decision papers, try to focus on only one thing at a time and include only the necessary information for this one thing. Extensive documentation is hard to read and to understand. Additional information should be stored in the appendix. Especially for decision papers it is more important to tell a convincing story instead of just throwing tons of arguments. Further, this saves you and your co-workers, who have to read it, a lot of time. Have a look at some documentation you have done in the past (source code, models, decision papers, etc.) and ask yourself the following questions: “Are all necessary information included to understand it?”, “Which information are really required and which could be omitted?” and “Does the documentation has a red line?”.
- **Learn more about architecture frameworks**: This point could be applied to all other “technical” points as well. I put it here, as frameworks like TOGAF or Zachmann are providing “tools” which feel heavy on the documentation side, although their added value is not limited to documentation. Getting certified in such a framework teaches you to tackle architecture more systematically.