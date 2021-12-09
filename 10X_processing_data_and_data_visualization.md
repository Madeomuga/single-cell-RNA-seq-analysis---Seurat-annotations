
## Uploading the data and specifying the assay type


```{r}
load("C:/Directory path/seurat_object.Robj")
stress.conditions<-All_cells_ID
DefaultAssay(stress.conditions)<-"integrated"
```
