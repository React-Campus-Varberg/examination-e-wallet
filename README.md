# Inlämningsuppgift - E-wallet

## Instruktioner
Du ska bygga en digital plånbok som samlar alla kreditkort. Det ska gå och se sina kreditkort samt lägga till ett nytt. Alla bilder du behöver ha finns i mappen assets i detta repo.


**Figmaskiss:** https://www.figma.com/file/PING2mPghGAlgaXNOmUfNz/E-Wallet-(Copy)?node-id=11%3A2

## Instruktioner

**För att få Godkänt ska du:**
* Gjort enligt Figma skissen (det behöver inte vara exakt enligt design)
* Det är en single file application (SPA) som använder ```react-router```

**För att Väl Godkänt ska du:**
* Spara korten och alla nya kort som läggs till i local storage samt läsa från local storage
* Det ska gå att ta bort ett kort (som också tas bort från local storage)
* Fälten när en kort läggs till ska valideras så du i fältet kortnummer enbart kan mata in siffror och max är 16 siffror. Fältet för namn ska enbart ta bokstäver.
