**Versioning:** Number syntax: Major.Minor.Build.Revision (x.x.x.x).  
The major and minor number follows the Dynamo version, e.g. Orchid 3.0.x.x is usable in Dynamo 3.0.x.x versions. The build number is internal major builds. The revision number is an internal build number without public documentation and display in this file.  
  
  
### History of Orchid for Dynamo 3.0.x -- 3.3.x (Revit 2025)  
  
3.3.1
- Folder/Class for generic or common functions covering Revit is created. This involves all Geometry nodes, some Annotation nodes, and Common nodes. Please verify which in the package.
  
3.3.0  
- Geometry nodes renamed with prefix “Oc” To “Revit” and geometry nodes without prefix does now have the prefix “Dynamo”. This indicates if a node covers geometry that uses either the Revit.API or the Dynamo.API.  
- Geometry nodes in general are expanded with many new functions.  
- Creation of ProjectParameter has been marked obsolete/deprecated. This is also the case with the comparative Dynamo node!  
- License for the Orchid Solution has been changed/updated. It is now based on CC BY-ND, however, with geographical and behavioral limitations.  
  
3.2.1  
- The “condense” option is removed from several nodes. A specific list.condense function is added.  
- SystemTree (MEP) functions have been extended and include also xml/json export options.  
- MEP system functions have a specific color (purple) to indicate the namespace of the nodes.  
  
3.2.0  
- 1st version of Orchid for the Dynamo 3.2.x series.  
  
3.0.1  
- Function for validating if the IFC exporter is validly implemented.  

3.0.0  
- 1st version of Orchid for the Dynamo 3.0.x series.  
  

### History of Orchid for Dynamo 2.17.x -- 2.19.x (Revit 2024)  
  
2.19.5
- Folder/Class for generic or common functions covering Revit is created. This involves all Geometry nodes, some Annotation nodes, and Common nodes. Please verify which in the package.
  
2.19.4  
- Geometry nodes renamed with prefix “Oc” To “Revit” and geometry nodes without prefix does now have the prefix “Dynamo”. This indicates if a node covers geometry that uses either the Revit.API or the Dynamo.API.  
- Geometry nodes in general are expanded with many new functions.  
- Creation of ProjectParameter has been marked obsolete/deprecated. This is also the case with the comparative Dynamo node!  
- License for the Orchid Solution has been changed/updated. It is now based on CC BY-ND, however, with geographical and behavioral limitations.  
  
2.19.3  
- The “condense” option is removed from several nodes. A specific list.condense function is added.  
- SystemTree (MEP) functions have been extended and include also xml/json export options.  
- MEP system functions have a specific color (purple) to indicate the namespace of the nodes.  
  
2.19.2  
- Function for validating if the IFC exporter is validly implemented.  
  
2.19.1  
- Refactoring nodes/functions for adaptation naming convention (uniform access principle) to get rid of “get” as prefix. At the time of writing, it is not possible to get rid of “set” as a prefix, as Dynamo handles methods with multiple signatures poorly.  
  
2.19.0
- 1st version of Orchid for the Dynamo 2.19.x series.  
  
2.18.1  
- Orchid versioning adjusted so major and minor number follows the Dynamo major and minor number. The build number follows internal Orchid major builds.  
  
218.0.0  
- 1st version of Orchid for the Dynamo 2.18.x series.  
  
217.0.0  
- 1st version of Orchid for the Dynamo 2.17.x series.  
  
  
### History of Orchid for Dynamo 2.13.x -- 2.16.x (Revit 2023)  
  
2.16.9
- Folder/Class for generic or common functions covering Revit is created. This involves all Geometry nodes, some Annotation nodes, and Common nodes. Please verify which in the package.
  
2.16.8  
- Geometry nodes renamed with prefix “Oc” To “Revit” and geometry nodes without prefix does now have the prefix “Dynamo”. This indicates if a node covers geometry that uses either the Revit.API or the Dynamo.API.  
- Geometry nodes in general are expanded with many new functions.  
- Creation of ProjectParameter has been marked obsolete/deprecated. This is also the case with the comparative Dynamo node!  
- License for the Orchid Solution has been changed/updated. It is now based on CC BY-ND, however, with geographical and behavioral limitations.  
  
