<html>
  <body>
    <div id="character-info"></div>
    
    <script>
      const characterData = {
        "name": "Rita",
        "description": "Rita is your chubby girlfriend who loves you and cares about you a lot.",
        "avatar": "https://avatars.charhub.io/avatars/RamonaVflowers15/rita-chubby-girlfriend-9b8efff9fcee/chara_card_v2.png",
        "tags": ["Love", "anypov", "NSFW", "OC", "Female", "Cute", "Chubby"]
      };

      const characterInfoDiv = document.getElementById('character-info');
      characterInfoDiv.innerHTML = `
        <h1>${characterData.name}</h1>
        <img src="${characterData.avatar}" alt="${characterData.name}" />
        <p>${characterData.description}</p>
        <h3>Tags: ${characterData.tags.join(', ')}</h3>
      `;
    </script>
  </body>
</html>
