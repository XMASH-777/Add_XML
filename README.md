# Add_XML background
![Screenshot_2026-02-26-14-07-47-16_7926f7171cab5ff3722cb14d3fb8a90e](https://github.com/user-attachments/assets/369aee67-a6c8-45de-947a-368614d19b83)

**ຖ້າແອັດຫລາຍຂໍ້ຄວາມຢາກໃຫ້ພື້ນຫລັງ ເປັນຫນື່ງດຽວຕ້ອງແອັດອັນນີ້ຢູ່ກ່ອນສະເຫມິ ແລະ ເວັ້ນໄລຍະຫ່າງຈາກເທິງແລະລຸ່ມ**
**ເຊັ່ນ**
```
<LinearLayout
    android:orientation="vertical"
    android:background="#ff161b22"
    android:padding="20dp"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_marginBottom="20dp">
```
**ຕ້ອງປິດໃຫ້ຕົງເສັ້ນເທິງລະຫວ່າງ**
**<linearlayout ແລະ </linearlayout>**

# ຢາກໃຫ້ຂໍ້ຄວາມຢູ່ກາງແລະເວັນລະຍະຫ່າງຈາກຂອບ
![Screenshot_2026-02-26-14-33-19-66_7926f7171cab5ff3722cb14d3fb8a90e](https://github.com/user-attachments/assets/0db2e1f7-d55b-4401-86a6-faed33c23633)

```
android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="12.0dip"
```

# ເຮັດແບບນີ້ເລືອນຊ້າຍຂວາ
![Screenshot_2026-02-26-15-41-10-78_a947b7d7499942e80a1b2df958c9383c](https://github.com/user-attachments/assets/d7892cf3-bcc7-4594-9e47-22e9fbbd848d)

```
<LinearLayout
                android:orientation="vertical"
                android:background="#ff161b22"
                android:padding="20.0dip"
                android:layout_width="fill_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="20.0dip">
                <TextView
                    android:textSize="16.0sp"
                    android:textStyle="bold"
                    android:textColor="#ff58a6ff"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="10.0dip"
                    android:text=" LEVEL "
                    android:fontFamily="@font/Road_Rage" />
                <SeekBar
                    android:id="@id/lag_seekbar"
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:max="200" />
                <TextView
                    android:textColor="#ffffffff"
                    android:id="@id/lag_value"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="6.0dip"
                    android:text="0 ms" />
            </LinearLayout>
```
# ກຳນົດພື້ນຫລັງສີ
![Screenshot_2026-02-26-15-48-07-24_7926f7171cab5ff3722cb14d3fb8a90e](https://github.com/user-attachments/assets/621d0451-607a-4b33-a914-9d93e9cc3b34)

**ອະທິບາຍ**
```
<?xml version="1.0" encoding="utf-8"?>
<shape
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:aapt="http://schemas.android.com/aapt"
    xmlns:app="http://schemas.android.com/apk/res-auto">
    <gradient
        android:startColor="@color/b1"
        android:endColor="@color/b2"
        android:angle="0.0" />
    <corners
        android:radius="16.0dip" />
</shape>
```
**ໂຕນີ້**
android:angle="0.0" />
ค่า
ทิศทางไล่สี
0
ซ้าย ➜ ขวา
90
ล่าง ➜ บน
180
ขวา ➜ ซ้าย
270
บน ➜ ล่าง

