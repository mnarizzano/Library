
### User Requirements Specification Document


**VERSION : 2.0**

**Authors**  
Massimo Narizzano


**REVISION HISTORY**

| Version    | Date        | Authors      | Notes        |
| ----------- | ----------- | ----------- | ----------- |
| 1.0 | 27/06/2024 | Massimo Narizzano| Creazione Struttura |
# Table of Contents

1. [Introduction](#p1)
	1. [Document Scope](#sp1.1)
	2. [Definitios and Acronym](#sp1.2) 
	3. [References](#sp1.3)
2. [System Description](#p2)
	1. [Context and Motivation](#sp2.1)
	2. [Project Objectives](#sp2.2)
3. [Requirement](#p3)
 	1. [Stakeholders](#sp3.1)
 	2. [Functional Requirements](#sp3.2)
 	
  
  

<a name="p1"></a>

## 1. Introduction

<a name="sp1.1"></a>

### 1.1 Document Scope


<a name="sp1.2"></a>

### 1.2 Definitios and Acronym


| Acronym				| Definition | 
| ------------------------------------- | ----------- | 
| ISBN                                  | International Standard Book Number|

<a name="sp1.3"></a>

### 1.3 References 

<a name="p2"></a>

1. ISBN : https://www.isbn.it/

## 2. System Description
<a name="sp2.15"></a>

### 2.1 Context and Motivation

<a name="sp2.2"></a>

Si PRogetti un software per la gestione privata dei libri. 
### 2.2 Project Obectives 

Il sistema dovrà permettere ad un utente di memorizzare informazioni su dei libri (titolo autore anno e ISBN). Deve inoltre permettere di recuperare informazioni su un libro e aggiungere togliere libri dalla libreria.

<a name="p3"></a>

## 3. Requirements

| Priorità | Significato | 
| --------------- | ----------- | 
| M | **Mandatory:**   |
| D | **Desiderable:** |
| O | **Optional:**    |
| E | **future Enhancement:** |

<a name="sp3.1"></a>
### 3.1 Stakeholders

Utente Generico : ha come obiettivo quello di memorizzare tutti i libri che vuole in un unico posto

<a name="sp3.2"></a>
### 3.2 Functional Requirements 
Di seguito possiamo vedere una descrizione delle principali funzionalità

![Use Case Diagrams](imgs/usecase.png)

<a name="sp3.2.1"></a>
#### 3.2.1 Prelievo 

<b>Nome</b> Prelievo

<b>Precondizioni</b> Essere in possesso di una tessera Bancomat


<b>Priorità</b> Mandatory

<b>Stakeholder Principale</b> Cliente

<b>Scenario Principale</b> 

	1. Cliente inserisce tessera bancomat
	2. Cliente inserisce pin corretto
	3. Il cliente seleziona la quantità da prelevare
	4. ATM eroga le banconote la tessera e la ricevuta
	5. Il cliente ritira le banconote, la tessera e la ricevuta
	6. ATM puslisce lo schermo

<b>Scenario Alternativo</b> 
	2A - Il Cliente inserisce il PIN non corretto per la terza volta
 
 	1. ATM Notifica che il PIN è errato 
 	2. L'ATM notifica che non restituisce la tessera
 	3. L'ATM va al punto 6 dello scenario principale.
    
<b>Scenario Alternativo</b>
2B - Il Cliente inserisce il PIN non corretto per un numero di volte minore di 3
 
 	1. ATM Notifica che il PIN è errato e invita il cliente a digitarlo di nuovo 
 	2. L'ATM incrementa il contatore dei fallimenti
 	3. L'ATM va al punto 2 dello scenario principale.

<b>Post-Condizioni</b>

La cifra richiesta viene prelevata dal conto corrente aggiornando il saldo



<a name="sp3.2.2"></a>
#### 3.2.2 Deposito 

<b>Nome</b>

<b>Precondizioni</b>

<b>Priorità</b>

<b>Stakeholder Principale</b>

<b>Scenario Principale</b>

<b>Scenario Alternativo</b>

<b>Scenario Alternativo</b>

<b>Post-Condizioni</b>

<a name="sp3.2.3"></a>
#### 3.2.3 Trasferimento

<b>Nome</b>

<b>Precondizioni</b>

<b>Priorità</b>

<b>Stakeholder Principale</b>

<b>Scenario Principale</b>

<b>Scenario Alternativo</b>

<b>Scenario Alternativo</b>

<b>Post-Condizioni</b>

<a name="sp3.2.4"></a>
#### 3.2.4 Saldo
<b>Nome</b>

<b>Precondizioni</b>

<b>Priorità</b>

<b>Stakeholder Principale</b>

<b>Scenario Principale</b>

<b>Scenario Alternativo</b>

<b>Scenario Alternativo</b>

<b>Post-Condizioni</b>


<a name="sp3.2.5"></a>
#### 3.2.5 Accensione

<b>Nome</b>

<b>Precondizioni</b>

<b>Priorità</b>

<b>Stakeholder Principale</b>

<b>Scenario Principale</b>

<b>Scenario Alternativo</b>

<b>Scenario Alternativo</b>

<b>Post-Condizioni</b>

<a name="sp3.2.6"></a>
#### 3.2.6 Spegnimento

<b>Nome</b>

<b>Precondizioni</b>

<b>Priorità</b>

<b>Stakeholder Principale</b>

<b>Scenario Principale</b>

<b>Scenario Alternativo</b>

<b>Scenario Alternativo</b>

<b>Post-Condizioni</b>





