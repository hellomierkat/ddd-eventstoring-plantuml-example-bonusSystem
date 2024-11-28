# ResourceClass


```text
c4k8s/Element/ResourceClass
```

```text
include('c4k8s/Element/ResourceClass')
```



| ResourceClass |
| :---: |
| ![illustration for ResourceClass](../../c4k8s/Element/ResourceClass.Local.png) |




## ResourceClass

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('c4k8s/bootstrap')

' loads the Item which embeds the element ResourceClass
include('c4k8s/Element/ResourceClass')

' load the c4model package
include('c4model/bootstrap')
ResourceClass('ResourceClass', 'Resource Class', 'an optional description label')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('c4k8s/bootstrap')

' loads the Item which embeds the element ResourceClass
include('c4k8s/Element/ResourceClass')

' load the c4model package
include('c4model/bootstrap')
ResourceClass('ResourceClass', 'Resource Class', 'an optional description label')
@enduml
```
