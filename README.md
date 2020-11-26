$thumbnail[$authorAvatar]
$nomention
$color[#ffcbdb]
$title[💼 | Trabalhando]
$description[
<@$authorID> **Você trabalhou de** **__$randomText[🎛Operador de Áudio;🚗Uber;🛵iFood;🏛Político;🏃Atletista;🖥Streamer;🔴YouTuber;💼Juíz;💵Bancário;📦Entregador;🔧Mecânico;🛰Hacker;🚚 Caminhoneiro;👮Policial;👷 Pedreiro;🕵️Detetive;🐳Pescador;🚖Taxista;🚑Médico;🚒 Bombeiro;🚂Maquinista;🎙Locutor ;📠 Secretário;🎭Ator;🎥Câmera Man; ⚗️Cientista;🎶Músico;☎️ Recepcionista;🛢Petroleiro;⚰️ Agente Funerário;💊Farmacêutico;💈Barbeiro;🚀?Astronauta;🚜 Fazendeiro;✈️Piloto de Avião;🖼️Fotógrafo;🤹Palhaço;⛏Minerador;⚒️Lenhador;🔪Chef de Cozinha]__** **e ganhou** **__$random[100;765] Estrelas!__**]

$setUserVar[Estrelas ;$sum[$getUserVar[Estrelas];$random[100;765]]]

$cooldown[30m;**● <@$authorID> __💼 | Você está cansado demais para__ ● __trabalhar agora! Espere__** %time%]
$footerIcon[$randomText[https://cdn.discordapp.com/attachments/679067296786022434/685809259241275402/emoji_79.gif;https://cdn.discordapp.com/attachments/770759810299330560/776907812848140308/MarioLuigiDancing.gif]]

$footer[$username#$discriminator[$authorID]]
$addTimestamp
$botTyping
