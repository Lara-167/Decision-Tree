# Decision-Tree

# Projektname: Decision Tree

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Lara-167/Decision-Tree/tree/main/HEAD)

Projektbeschreibung: Für dieses Projekt werden öffentlich verfügbare Daten von LendingClub.com verwendet. Lending Club bringt Leute zusammen, die Geld brauchen (Leihende) und solche, die Geld investieren möchten (Geldgeber). Als Invester möchte man dann verständlicherweise vor allem an die Leute sein Geld verleihen, die es mit einer hohen Wahrscheinlichkeit zurückzahlen. Es wird ein Modell zu erstellt, dass bei dieser Vorhersage hilft.

Die Daten sind von 2007 bis 2010, bevor das Unternehmen an die Börse ging. Anhand der Daten wird vorhergesagt, ob ein Leihender das Geld zurückgezahlt hat oder nicht.

#Der Datensatz beinhaltet folgende Eigenschaften:

    credit.policy: 1 falls der Kunde die Risikobewertung besteht, 0 falls nicht.
    purpose: Der Zweck des Kreidts (Werte sind "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", und "all_other").
    int.rate: Der Zinssatz des Kreidts als Anteil (eine Rate von 11% würde 0.11 sein). Kreditnehmer, die LendingClub.com als riskanter einstuft erhalten einen höheren Zins.
    installment: Die monatliche Zeilzahlung, die der Kreditnehmer leistet, wenn der Kredit finaziert wird.
    log.annual.inc: Der natürliche Log des angegebenen jährlichen Einkommens des Kreditnehmers.
    dti: Die "debt-to-income" Rate des Kreditnehmers (Kredit geteilt durch jährliches Einkommen.
    fico: Der FICO Kreditscore des Kreditnehmers.
    days.with.cr.line: Anzahl der Tage an denen der Kunde einen Dispokredit hatte.
    revol.bal: Die Bilanz am Ende eines Kreditkartenabrechnungszeitraums.
    revol.util: Der erstattete Anteil am Gesamtkredit.
    inq.last.6mths: Die Anzahl an Anfragen, die Kreditgeber in den letzten 6 Monaten an den Kreditnehmer gestellt haben.
    delinq.2yrs: Die Anzahl der Vorkommnisse eines Verzugs von über 30 Tagen innerhalb der letzten 2 Jahre.
    pub.rec: Die Anzahl an negativen Einträgen (Bankrott, Steuerverzug, Verurteilungen,...) des Kreditnehmers.

#Code-Ausführung: 
1. GitHub URL des Repository "Logistic-Regression" in https://mybinder.org/ einfügen und launchen
Notebook öffnen
Code-Zeilen nacheinander ausführen lassen

#Future Warning ist eine Warninformation und gilt für zukünftige Versionen.

#Code-Abfolge: 
1. Libraries importieren (nachdem sie vorab durch binder installiert wurden)
2. Daten einlesen
3. Explorative Datenanalyse
4. Datenvorbereitung
5. Train Test Split
6. Ein Entscheidungsbaummodell trainieren
7. Vorhersagen und Auswertung
8. Ein Random Forest Modell trainieren
9. Vorhersage und Auswertung

#Projektergebnis: Anhand der Daten wird vorhergesagt, ob ein Leihender das Geld zurückgezahlt hat oder nicht. Die beiden Modelle haben eine Accuracy von 73% und 85%. Der Recall beider Modelle fällt bei einem Makro-Durchschnitt von 51% und 53% nicht besonders gut aus. D.h. es wurden nur knapp die Hälfte der tatsächlich positiven Fälle vom Modell korrekt erkannt, im Verhältnis zur Gesamtzahl der tatsächlichen positiven Fälle.
