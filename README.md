# Pemprogramanmobile

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/judul"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="80dp"

        android:fontFamily="@font/vampiro_one"
        android:text="Selamat Datang "
        android:textAlignment="center"
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="34sp" />

    <TextView
        android:id="@+id/judul2"
        android:layout_width="match_parent"
        android:layout_height="37dp"
        android:layout_below="@id/judul"

        android:layout_alignParentEnd="true"
        android:layout_marginTop="-1dp"
        android:layout_marginEnd="0dp"
        android:fontFamily="@font/itim"
        android:text=" Document Apa yang anda butuhkan ? "
        android:textAlignment="center"
        android:textColor="#451212"
        android:textColorLink="#C0392B"
        android:textSize="20sp" />

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="420dp"
        android:layout_height="328dp"
        android:layout_below="@id/judul2"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="89dp"
        android:src="@drawable/gambar1" />

    <Button
        android:id="@+id/btn1"
        android:layout_width="wrap_content"
        android:layout_height="66dp"
        android:layout_below="@id/gambar1"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="55dp"
        android:width="250dp"
        android:background="@drawable/button_shape"
        android:fontFamily="@font/inria_serif_light"
        android:text="LOGIN"
        android:textColor="#FFF9F9"
        android:textSize="32sp"
        />

    <Button
        android:id="@+id/btn2"
        android:layout_width="wrap_content"
        android:layout_height="66dp"
        android:layout_below="@id/btn1"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="55dp"
        android:width="250dp"
        android:background="@drawable/button_shape2"
        android:fontFamily="@font/inria_serif_light"
        android:text="SIGN UP"
        android:textColor="#9C1D1D"
        android:textSize="32sp" />

</RelativeLayout>
<img width="724" alt="image" src="https://user-images.githubusercontent.com/101643559/236656741-957fccec-3e5b-466c-aced-47ac72bf47b5.png">

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Login2Activity">


    <TextView
        android:id="@+id/judul"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="80dp"

        android:fontFamily="@font/inria_serif_light"
        android:text="LOGIN "
        android:textAlignment="center"
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="34sp" />

    <TextView
        android:id="@+id/judul2"
        android:layout_width="match_parent"
        android:layout_height="37dp"
        android:layout_below="@id/judul"

        android:layout_alignParentEnd="true"
        android:layout_marginTop="-1dp"
        android:layout_marginEnd="0dp"
        android:fontFamily="@font/inria_serif_light"
        android:text=" Sistem Document Control "
        android:textAlignment="center"
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="20sp" />

    <ImageView
        android:id="@+id/gambar1"
        android:layout_width="286dp"
        android:layout_height="230dp"
        android:layout_below="@id/judul2"
        android:layout_marginTop="29dp"
        android:src="@drawable/gambar2"
        android:layout_centerHorizontal="true"/>

    <ImageView
        android:id="@+id/gambar2"
        android:layout_width="286dp"
        android:layout_height="230dp"
        android:layout_below="@id/gambar1"
        android:layout_marginTop="-79dp"
        android:src="@drawable/component3"
        android:layout_centerHorizontal="true"/>

    <ImageView
        android:id="@+id/gambar3"
        android:layout_width="286dp"
        android:layout_height="230dp"
        android:layout_below="@id/gambar2"
        android:layout_marginTop="-184dp"
        android:src="@drawable/component4"
        android:layout_centerHorizontal="true"/>

    <Button
        android:id="@+id/btn1"
        android:layout_width="wrap_content"
        android:layout_height="66dp"
        android:layout_below="@id/gambar3"
        android:layout_marginTop="-36dp"
        android:width="250dp"
        android:background="@drawable/button_shape"
        android:fontFamily="@font/inria_serif_light"
        android:text="LOGIN"
        android:textColor="#FFF9F9"
        android:textSize="32sp"
        android:layout_centerHorizontal="true"/>
</RelativeLayout>

<img width="722" alt="image" src="https://user-images.githubusercontent.com/101643559/236656755-22c533c3-8ccf-41fb-911d-211f2f1ae520.png">


