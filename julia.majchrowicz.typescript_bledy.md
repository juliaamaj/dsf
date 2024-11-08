# Kompilacja pliku TypeScript z błędem

## 1. Inicjalizacja projektu npm
- W terminalu uruchomiono komendę `npm init -y`, która wygenerowała plik `package.json`.

## 2. Instalacja TypeScript
- Zainstalowano TypeScript za pomocą komendy `npm install typescript --save-dev`.

## 3. Kompilacja pliku z błędnym kodem
- Uruchomiono komendę `npx tsc 028_bledny_kod.ts`, która spowodowała wygenerowanie błędu w terminalu:

Error: Type 'string' is not assignable to type 'number'. Error: Type 'boolean' is not assignable to type 'number'.