2.16.7  
- The “condense” option is removed from several nodes. A specific list.condense function is added.  
- SystemTree (MEP) functions have been extended and include also xml/json export options.  
- MEP system functions have a specific color (purple) to indicate the namespace of the nodes.  
  
2.16.6  
- Function for validating if the IFC exporter is validly implemented.  
  
2.16.5  
- Refactoring nodes/functions for adaptation naming convention (uniform access principle) to get rid of “get” as prefix. At the time of writing, it is not possible to get rid of “set” as a prefix, as Dynamo handles methods with multiple signatures poorly.  
  
2.16.4  
- Orchid versioning adjusted so major and minor number follows the Dynamo major and minor number. The build number follows internal Orchid major builds.  
 
216.3.0  
- Refactored layout.  
- Nodes where the internal function can return an enumeration, is being refactored to do so.  
- Nodes where enumerations values is replacing string values is updated to do so.  
  
216.2.1  
- Addition of guidance and helping files (/doc) for every node/function.  
- Categories (Category, SubCategory) refactored to independent branch.  
- Methods named “All” renamed to “InDocument” where applicable.  
  
216.2.0  
- 1st version of Orchid for the Dynamo 2.16.x series.  
  
213.2.0  
- The Dynamo transactions are being overwritten to give users more information about the transaction.  
- Shared parameters nodes for CCS and BIM7AA classification systems have been deprecated due to decisions taken by the stakeholders of the classification.  
  
213.1.0  
- Orchid types like Document, FamilyDocument, Parameter, and FamilyParameter are deprecated and converted into the alike Dynamo types. Remaining types will follow if possible.  
  
213.0.1  
- Nodes for Materials refactored and updated, do now support all kinds of schemas for appearances.  
  
213.0.0  
- 1st version of Orchid for the Dynamo 2.13.x series.  
  
  
### History of Orchid for Dynamo 2.10.x -- 2.12.x (Revit 2022)  
  
2.12.10
- Folder/Class for generic or common functions covering Revit is created. This involves all Geometry nodes, some Annotation nodes, and Common nodes. Please verify which in the package.
  
2.12.9  
- Geometry nodes renamed with prefix “Oc” To “Revit” and geometry nodes without prefix does now have the prefix “Dynamo”. This indicates if a node covers geometry that uses either the Revit.API or the Dynamo.API.  
- Geometry nodes in general are expanded with many new functions.  
- Creation of ProjectParameter has been marked obsolete/deprecated. This is also the case with the comparative Dynamo node!  
- License for the Orchid Solution has been changed/updated. It is now based on CC BY-ND, however, with geographical and behavioral limitations.  
  
2.12.8  
- The “condense” option is removed from several nodes. A specific list.condense function is added.  
- SystemTree (MEP) functions have been extended and include also xml/json export options.  
- MEP system functions have a specific color (purple) to indicate the namespace of the nodes.  
  
2.12.7  
- Function for validating if the IFC exporter is validly implemented.  
  
2.12.6  
- Refactoring nodes/functions for adaptation naming convention (uniform access principle) to get rid of “get” as prefix. At the time of writing, it is not possible to get rid of “set” as a prefix, as Dynamo handles methods with multiple signatures poorly.  
  
2.12.5
- Orchid versioning adjusted so major and minor number follows the Dynamo major and minor number. The build number follows internal Orchid major builds.  
  
212.4.0  
- Refactored layout.  
- Nodes where the internal function can return an enumeration, is being refactored to do so.  
- Nodes where enumerations values is replacing string values is updated to do so.  
  
212.3.1  
- Addition of guidance and helping files (/doc) for every node/function.  
- Categories (Category, SubCategory) refactored to independent branch.  
- Methods named “All” renamed to “InDocument” where applicable.  
  
212.3.0  
- The Dynamo transactions are being overwritten to give users more information about the transaction.  
- Shared parameters nodes for CCS and BIM7AA classification systems have been deprecated due to decisions taken by the stakeholders of the classification.  
  
