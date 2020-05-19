[libtd-ktx](../../index.md) / [kotlinx.telegram.extensions](../index.md) / [UserKtx](index.md) / [getChatMember](./get-chat-member.md)

# getChatMember

`open suspend fun `[`User`](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi.User.html)`.getChatMember(chatId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`ChatMember`](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi.ChatMember.html)

Suspend function, which returns information about a single member of a chat.

### Parameters

`chatId` - Chat identifier.

**Return**
[TdApi.ChatMember](https://tdlibx.github.io/td/docs/org/drinkless/td/libcore/telegram/TdApi.ChatMember.html) A user with information about joining/leaving a chat.
