# FullStackInventoryApp

Апликација за управување со производи – со frontend изработен во Angular и backend во .NET Core.

## 🚀 Како да го стартувате проектот

### ✅ Backend (.NET Core Web API)

1. Отворете го решението во **Visual Studio**.
2. Изберете `IIS Express` како начин на извршување.
3. Притиснете **F5** или кликнете на **Start** за да го стартувате backend-от.

#### ⚙️ Конфигурирање на базата на податоци

- Се користи **SQL Server** преку **SQL Server Object Explorer**.
- Во **Package Manager Console**, извршете ја командата: Update-Database

Ова ќе ја креира базата на податоци според миграциите дефинирани во проектот.

> Уверете се дека `appsettings.json` содржи валиден `ConnectionString` до вашиот локален SQL Server.

---

### 🌐 Frontend (Angular)

1. Отворете терминал во папката со Angular проектот.
2. Инсталирајте ги зависностите: npm install
3. Стартувајте ја апликацијата: ng serve
4. Откако ќе се стартува успешно, **посетете ја веб-адресата што ќе биде прикажана во конзолата**.

---

## 📦 Технологии

- **Backend**: .NET Core Web API
- **Frontend**: Angular
- **Database**: SQL Server
