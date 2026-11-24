# Zen Kitchen Remodel – WordPress Sitesi

zenkitchenremodel.com sitesinin özel kodu.

## Repoda olanlar

- `wp-content/themes/betheme-child/`: aktif child tema (Lexend fontları dahil)
- `PLUGINS.md`: kullanılan hazır eklentilerin ve temaların adı ve sürümü

## Repoda olmayanlar

- `wp-config.php`, veritabanı yedeği (`.sql` / `.gz`): gizli bilgi içerir
- `wp-content/uploads/`: görseller (UpdraftPlus yedeğinde)
- WordPress çekirdeği (`wp-admin/`, `wp-includes/`)
- Hazır eklentiler ve ana tema (Betheme): `PLUGINS.md` listesine bakın
- Önbellek, yedek `.zip` dosyaları ve loglar

## Siteyi yeniden kurma

1. WordPress'i kurun.
2. Betheme ana temasını ve `PLUGINS.md` içindeki eklentileri yükleyin.
3. Bu repodaki `wp-content/themes/betheme-child/` klasörünü sunucuya kopyalayın.
4. UpdraftPlus ile veritabanını ve `uploads` klasörünü geri yükleyin.

Not: Sitenin tasarım ayarları (Betheme seçenekleri, sayfa düzenleri) veritabanında durur, bu repoda değil.
