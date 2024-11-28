# Upgrade


```text
material-4/Action/Upgrade
```

```text
include('material-4/Action/Upgrade')
```



| Illustration | Upgrade |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/Upgrade.png) | ![illustration for Upgrade](../../material-4/Action/Upgrade.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$UpgradeXs>`
- `<$UpgradeSm>`
- `<$UpgradeMd>`
- `<$UpgradeLg>`





## Upgrade

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Upgrade
include('material-4/Action/Upgrade')

' renders the element
Upgrade('Upgrade', 'Upgrade', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element Upgrade
include('material-4/Action/Upgrade')

' renders the element
Upgrade('Upgrade', 'Upgrade', 'an optional tech label', 'an optional description')
@enduml
```
