# LaraGigs App

LaraGigs is an application for listing Laravel gigs/jobs.
![LaraGigs Screenshot](/public/images/screen.png)

## Usage

### Database Setup

This app uses MySQL. Make sure to configure your database settings in the `.env` file.

### Migrations

To create all the necessary tables and columns, run the following command:
php artisan migrate

### Seeding The Database

To add dummy listings with a single user, run the following command:
php artisan db:seed

### File Uploading

When uploading listing files, they are stored in "storage/app/public". Create a symlink with the following command to make them publicly accessible:
php artisan storage:link

### Running The App

Upload the files to your document root, Valet folder, or run the following command:
php artisan serve
Visit http://localhost:8000 in your browser to access the LaraGigs app.
