**1. Kompozyt (Composite)**

Wzorzec kompozytu jest wzorcem strukturalnym, który pozwala traktować pojedyncze obiekty i złożone zbiory obiektów tak samo. Jest to szczególnie przydatne, gdy tworzysz struktury drzewiaste, gdzie elementy mogą zawierać inne elementy. 

**Zastosowanie w .NET Core:**

Można zastosować ten wzorzec w .NET Core podczas projektowania struktury menu w aplikacji lub podczas tworzenia struktury folderów, gdzie folder może zawierać pliki, a także inne foldery.

**2. Obserwator (Observer)**

Wzorzec obserwatora jest wzorcem behawioralnym, który pozwala na powiadamianie obiektów o zmianach stanu innego obiektu. W tym wzorcu obiekt, którego stan jest obserwowany, nazywany jest "subject", a obiekty, które obserwują stan, są nazywane "observers" lub "listeners".

**Zastosowanie w .NET Core:**

W .NET Core, ten wzorzec jest często używany do monitorowania zdarzeń, na przykład w interfejsach użytkownika, gdzie różne komponenty mogą nasłuchiwać i reagować na zdarzenia, takie jak kliknięcia przycisku.

**3. Strategia (Strategy)**

Wzorzec strategii jest wzorcem behawioralnym, który pozwala na wybór algorytmu w trakcie wykonywania programu. To jest szczególnie przydatne, gdy istnieje wiele sposobów wykonania zadania, i chcesz móc łatwo przełączać między nimi.

**Zastosowanie w .NET Core:**

W .NET Core, można użyć tego wzorca, na przykład, gdy masz różne algorytmy sortowania, i chcesz umożliwić użytkownikowi wybór algorytmu, który chce użyć.

**4. Metoda Wytwórcza (Factory Method)**

Metoda wytwórcza to wzorzec kreacyjny, który pozwala na definiowanie interfejsu do tworzenia obiektu, ale pozwala klasom podrzędnym decydować, która klasa ma zostać zainstancjonowana. To jest użyteczne, gdy masz wiele typów obiektów, które mogą być tworzone, i chcesz zdecydować, który z nich stworzyć w trakcie wykonywania programu.

**Zastosowanie w .NET Core:**

W .NET Core, ten wzorzec może być używany, na przykład, w systemie logowania, gdzie różne typy loggerów (np. logger konsoli, logger plików, itp.) mogą być tworzone w zależności od konfiguracji.

**5. Dekorator (Decorator)**

Wzorzec dekoratora jest wzorcem strukturalnym, który pozwala na dodawanie nowych zachowań do obiektów poprzez umieszczenie tych obiektów wewnątrz specjalnych obiektów dekoratorów. Dekoratory są elastycznym alternatywą dla dziedziczenia w celu rozszerzania funkcjonalności, ponieważ pozwalają na dodawanie i usuwanie funkcji w czasie wykonywania.

**Zastosowanie w .NET Core:**

W .NET Core, ten wzorzec jest często używany do dodawania nowych funkcji do strumieni IO. Na przykład, możesz mieć prosty strumień odczytu, ale następnie "udekorować" go, dodając funkcje buforowania lub odczytu tekstu. Dekoratory są również często używane w middleware ASP.NET Core, gdzie różne warstwy middleware mogą być dodawane lub usuwane, aby zmienić zachowanie aplikacji.

W sumie, te wzorce projektowe są niezwykle przydatne narzędzia do tworzenia bardziej zrozumiałego, elastycznego i utrzymywalnego kodu. Wszystkie one mają swoje miejsce w ekosystemie .NET Core i mogą znacznie ułatwić proces projektowania i budowania skomplikowanych systemów.
