# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "projectName" : "golang-accelerator",
  "deploymentType" : "workload",
  "giturl" : "https://github.com/TanzuDK/golang-accelerator.git",
  "gitbranch" : "main",
  "minscale" : "1",
  "bsGitRepository" : "github.com?owner=coyte&repo=golang-accelerator"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(YTT, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (YTT)
┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"deploymentType":"workload","gitbranch":"main","bsGitBranch":"main","artifactVersion":"0.0.1-beta","bsGitRepository":"github.com?owner=coyte&repo=golang-accelerator","artifactId":"golang-accelerator","projectName":"golang-accelerator","giturl":"https://github.com/TanzuDK/golang-accelerator.git","minscale":"1"}
┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input412754437609404586, --data-values-file, /tmp/accelerator-options4853790118726976521.json, --output-files, /tmp/ytt-output4962511816521415289]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Dockerfile matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug toto.txt didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug values.yml didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug app/main.go matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug docs/index.md matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┃ ┃ Debug docs/links.md matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┃ ┃ Debug images/golang.png didn't match [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .github/workflows/techdocs.yml matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┃ ┃ Debug app/html/index.html matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┃ ┃ Debug app/html/style.css matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┗ ┗ Debug app/html/tap-into-prod.png matched [**/*.md, app/**, docs/**, procfile, Dockerfile, .github/workflows/*] -> included
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┃ ┗ ┗ ┗ Debug Multiple representations for path '.github/workflows/techdocs.yml', will use the one appearing last 
┗ ╺ engine.transformations[1] (UniquePath)
```