<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".BerandaActivity">

    <Button
        android:id="@+id/button1"
        android:layout_width="303dp"
        android:layout_height="wrap_content"
        android:layout_marginLeft="15dp"
        android:layout_marginTop="30dp"
        android:background="@drawable/button_shape2"
        android:text="Cari Doc Disini"
        android:fontFamily="@font/inria_serif_light"
        />

    <SearchView
        android:layout_width="72dp"
        android:layout_height="101dp"
        android:layout_marginLeft="320dp" />

    <TextView
        android:id="@+id/judul"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="80dp"
        android:fontFamily="@font/inika_bold"
        android:text="Berita Tentang ISO "
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="25sp"
        android:layout_marginLeft="15sp"/>

    <ImageView
        android:id="@+id/gambar"
        android:layout_width="131dp"
        android:layout_height="wrap_content"
        android:layout_below="@id/judul"
        android:layout_marginTop="15dp"
        android:src="@drawable/slogan"
        android:layout_marginLeft="15sp"/>
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/judul1"
        android:layout_marginLeft="140sp"
        android:text="Daftar Juara Quality Slogan"
        android:layout_marginTop="190dp"
        android:textColor="#AD6464"
        android:fontFamily="@font/inika_bold" />

    <TextView
        android:id="@+id/judul1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="140sp"
        android:layout_marginTop="210dp"
        android:fontFamily="@font/inika_bold"
        android:text="Daftar Juara Quality Slogan tahun 2022 yaitu Rahmi"
        android:textColor="#090909"
        android:textSize="10dp" />

    <ImageView
        android:id="@+id/gambar2"
        android:layout_width="131dp"
        android:layout_height="wrap_content"
        android:layout_below="@id/judul"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="140dp"
        android:src="@drawable/slogan" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/judul2"
        android:layout_marginLeft="140sp"
        android:text="Daftar Juara Quality Slogan"
        android:layout_marginTop="320dp"
        android:textColor="#AD6464"
        android:fontFamily="@font/inika_bold" />

    <TextView
        android:id="@+id/judul1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="140sp"
        android:layout_marginTop="340dp"
        android:fontFamily="@font/inika_bold"
        android:text="Daftar Juara Quality Slogan tahun 2022 yaitu Rahmi"
        android:textColor="#090909"
        android:textSize="10dp" />

    <ImageView
        android:id="@+id/gambar3"
        android:layout_width="131dp"
        android:layout_height="wrap_content"
        android:layout_below="@id/judul"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="262dp"
        android:src="@drawable/slogan" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/judul3"
        android:layout_marginLeft="140sp"
        android:text="Daftar Juara Quality Slogan"
        android:layout_marginTop="430dp"
        android:textColor="#AD6464"
        android:fontFamily="@font/inika_bold" />

    <TextView
        android:id="@+id/judul1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="140sp"
        android:layout_marginTop="450dp"
        android:fontFamily="@font/inika_bold"
        android:text="Daftar Juara Quality Slogan tahun 2022 yaitu Rahmi"
        android:textColor="#090909"
        android:textSize="10dp" />

    <TextView
        android:id="@+id/judul4"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="480dp"
        android:fontFamily="@font/inika_bold"
        android:text="Document ISO "
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="22sp" />

    <ImageView
        android:id="@+id/gambar4"
        android:layout_width="241dp"
        android:layout_height="125dp"
        android:layout_below="@id/judul"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="397dp"
        android:src="@drawable/rectangle" />

    <ImageView
        android:id="@+id/gambar5"
        android:layout_width="183dp"
        android:layout_height="77dp"
        android:layout_below="@id/judul"
        android:layout_marginLeft="80sp"
        android:layout_marginTop="397dp"
        android:src="@drawable/sometric" />

    <TextView
        android:id="@+id/judul5"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="25sp"
        android:layout_marginTop="580dp"
        android:fontFamily="@font/inika_bold"
        android:text="Level 1 "
        android:textColor="#000000"
        android:textColorLink="#C0392B"
        android:textSize="18sp" />
    <TextView
        android:id="@+id/judul6"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="25sp"
        android:layout_marginTop="600dp"
        android:fontFamily="@font/inika_bold"
        android:text="21 Document "
        android:textColor="#000000"
        android:textColorLink="#C0392B"
        android:textSize="13sp" />

    <ImageView
        android:id="@+id/gambar6"
        android:layout_width="71dp"
        android:layout_height="62dp"
        android:layout_below="@id/judul"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="530dp"
        android:src="@drawable/home" />
    <ImageView
        android:id="@+id/gambar7"
        android:layout_width="71dp"
        android:layout_height="62dp"
        android:layout_below="@id/judul"
        android:layout_marginLeft="340sp"
        android:layout_marginTop="530dp"
        android:src="@drawable/Profile" />

</RelativeLayout>

<img width="720" alt="image" src="https://user-images.githubusercontent.com/101643559/236656778-b1a67fe0-3e62-4add-a27d-420c0347bbaf.png">

?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".ProfileActivity2">

    <ImageView
        android:id="@+id/gambar"
        android:layout_width="71dp"
        android:layout_height="62dp"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="15dp"
        android:src="@drawable/Profile" />

    <TextView
        android:id="@+id/judul"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="100sp"
        android:layout_marginTop="27dp"
        android:fontFamily="@font/inika_bold"
        android:text="My Profile "
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="25sp" />
    <TextView
        android:id="@+id/judul2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="25sp"
        android:layout_marginTop="100dp"
        android:fontFamily="@font/inika_bold"
        android:text="Nama "
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="22sp" />

    <ImageView
        android:id="@+id/gambar2"
        android:layout_width="367dp"
        android:layout_height="300dp"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="15dp"
        android:src="@drawable/line" />
    <TextView
        android:id="@+id/judul3"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="25sp"
        android:layout_marginTop="180dp"
        android:fontFamily="@font/inika_bold"
        android:text="NIK "
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="22sp" />

    <ImageView
        android:id="@+id/gambar3"
        android:layout_width="367dp"
        android:layout_height="450dp"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="15dp"
        android:src="@drawable/line" />
    <TextView
        android:id="@+id/judul4"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="25sp"
        android:layout_marginTop="250dp"
        android:fontFamily="@font/inika_bold"
        android:text="Unit "
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="22sp" />

    <ImageView
        android:id="@+id/gambar4"
        android:layout_width="367dp"
        android:layout_height="590dp"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="15dp"
        android:src="@drawable/line" />
    <TextView
        android:id="@+id/judul5"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="25sp"
        android:layout_marginTop="330dp"
        android:fontFamily="@font/inika_bold"
        android:text="Section "
        android:textColor="#C0392B"
        android:textColorLink="#C0392B"
        android:textSize="22sp" />

    <ImageView
        android:id="@+id/gambar5"
        android:layout_width="367dp"
        android:layout_height="880dp"
        android:layout_marginLeft="15sp"
        android:layout_marginTop="15dp"
        android:src="@drawable/line" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/button"
        android:layout_marginLeft="250dp"
        android:layout_marginTop="400dp"
        android:background="@color/primary"
        android:text="UBAH"/>
</RelativeLayout>

<img width="731" alt="image" src="https://user-images.githubusercontent.com/101643559/236656804-180df289-9e95-4deb-9591-a2257a34cbb5.png">

