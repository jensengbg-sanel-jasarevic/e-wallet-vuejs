#### URL
https://ewallet-vuejs.herokuapp.com/

# Inlämningsuppgift 1: E-wallet

Du ska bygga en digital plånbok som samlar alla kreditkort. Det ska gå och se sina kreditkort samt lägga till ett nytt.

#### Design
Mockup överfärdiga appen. Figmaskiss: https://www.figma.com/file/G4ep4nWFUplM8kXEntq83C/E-Wallet?node-id=11%3A2

#### Tekniker du ska använda i denna app är följande:
* Local properties.
* Inherited properties (props).
* Computed properties.
* Events (listen and emit).
* Methods.
* v-for (incl. key and props in a loop).
* Vue-router.
* LocalStorge (VG).
* Life Cycle Hook (VG).

#### Funktionella krav
* Viewn ska högst upp visa active card.
* Vid tryck på Add new card ska man routas vidare till /addcard.
* Varje nytt card som läggs till ska synas i en lista i denna vy.
* Vid klick på kort i listan så ska den läggas som active card högst upp i vyn.
* Ett nytt kort ska kunna läggas till med följande information: vendor, card number, cardholder, expire
month, expire year, CCV.

## Instruktioner

**För att få Godkänt ska du:**
* Ha gjort uppgiften med ```vue create```.
* Gjort enligt Figma skissen (det behöver inte vara exakt enligt design).
* Det är en single file application (SPA) som använder ```vue-router```.

**För att Väl Godkänt ska du:**
* Spara korten och alla nya kort som läggs till i local storage samt läsa från local storage.
* Det ska gå att ta bort ett kort (som också tas bort från local storage).
* Fälten när en kort läggs till ska valideras så du i fältet kortnummer enbart kan mata in siffror och max är 16 siffror. Fältet för namn ska enbart ta bokstäver.

### Komponentarkitektur

![alt text](components-e-wallet.png)
