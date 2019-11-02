Hi, this is bitrix deployment compose file. To start

1. Create directory, for example "data" and copy your bitrix directory to newly created directory.
2. Edit .env file and set env DATA=your_project and PORT=80
3. Run command "docker-compose up -d"
4. Enjoy

P.S. You will probably need to edit some files like
./bitrix/php_interface/init.php < define('BX_COMPRESSION_DISABLED',true);
