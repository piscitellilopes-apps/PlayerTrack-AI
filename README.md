# PlayerTrack AI S24 – Android-Quellprojekt v0.5

Dies ist ein **Android-Studio-Projekt, keine installierbare APK**. Android Studio mit Android SDK 35 öffnen, Gradle synchronisieren und Build > Build APK(s) wählen. Die APK entsteht dann unter `app/build/outputs/apk/debug/`.

Bereits implementiert: lokale MP4-Datei über Android-Dateiauswahl öffnen, ansehen, manuell Szenen-Start/Ende markieren, Vorschau-Zoom (1–2x), Szenenliste als CSV speichern. Offline; keine Serverübertragung.

Noch NICHT implementiert: automatische Diego-Erkennung, Re-Identifikation nach Kameraschwenks, Ball-/Pass-/Flanken-Erkennung, automatischer Videoschnitt, 1080p/4K-Export, GPS-genaue Laufleistungsanalyse. Für diese Features ist ein getestetes Computer-Vision-Modell, Videopipeline und kalibrierte Kamera nötig. Ein 1080p-Export darf nicht als vorhanden ausgegeben werden.

Hinweis: Für das Kompilieren ist ein Windows-/Mac-/Linux-Rechner mit Android Studio erforderlich. Hier war keine Android-SDK-/Gradle-Buildumgebung verfügbar; APK wurde nicht erstellt oder getestet.
