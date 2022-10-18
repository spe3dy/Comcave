# Hausaufgaben 18-10-2022

Die BioScan GmbG soll eine Software zur Erkennung und Speicherung von Fingerabdruecken und Handflaechenabdruecken erstellen.
Zur Vorbereitung der Programmierung soll ein UML-Klassendiragramm erstellt werden.

a: In einem UML-Klassendiagramm koennen die folgenden Beziehungen vorkommen.
Beschreiben Sie jeweils Kurz

aa: Assoziation

Eine Assoziation beschreibt eine Beziehung zwischen zwei oder mehr Classifiern, im häufigsten Fall eine Verbindung zwischen genau zwei Klassen. Assoziationen definieren dabei eine Beziehung auf Typebene. Auf Instanzebene nennen sich die konkreten Ausprägungen einer Assoziation


ab: Vererbung

Die Vererbung ist eines der grundlegenden Konzepte der Objektorientierung und hat große Bedeutung in der Softwareentwicklung. Die Vererbung dient dazu, aufbauend auf existierenden Klassen neue zu schaffen, wobei die Beziehung zwischen ursprünglicher und neuer Klasse dauerhaft ist.

ac: Komposition

Eine Komposition in der Unified Modeling Language (UML) ist ein Sonderfall der Assoziation, die eine Beziehung zwischen einem Ganzen und seinen vom Ganzen existenzabhängigen Teilen beschreibt. Einfach ausgedrückt: Bei einer Komposition kann ein Teil nie größer als das Ganze sein.

b: Fuer eine Person sollen von der Linken und rechten Hand jewals folgende Abdruecke gespeichert werden:

F1 bis F5: Abdruecke der fuenf Finger
H1 und H2: Abdruecke der Handflaechenbereiche

Zu jedem Abddruck sollen ein Bild und ein String gespeichert werden.

Die Zeichenkenne enthaelt Beschreibungen derjenigen Merkmale des Abdrucks. die beim Vergleich von Fingerabdruecken verwendet werden.

Die Zeichekette wird von der Methode berechneZeichenkette() anhand des Bildes berechnet.

die Algorithemn zur Berechnung der Zeichenkette sind fuer Fingerabdruck und Handflaechenabdruck unterschiedlich.

Es existieren bereits folgende Klasse abdruck, die fuer das Klassendiagramm verwendet werden soll.


Abdruck
-: Bild
-: String
----------
+berechneZeichenkette()

Erstellen Sie auf der Folgeseite ein UML - Klassendiagramm, dass ...
- die Klassen Person, Hand, Finger, Handflaechenbereich, Abdruck, AbdruckFinger, AbdruckHandflaeche darstellt.

siehe Bild: UML-Fingerabdruecke.jpg

- die Beziehungen zwischen den Klassen mit dem Kadrinalitaeten angbiet.

 in dem Fall Handabdruck und Finger

 
- Geben Sie an, in welchen Klassen die Methode berechneZeichenkette() ueberschrieben werden muss.


Test
