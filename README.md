# wtyczka-inzynieria_oprogramowania
Wtyczka WordPress do automatycznego generowania podsumowań artykułów przy użyciu OpenAI API.

## Funkcjonalności

- 🤖 Automatyczne generowanie podsumowań artykułów
- 📱 Shortcode `[ai_summary]` do łatwego umieszczania
- ⚙️ Panel administracyjny do konfiguracji
- 🔒 Bezpieczne przechowywanie kluczy API

## Instalacja

1. Pobierz plugin z GitHub
2. Umieść w folderze `/wp-content/plugins/`
3. Aktywuj w panelu WordPress
4. Dodaj klucz OpenAI API do `wp-config.php`:

```php
define('OPENAI_API_KEY', 'twój-klucz-api');

ai-section-summaries/
├── ai-section-summaries.php
└── inc/
    ├── Summarizer.php
    ├── ContentProcessor.php
    ├── Admin.php
    └── Settings.php
