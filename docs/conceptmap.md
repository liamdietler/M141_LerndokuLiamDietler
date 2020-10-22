# Conceptmap

```plantuml
@startuml conceptmap
<<<<<<< HEAD
left to right direction

(Scripting-Sprachen) as (ScriptSprachen)
(PHP)
note bottom of (PHP)
=======

(Scripting-Sprachen) as (ScriptSprachen)
(PHP)
note right of (PHP)
>>>>>>> 473ae40d51d8ad5f51a91dad88b46a1f8d80e5ba
    PHP steht für "Personal Home Page Tools" oder "Hypertext Preprocessor", dies ist eine Skriptsprache die speziell für die Webprogrammierung geeignet ist da sie in HTML eingebettet werden kann.
endnote
(Docker-Compose)
(YAML)
<<<<<<< HEAD
note bottom of (YAML)
=======
note right of (YAML)
>>>>>>> 473ae40d51d8ad5f51a91dad88b46a1f8d80e5ba
    YAML steht für "YAML Ain't Markup Language" und ist eine Markup Sprache die einfacher zu verstehen ist als beispielsweise XML.
endnote
(ScriptSprachen) ---> (YAML)
(ScriptSprachen) ---> (PHP)
(Webapplikation) as (Web)
(SSR)
(CSR)
(Web) <--- (PHP)
(PHP) ---> (CSR)
(PHP) ---> (SSR)
(CSR) <---> (SSR)
<<<<<<< HEAD
note bottom of (CSR)
    CSR steht für Client Side Rendering,  womit gemeint ist dass der Host einen beispielsweise HTML-Request macht an einen Server und dieser ein HTML-File ohne weiteres sendet.
endnote
note bottom of (SSR)
=======
note right of (CSR)
    CSR steht für Client Side Rendering,  womit gemeint ist dass der Host einen beispielsweise HTML-Request macht an einen Server und dieser ein HTML-File ohne weiteres sendet.
endnote
note right of (SSR)
>>>>>>> 473ae40d51d8ad5f51a91dad88b46a1f8d80e5ba
    SSR steht für Server Side Rendering, wenn eine Website vorgerendert wird auf dem Server bezeichnet man dies als SSR. Der Server stellt eine statische HTML-Version der URL und des Clients bereit.
endnote
(Docker-Compose)
note left of (Docker-Compose)
    Docker-Compose ist ein Tool zum definieren und ausführen von mehreren Container.
endnote
(ScriptSprachen) <---> (Python)
(ScriptSprachen) <---> (Bash)

@enduml
```
