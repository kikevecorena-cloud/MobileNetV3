MobileNetV3 + decodificador: segmentacion semantica.
RGB originales referenciados por ruta absoluta en manifest.csv; conservar fuentes.
Mascaras semanticas: 0=fondo, 1=hoja sin mancha anotada, 2=mancha.
Mascaras binarias: 0/255; no confundir con IDs semanticos.
No se inventan contornos ni negativos Healthy sin revision.
Revisar review_template.csv; guardar como /content/drive/MyDrive/LeafAndroid_reviews.csv y reejecutar para otra version.
Aprobacion: approved / pending / rejected, por tarea.
Las listas reviewed son las autorizadas para entrenamiento/evaluacion.
Agrupacion nominal y duplicados exactos; pendiente deduplicacion visual y por planta/sesion.
Conservar splits existentes; augmentaciones solo en train.
MobileNetV3Small es el encoder; necesita decodificador para producir mascaras.
