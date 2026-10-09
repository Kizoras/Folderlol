# Folderlol

Remove-Item -Recurse -Force vendor

<br> php artisan migrate

<br> composer install

<br> ini bagian seeder
<br> php artisan db:seed --class=SiswaSeeder /KelasSeeder /WalasSeeder
<br> pake yang dibawah kalo di atas tidak bisa
<br> composer install --no-security-blocking
<br> composer install --no-dev --prefer-dist

<br> public function walas()
    {
        return $this->hasMany(Walas::class, 'kelas_id');
    }
