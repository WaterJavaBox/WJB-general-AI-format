# WJB AI替換詞通用格式

用於建立標準的通用替換詞格式

使用 ``X`` for迴圈替換

## 機器人標準替換

標準替換

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {bot-name} | 機器人短名稱 | 可用於主要簡稱 |
| {bot-nick} | 機器人暱稱 | 用於多個暱稱 |
| {bot-fullName} | 機器人全稱 | |
| {bot-presonality} | 機器人性格&個性 | 自訂義 或 [16型性格](https://www.16personalities.com/tw/%E6%80%A7%E6%A0%BC%E6%B8%AC%E8%A9%A6) |
| {bot-birthday} | 機器人生日 | 生日，格式為yyyy-mm-dd |
| {bot-gender} | 機器人性別 | |
| {bot-height} | 機器人身高 | |
| {bot-weight} | 機器人體重 | |
| {bot-language} | 機器人使用語言 | 機器人會使用的語言，最多建議三個 |
| {bot-id} | 機器人ID | |

## 主人名稱ID

這是一個可以浮動的格式，只須遵循規則增加數字即可

可使用於訓練

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {master1-name} | 第一主人名稱 | 可用於類似父親、母親等 |
| {master1-fullName} | 第一主人全名 | 可用於類似父親、母親等 |
| {master1-id} | 第一主人ID | 可用於類似父親、母親等 |
| {master1-call} | 第一主人的稱呼 | AI如何稱呼對方 |
| {master1-relation} | 第一主人的關係 | AI與使用者的關係 |
| {master2-name} | 第二主人名稱 | 可用於類似父親、母親等 |
| {master2-fullName} | 第二主人全名 | 可用於類似父親、母親等 |
| {master2-id} | 第二主人ID | 可用於類似父親、母親等 |
| {master2-call} | 第二主人的稱呼 | AI如何稱呼對方 |
| {master2-relation} | 第二主人的關係 | AI與使用者的關係 |

用於替換類別

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {masterX-name} | 浮動主人名稱 | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |
| {masterX-fullName} | 浮動主人全名 | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |
| {masterX-id} | 浮動主人ID | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |
| {masterX-call} | 浮動主人稱呼 | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |
| {masterX-relation} | 浮動主人的關係 | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |

## 訓練用

這是一個可以浮動的格式，只須遵循規則增加數字即可

訓練文件用，可以替換訓練的資訊

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {example-prompt} | 自訂義的範例提示 | 用於回應的範例提示詞，告訴機器人想模仿的語氣 |
| {train1-name} | 第一訓練名稱 | 訓練用專屬 |
| {train1-fullName} | 第一訓練全名 | 訓練用專屬 |
| {train1-id} | 第一訓練ID | 訓練用專屬 |
| {train1-call} | 第一訓練稱呼 | 訓練用專屬 |
| {train2-name} | 第二訓練名稱 | 訓練用專屬 |
| {train2-fullName} | 第二訓練全名 | 訓練用專屬 |
| {train2-id} | 第二訓練ID | 訓練用專屬 |
| {train2-call} | 第二訓練稱呼 | 訓練用專屬 |

用於替換類別

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {trainX-name} | 浮動訓練名稱 | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |
| {trainX-fullName} | 浮動訓練全名 | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |
| {trainX-id} | 浮動訓練ID | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |
| {trainX-call} | 浮動訓練稱呼 | 此大寫X必須將其替換為數字，轉換為數字後才呼叫 |

## 訊息

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {message_userName} | 訊息傳送者的姓名 | |
| {message_userID} | 訊息傳送者的姓名 | |
| {message_content} | 訊息內容 | |
| {message_userRelation} | 傳送者與機器人的關係 | |
| {message_reference} | 回應的訊息內容 | |
| {message_time} | 訊息傳送的時間 | 跟 {time} 不一樣 |

## 其他

這是一個可以浮動的格式，只須遵循規則放置即可

基礎模塊

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {time} | 現在時間 | |
| {other-1} | 其他的附加提示詞 | 通常用於說明訊息內，你對此對話，希望有什麼要求。例如 : 不要在本對話中加入句號 |
| {other-2} | 其他的附加提示詞 | 通常用於說明訊息內，你對此對話，希望有什麼要求。例如 : 不要在本對話中加入句號 |


用於替換類別

| 替換詞 | 作用 | 說明 |
|-----|-----|-----|
| {other-X} | 浮動的附加提示詞 | 此大寫X必須將其替換為字符，例如type、test或者prompt之類的，轉換為其他字符後才呼叫 |
