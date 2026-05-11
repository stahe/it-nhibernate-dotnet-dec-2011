# Introduzione al framework NHibernate per la piattaforma .NET

[Introduzione al framework NHibernate per la piattaforma .NET (2011)](https://stahe.github.io/it-nhibernate-dotnet-dec-2011/)

Questo repository accompagna un corso introduttivo su **NHibernate**, presentato come l'equivalente .NET del framework Java **Hibernate**. Il documento fornisce una panoramica concisa sull'uso di un **ORM** (*Object Relational Mapper*) nell'ecosistema .NET.

## Panoramica

Un ORM è un insieme di librerie che consente a un'applicazione basata su database di manipolare il database **senza scrivere esplicitamente query SQL** e **senza dipendere dalle specifiche del DBMS utilizzato**.

Questo materiale funge da **breve introduzione** a NHibernate. Per uno studio più approfondito, il documento raccomanda il seguente libro:

- **NHibernate in Action**
- **Autore**: Pierre-Henri Kuaté
- **Editore**: Manning
- **ISBN-13**: 978-1932394924

## Livello e prerequisiti

Su una scala **principiante / intermedio / avanzato**, questo documento si colloca al livello **intermedio**.

Per comprenderlo sono necessari diversi prerequisiti, tra cui:

1. **C# 2008**  
   *Apprendimento del linguaggio C# 3.0 con il .NET 3.5 Framework*

2. **Spring IoC per .NET**  
   Introduzione alle basi dell'**Inversione di Controllo (IoC)** e dell'**Iniezione di Dipendenza** con **Spring.NET**

Il documento include inoltre, all'inizio di alcuni paragrafi, riferimenti bibliografici consigliati a queste risorse preliminari.

## Strumenti utilizzati

Il caso di studio si avvale di strumenti disponibili gratuitamente sul web, nelle versioni elencate a partire da **dicembre 2011**:

- **NHibernate 3.2**  
- **Spring.NET 1.3.2**  
  Utilizzato qui per le librerie che facilitano l'uso di NHibernate  
- **log4net 1.2.10**  
  Framework di logging utilizzato da NHibernate  
- **NUnit 2.5**  
  Framework di test unitari, l'equivalente .NET di JUnit
- **ADO.NET Driver 6.4.4 per MySQL 5**

## Obiettivo del corso

Questo corso mira a introdurre le basi di **NHibernate** in un contesto .NET, dimostrando come semplificare l'accesso ai dati attraverso un approccio orientato agli oggetti, sfruttando al contempo strumenti complementari di configurazione, registrazione e test.

