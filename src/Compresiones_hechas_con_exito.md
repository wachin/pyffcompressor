Menos de 16 MB acepta WhatsApp en un video, y para poderlos compartir a ese tamaño he hecho los siguientes
calculos para comprimir videos

Cualquiera de las líneas ejemplo:

-vf "scale=512:288" -b:v 220k -r 15 -ac 1 -b:a 30k -ar 44100

hay que colocarla en FFmulticonverter en:

Comando:


*****************
Un canal de audio
*****************

video 300kbps, 512x288, fps15,audio 96kbps, 44.1kHz, 1 chnnels, AAC
-vf "scale=512:288" -b:v 300k -r 15 -ac 1 -b:a 96k -ar 44100

video 256kbps, 512x288, fps15, audio 96kbps, 44.1kHz, 1 chnnels, AAC
-vf "scale=512:288" -b:v 256k -r 15 -ac 1 -b:a 96k -ar 44100

video 180kbps, 512x288, fps15, audio 96kbps, 44.1kHz, 1 chnnels, AAC
-vf "scale=512:288" -b:v 180k -r 15 -ac 1 -b:a 96k -ar 44100

video 145kbps, 512x288, fps15, audio 96kbps, 44.1kHz, 1 chnnels, AAC
-vf "scale=512:288" -b:v 145k -r 15 -ac 1 -b:a 96k -ar 44100

video 220kbps, 512x288, fps15. Audio 30k, 44.1kHz (Convirtió un video de 7:58min a 15.5MB)
                                                  (Convirtió un video de 8:22min a 15.2MB)
-vf "scale=512:288" -b:v 220k -r 15 -ac 1 -b:a 30k -ar 44100
                                                  buena calidad

video 200kbps, 512x288, fps15. Audio 30k, 44.1kHz
                                                  (Convirtió un video de 8:42min a 15,3MB)
                                                  (Convirtió un video de 9:17min a 11,9MB)
                                                  (Convirtió un video de 9:35min a 15.5MB bien)
-vf "scale=512:288" -b:v 200k -r 15 -ac 1 -b:a 30k -ar 44100


video 180kbps, 512x288, fps15. Audio 30k, 44.1kHz (Convirtió un video de 9:17min a 14,4MB)
                                                  (Convirtió un video de 10:9min a 15,4MB)
-vf "scale=512:288" -b:v 180k -r 15 -ac 1 -b:a 30k -ar 44100


video 170kbps, 512x288, fps15. Audio 30k, 44.1kHz (Convirtió un video de 10:14min a 15,2MB)
                                                  (Convirtió un video de  9:35min a 13.5MB)
-vf "scale=512:288" -b:v 170k -r 15 -ac 1 -b:a 30k -ar 44100


video 165kbps, 512x288, fps15. Audio 30k, 44.1kHz (Ej.: Video Telegram 10:55min a 16.2MB se pasó)
-vf "scale=512:288" -b:v 165k -r 15 -ac 1 -b:a 30k -ar 44100


video 160kbps, 512x288, fps15. Audio 30k, 44.1kHz (Convirtió un video de 10:45min a 12.8MB)
-vf "scale=512:288" -b:v 160k -r 15 -ac 1 -b:a 30k -ar 44100

************
El siguiente es un video con baja calidad de video pero alta calidad de sonido
-vf "scale=512:288" -b:v 155k -r 15 -ac 1 -b:a 80k -ar 44100

video 150k, 512x288, fps15. Audio 30k, 44.1kHz  (Convirtió un video de 11:07min a 15,05MB)
-vf "scale=512:288" -b:v 150k -r 15 -ac 1 -b:a 30k -ar 44100


video 145k, 512x288, fps15. Audio 30k, 44.1kHz  (Convirtió un video de 12:29min a 15,70MB)
-vf "scale=512:288" -b:v 145k -r 15 -ac 1 -b:a 30k -ar 44100


video 140k, 512x288, fps15. Audio 30k, 44.1kHz

-vf "scale=512:288" -b:v 140k -r 15 -ac 1 -b:a 30k -ar 44100


video 130k, 512x288, fps15, Audio 30k, 44.1kHz  (Convirtió un video de 13:36 min a 15.9MB)
-vf "scale=512:288" -b:v 130k -r 15 -ac 1 -b:a 30k -ar 44100


video 120k, 512x288, fps15, Audio 27k, 44100   (Convirtió un video de 14:23min a 15.8MB)
                                               (Convirtió un video de 14:05min a 15.7MB)
-vf "scale=512:288" -b:v 120k -r 15 -ac 1 -b:a 27k -ar 44100

video 120k, 512x288, fps15, Audio 26k, 44100        (Convirtió un video de 14:35min a 15.7MB)
-vf "scale=288:512" -b:v 120k -r 15 -ac 1 -b:a 26k -ar 44100


video 110k, 512x288, fps15, Audio 24k, 44100   (Convirtió un video de 15:14min a 15.2MB)
-vf "scale=512:288" -b:v 110k -r 15 -ac 1 -b:a 24k -ar 44100


video 100k, 512x288, fps15, Audio 19k, 44100  (Convirtió un video de 16:45min a 14.9MB)
-vf "scale=512:288" -b:v 100k -r 15 -ac 1 -b:a 19k -ar 44100

video 95k, 512x288, fps15, Audio 19k, 44100  (Convirtió un video de 17:18min a 15.1MB)
-vf "scale=512:288" -b:v 95k -r 15 -ac 1 -b:a 19k -ar 44100
Brandon

