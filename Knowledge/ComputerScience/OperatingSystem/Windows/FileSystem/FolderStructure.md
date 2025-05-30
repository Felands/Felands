# Folder Structure

## Windows

### AppData

AppData用于存放每一位用户使用应用时留下的个人数据，因此每个用户的用户目录下都会存在该文件夹。
AppData下有三个子文件夹：1.Local、2.LocalLow、3.Roaming

- Local

Local文件夹存放的数据是本地化的，与之相对的是Roaming所表示的漫游概念

- LocalLow

LocalLow是用来存放共享数据

- Roaming

“Windows uses the Roaming folder for application specific data, such as custom dictionaries, which are machine independent and should roam with the user profile.”
“Windows系统使用这个文件夹来存放应用相关的数据，比如个人制订的字典（Word里能用到）。这些数据都是独立于机器的，并且应该随着你的用户账号而迁移。”
因此Roaming文件夹存放的是漫游应用数据，可随着工作环境的迁移而迁移的，即相同账号在不同设备上使用的是相同的漫游数据，与之相对的是Local所表示的本地概念