212.2.0  
- Orchid types like Document, FamilyDocument, Parameter, and FamilyParameter are deprecated and converted into the alike Dynamo types. Remaining types will follow if possible.  
  
212.1.1  
- Nodes for Materials refactored and updated, do now support all kinds of schemas for appearances.  
  
212.1.0  
- 1st version of Orchid for the Dynamo 2.12.x series.  
  
210.1.0  
- Nodes for (MEP) System is extended with many functions.  
- Nodes for Reference and Assembly is added.  
- A wide range of Geometry functions (Nodes) is added.  
  
210.0.0  
- 1st version of Orchid for the Dynamo 2.10.x series.  
  
  
### History of Orchid for Dynamo 2.5.x -- 2.6.x (Revit 2021)  
  
2.6.12
- Folder/Class for generic or common functions covering Revit is created. This involves all Geometry nodes, some Annotation nodes, and Common nodes. Please verify which in the package.
  
2.6.11  
- Geometry nodes renamed with prefix “Oc” To “Revit” and geometry nodes without prefix does now have the prefix “Dynamo”. This indicates if a node covers geometry that uses either the Revit.API or the Dynamo.API.  
- Geometry nodes in general are expanded with many new functions.  
- Creation of ProjectParameter has been marked obsolete/deprecated. This is also the case with the comparative Dynamo node!  
- License for the Orchid Solution has been changed/updated. It is now based on CC BY-ND, however, with geographical and behavioral limitations.  
  
2.6.10  
- The “condense” option is removed from several nodes. A specific list.condense function is added.  
- SystemTree (MEP) functions have been extended and include also xml/json export options.  
- MEP system functions have a specific color (purple) to indicate the namespace of the nodes.  
  
2.6.9  
- Function for validating if the IFC exporter is validly implemented.  
  
2.6.8  
- Refactoring nodes/functions for adaptation naming convention (uniform access principle) to get rid of “get” as prefix. At the time of writing, it is not possible to get rid of “set” as a prefix, as Dynamo handles methods with multiple signatures poorly.  
  
2.6.7  
- Orchid versioning adjusted so major and minor number follows the Dynamo major and minor number. The build number follows internal Orchid major builds.  
  
206.6.0  
- Refactored layout.  
- Nodes where the internal function can return an enumeration, is being refactored to do so.  
- Nodes where enumerations values is replacing string values is updated to do so.  
  
206.5.1  
- Addition of guidance and helping files (/doc) for every node/function.  
- Categories (Category, SubCategory) refactored to independent branch.  
- Methods named “All” renamed to “InDocument” where applicable.  
  
206.5.0  
- The Dynamo transactions are being overwritten to give users more information about the transaction.  
- Shared parameters nodes for CCS and BIM7AA classification systems have been deprecated due to decisions taken by the stakeholders of the classification.  
  
206.4.0  
- Orchid types like Document, FamilyDocument, Parameter, and FamilyParameter are deprecated and converted into the alike Dynamo types. Remaining types will follow if possible.  
  
206.3.1  
- Nodes for Materials refactored and updated, do now support all kinds of schemas for appearances.  
  
206.3.0  
- Nodes for (MEP) System is extended with many functions.  
- Nodes for Reference and Assembly is added.  
- A wide range of Geometry functions (Nodes) is added.  
    
206.2.0  
- Version number changed from 260 to 206 to support two-digit Dynamo minor versioning. By this the Dynamo build number has been deprecated in the version number. Before 260 = 2.6.0, now 206 = 2.6.x.  
  
260.1.0  
- Support for external applications is moved to independent assemblies, this includes support for IfxExport.  
  
260.0.3  
- 1st version of Orchid for the Dynamo 2.6.x series.  
  
250.0.2  
- Filters, Schedules, and parameter Definitions (project and family parameters) added.  
  
250.0.1  
- Refactoring of Core nodes, nodes are moved into Common. Several other functions are also refactored into other namespaces.  
  
250.0.0  
- 1st version of Orchid for the Dynamo 2.5.x series.  