video 90k, 512x288, fps15, Audio 18k, 44100   (Convirtió un video de 19:23min a 15.6MB)
                                              (Convirtió un video de 18:18min a 14.68MB)
-vf "scale=512:288" -b:v 90k -r 15 -ac 1 -b:a 18k -ar 44100


video 85k, 512x288, fps15, Audio 18k, 44100   (Convirtió un video de 20:20min a 15.8MB)
-vf "scale=512:288" -b:v 85k -r 15 -ac 1 -b:a 18k -ar 44100


video 80k, 512x288, fps15, Audio 18k, 44100   (Convirtió un video de 21:07min a 15.6MB)
-vf "scale=512:288" -b:v 80k -r 15 -ac 1 -b:a 18k -ar 44100
Beto para la Boda usar


video 70k, 512x288, fps15, Audio 18k, 44100   (Convirtió un video de 20:33min a 14.4MB)
                                              (Convirtió un video de 21:10min a 14.3MB)
                                              (Convirtió un video de 22:07min a 15.1MB)
-vf "scale=512:288" -b:v 75k -r 15 -ac 1 -b:a 18k -ar 44100


-vf "scale=512:288" -b:v 70k -r 15 -ac 1 -b:a 18k -ar 44100

-vf "scale=512:288" -b:v 70k -r 15 -ac 1 -b:a 22k -ar 44100
                                              (Convirtió un video de 22:50min a 15.7MB)


-vf "scale=512:288" -b:v 65k -r 15 -ac 1 -b:a 18k -ar 44100
                                              (Convirtió un video de 23:00min a 16.2MB)

-vf "scale=512:288" -b:v 65k -r 15 -ac 1 -b:a 20k -ar 44100


-vf "scale=512:288" -b:v 65k -r 15 -ac 1 -b:a 22k -ar 44100
                                              (Convirtió un video de 23:12min a 15.1MB) mejoró el audio

-vf "scale=512:288" -b:v 65k -r 15 -ac 1 -b:a 24k -ar 44100
                                              (Convirtió un video de 23:12min a 15.5MB) mejoró el audio




-vf "scale=512:288" -b:v 64k -r 15 -ac 1 -b:a 18k -ar 44100


-vf "scale=512:288" -b:v 64k -r 15 -ac 1 -b:a 18k -ar 44100
                                              (Convirtió un video de min a MB)

-vf "scale=512:288" -b:v 63k -r 15 -ac 1 -b:a 18k -ar 44100
                                              (Convirtió un video de 23:12min a 14.2MB)

-vf "scale=512:288" -b:v 72k -r 15 -ac 1 -b:a 19k -ar 44100
                                              (Convirtió un video de 23:27min a 15.9MB)

video 70k, 512x288, fps15, Audio 16k, 44100   (Convirtió un video de 23:27min a 15.1MB pero la calidad del audio es baja)
-vf "scale=512:288" -b:v 70k -r 15 -ac 1 -b:a 16k -ar 44100



video 70k, 512x288, fps14, Audio 12k, 44100   (Convirtió un video de 21.56 a 14.5MB pero video se apagaba y prendia y audio se escuchaba feo)
-vf "scale=512:288" -b:v 70k -r 14 -ac 1 -b:a 12k -ar 44100


*****************
UN CANAL VERTICAL
*****************


video 220kbps, 288x512, fps15,  Audio 30k, 44.1kHz  (Convirtió un video de 8:05min a 14.4MB)
-vf "scale=288:512" -b:v 220k -r 15 -ac 1 -b:a 30k -ar 44100


video 180kbps, 288x512, fps15,  Audio 30k, 44.1kHz
-vf "scale=288:512" -b:v 180k -r 15 -ac 1 -b:a 30k -ar 44100





************
QVGA 320×240
************
https://es.wikipedia.org/wiki/Resoluci%C3%B3n_de_pantalla

video 90k, 320×240, fps15, Audio 18k, 44100   (Convirtió un video de  a MB)
-vf "scale=320:240" -b:v 90k -r 15 -ac 1 -b:a 18k -ar 44100


Experimento
video 70k, 320×240, fps15, Audio 17k, 44100   (Convirtió un video de  a MB)
-vf "scale=320:240" -b:v 70k -r 15 -ac 1 -b:a 17k -ar 44100






CUADRADO

Tenía un video de 1080x1080px de 7:13min así que probé así  (Convirtió un video de 7:13min a 9.5MB)
-vf "scale=512:512" -b:v 150k -r 15 -ac 1 -b:a 30k -ar 44100




320x240

video 115kbps, 320x240, fps15
audio 96kbps, 44.1kHz, 2 chnnels, AAC
-vf "scale=320:240" -b:v 115k -r 15 -ac 2 -b:a 96k -ar 44100


-vf "scale=320:240" -b:v 115k -r 15 -ac 2 -b:a 80k -ar 44100
                                               (Convirtió un video SD de 10:54 min a 15.6MB)

-vf "scale=320:240" -b:v 115k -r 15 -ac 2 -b:a 65k -ar 44100


-vf "scale=320:240" -b:v 115k -r 15 -ac 2 -b:a 40k -ar 44100
                                               (Convirtió un video SD de 13:52 min a 15.8MB)

video 115kbps, 320x240, fps15
audio 32kbps, 44.1kHz, 1 chnnels, AAC
-vf "scale=320:240" -b:v 115k -r 15 -ac 1 -b:a 32k -ar 44100

vídeo 95kbps, 320x240, fps15, audio 32kbps, 1 chnnel
-vf "scale=320:240" -b:v 95k -r 15 -ac 1 -b:a 30k -ar 44100



