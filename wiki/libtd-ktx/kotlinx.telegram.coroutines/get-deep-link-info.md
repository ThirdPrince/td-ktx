[libtd-ktx](../index.md) / [kotlinx.telegram.coroutines](index.md) / [getDeepLinkInfo](./get-deep-link-info.md)

# getDeepLinkInfo

`suspend fun `[`TelegramFlow`](../kotlinx.telegram.core/-telegram-flow/index.md)`.getDeepLinkInfo(link: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`DeepLinkInfo`](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi.DeepLinkInfo.html)

Suspend function, which returns information about a tg:// deep link. Use
&amp;quot;tg://need_update_for_some_feature&amp;quot; or &amp;quot;tg:someUnsupportedFeature&amp;quot; for testing.
Returns a 404 error for unknown links. Can be called before authorization.

### Parameters

`link` - The link.

**Return**
[DeepLinkInfo](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi.DeepLinkInfo.html) Contains information about a tg:// deep link.
