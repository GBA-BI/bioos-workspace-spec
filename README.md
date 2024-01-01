# Bio-OS Workspace Specification
Bio-OS, short for Bio-medical Big Data Operating System, is an open-source framework to rapidly construct bioinformatics analysis platforms on various infrastructures like local, HPC and cloud resources. Workspace is the basic data structure in Bio-OS which encapsulates all related elements for a research project, including data, programs and tools in secondary and tertiary analysis procedures with their environments, analysis logs, and the dashborad to describe the research project. It is designed as a self-descriptive object to deposit, disseminate, publish and reproduce the research project work. Both Workspace object and its sub-objects are strictly reprocucible, compatible with multiple widely used formats. People can use the entire Workspace object or the sub-objects to aid there research work. 

Bio-OS workspace spec is licensed under the [MIT License](LICENSE). 

## Specifications
The current version is draft-2, you can see the human-readable [OpenAPI YAML description](versions/draft-2/spec.yaml). You can also explore the specification in the [Swagger Editor](https://editor.swagger.io/?url=https://raw.githubusercontent.com/zhou-jianwen/bioos-workspace-spec/main/versions/draft-2/spec.yaml) .

## Published Workspaces
Digger, short for Digital Gallery, is the Bio-OS Workspace warehouse maintained by Guangzhou Laboratory where you can find, download and submit Workspaces.
## Tools
The Bio-OS instance platforms like Miracle Cloud are the best integrated environment to browse, create, run, reproduce a Bio-OS Workspace. Moreover, using Bio-OS CLI and SDK, you can not only manipulate the entire Workspace object, but also the sub-objects in the selected Workspace.
## Community and Support
The recommend place to get involved is github issues in this repo, any bugs, ambiguity, or problems with this specification can be reported. Please feel free to ask questions, provide answers in the issues.
## Contributing
Bio-OS is an open-source project and advances through community contributions. We encourage all issues and PRs submitting from community.