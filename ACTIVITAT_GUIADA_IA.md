# Activitat guiada amb IA - Lab 1.2

Aquest laboratori aplica el flux de treball per tasques a Symfony: cada canvi ha de tenir targeta, prompt, pla, PR, proves i revisió crítica.

## Nivell de guia

**Nivell 1 - Molt guiat.** Encara podeu treballar amb instruccions molt concretes. Cada tasca ha de deixar clar ruta, fitxers, PR i prova al navegador.

## Entrega per cada tasca

- **Descripció funcional:** què s'ha de fer i per què aporta valor al projecte.
- **Prompt utilitzat:** prompt inicial i prompts de refinament, si n'hi ha.
- **Pla generat per la IA:** pla complet o resum si l'eina no el guarda.
- **Link al PR:** URL del PR amb els commits associats. Pot estar obert o merged.
- **Joc de proves:** casos correctes, errors esperats, codis HTTP si n'hi ha, captures, comandes, curl/Postman o comprovació visual.
- **Revisió crítica:** què ha fet bé la IA, què heu hagut de corregir i quines decisions són vostres.

## Tasques suggerides

1. Crear un controlador i una ruta `/hello/demo`.
2. Retornar una vista Twig amb variables.
3. Connectar una entitat `Car` amb una taula MySQL.

Després de cada tasca, afegiu a Moodle el link al PR i el joc de proves. No espereu al final del laboratori.

## Exemple de joc de proves

- Ruta existent `/hello/demo` -> 200 i contingut esperat.
- Ruta incorrecta -> 404.
- Variable enviada al Twig -> es mostra correctament.
- Variable no enviada -> error identificat i corregit.
