

```mermaid
classDiagram
    class Sufyan["nayfusaurus.github.io"]
    Sufyan <|-- Software Engineer
    Sufyan <|-- CybersecurityResearcher
    Sufyan <|-- MobileDeveloper
    Sufyan <|-- Gamer
    Sufyan : +he/him 🦸‍♂️ 👨‍🚀 🤦‍♂️
    Sufyan : +country 🇸🇬 🇸🇬 🇸🇬 🇸🇬
    Sufyan : +moniker nayfusaurus
    Sufyan: +isAwesome()
    Sufyan: +isGamer()
    Sufyan: +lifeLongLearning()
    link Sufyan "[https://www.github.com](https://nayfusaurus.github.io/)" "Personal Website"

    class SoftwareEngineer{
      +String devops
      +nodejs()
      +django()
      +labview()
    }
    class CybersecurityResearcher{
      +bool is_learning
      +app_security()
      +mobile_security()
      +pen_testing()
    }
    class MobileDeveloper{
      +bool is_wild
      +ios()
      +android()
      +react_native()
    }
    class Gamer{
      +genre strategy
      +total_war()
      +starcraft()
      +company_of_heroes()
    }
    
```
