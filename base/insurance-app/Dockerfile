# Použije oficiálny openjdk image ako základ (alebo iný podľa potreby)
FROM openjdk:17-jdk-slim

# Nastaví pracovný adresár
WORKDIR /app

# Skopíruje všetky súbory projektu
COPY . .

# Predpokladám, že ide o jar súbor alebo nejakú binárku
# COPY target/booking-app.jar ./booking-app.jar

# Príkaz na spustenie aplikácie (upravi podľa typu app)
# CMD ["java", "-jar", "booking-app.jar"]

