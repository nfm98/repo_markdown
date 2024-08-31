```mermaid
classDiagram
    class Liga Argentina {
        +Rosario Central
        +Boca Juniors
        +Racing Club
    }

    class Brasileirao {
        +Palmeiras
        +Sao Paulo
        +Corinthians

    }

    class Liga MX {
        +Chihuahuas de quetzalcoatl
        +Pollitos de Bragarnik
        +Toluca
      

    class Resultados {
        +
        +1° Rosario Central
        +2° Francia
        +3° Palmeiras
        +4° Boca Juniors
        +5° Sao Paulo
        +19° Newells

    }

    Library "1" -- "contains" Book
    Library "1" -- "registers" Member
    Library "1" -- "manages" Librarian
