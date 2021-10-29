How To Run Schedule In Localhost or Windows

your_xampp_local_disk_name:\xampp\php\php.exe your_xampp_local_disk_name:\xampp\htdocs\your_project_folder_name\artisan schedule:run

1.Create A Batch File And Paste The Above Command.
2. Replace path with your localdrive and project name
like
E:\xampp\php\php.exe E:\xampp\htdocs\cronjob\artisan schedule:run

3. Save the batch file and cofigure it with AlwaysUp software.

How To Schedule Task In Server or Cpanel

1. Goto corn job and create a new command like 

cd location_file && php artisan schedule:run >>/dev/null 2>&1

Here you have to change location_file to your sever address example:

cd /home/hrmahidc/public_html && php artisan schedule:run >>/dev/null 2>&1

