**RADIO SU VLC** -ITA-

Per ascoltare stazioni radio direttamente su VLC Media Player puoi seguire questi passaggi:

1. Prima cosa, apri un editor di testo e crea un nuovo file.

2. Nel file di testo, inserisci il seguente testo:

#EXTM3U

#EXTINF:-1 tvg-id="NOME_RADIO" tvg-chno="ID_RADIO" group-title="Radio",NOME_RADIO

LINK_RADIO
  
  dove:
  
      NOME_RADIO: Il nome della stazione radio (es. "RTL 102.5").
      ID_RADIO: Un identificativo per la radio (es. "1").
      LINK_RADIO: L'URL del flusso streaming della radio.
  
  Un esempio:
  
#EXTM3U
#EXTINF:-1 tvg-id="RTL 102.5" tvg-chno="1" group-title="Radio",RTL 102.5
http://shoutcast.rtl.it:3010/

Puoi aggiungere altre stazioni radio copiando e modificando le righe sopra per ogni nuova radio che vuoi inserire.

3. Una volta inserite tutte le stazioni radio desiderate, salva il file. Assicurati di cambiare l'estensione del file da .txt a .m3u (esempio: radio_playlist.m3u).

5. Apri VLC Media Player, poi:

    Clicca su Media → Apri file... e seleziona il file .m3u che hai appena creato. VLC caricherà automaticamente la playlist!

**RADIO SU VLC** -ENG-

To listen to radio stations directly on VLC Media Player you can follow these steps:

1. First, open a text editor and create a new file.

2. In the text file, enter the following text:

#EXTM3U
#EXTINF:-1 tvg-id="RADIO_NAME" tvg-chno="ID_RADIO" group-title="Radio",RADIO_NAME
LINK_RADIO

where:

      RADIO_NAME: The name of the radio station (e.g. "RTL 102.5").
      ID_RADIO: An identifier for the radio (e.g. "1").
      LINK_RADIO: The URL of the radio streaming stream.

  An example:

#EXTM3U
#EXTINF:-1 tvg-id="RTL 102.5" tvg-chno="1" group-title="Radio",RTL 102.5
http://shoutcast.rtl.it:3010/

You can add more radio stations copying and editing the lines above for each new radio you want to insert.

3. Once you have entered all the radio stations, save the file. Change the file extension from .txt to .m3u (example: radio_playlist.m3u).

5. Open VLC Media Player, then:

    Click Media → Open File... and select the .m3u file you just created. VLC will automatically load the playlist!
