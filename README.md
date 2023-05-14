# Go Clean Architecture Sample
This is the sample for go clean architecture application structure.
For more details please refer to [this repository](https://github.com/VlasovArtem/go-clean-architecture).
# How to use
Clone this repository and run the following command:
```bash
git clone https://github.com/VlasovArtem/go-clean-architecture-sample.git
```
Rename the project:
```bash
mv go-clean-architecture-sample <your_project_name>
```
Clean git folder:
```bash
rm -rf .git
```
Change the import path:
```bash
go mod edit -module <your_project_name>
```
Clean .keep files:
```bash
find . -name .keep -type f -delete
```
Clean up the README.md file and start coding!