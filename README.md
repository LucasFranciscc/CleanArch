# CleanArch

Executar a migration para criar o banco

1. criar no sql server a base de dados CleanArch
2. No visual studio ir no menu superior e clicar na opcao Tools > Nuget Package Manager > Package Manager Console
3. No terminal em Default project selecionar CleanArch.Infra.Data
4. Executar o comando update-database


Para criar uma migration deve executar o comando "add-migration nomeDaMigration" em seguida executar o comando "update-database"