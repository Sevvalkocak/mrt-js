# mrt-js

const userName = ["mrtbskc"]
const password = "123456"
const age = 31;
const school = "university";
const job = "software engineer";
const isStudent = false;
const isBoss = true;
const isMarried = false;
const isPartner = true;
const isChild = false;

if (userName == "mrtbskc") {
    console.log("Hoşgeldin Murat");
} else {
    console.log("Kullanıcı bulunamadı! Tekrar deneyiniz.");
}

if (password == "123456") {
    console.log("Başarıyla giriş yaptınız.");
} else {
    console.log("Hatalı şifre girdiniz!");
}

if (age >= 18) {
    console.log("Platformu kullanabilirsiniz.");
} else {
    console.log("18 yaşından küçükler platforma üye olamaz");
}

if (school <= "high school") {
    console.log("18 yaşından küçükler platforma üye olamaz");
} else {
    console.log("Platformu kullanabilirsiniz.");
}

if (job == "software engineer") {
    console.log("Yeni iş fikirlerimiz için bizimle iletişime geçebilirsiniz.");
} else {
    console.log("Yazılımcı olmak ister misiniz?");
}

if (isStudent == true) {
    console.log("Yazılımcı olmak için üniversiteni bizim seçmemizi ister misiniz?");
} else {
    console.log("Hangi mesleği yapmaktasın?");
}

if (isBoss == false) {
    console.log("Bizimle çalışmak ister misin?");
} else (
    console.log("Nerede çalışmaktasın? Eğer işinden memnun değilsen sizinle iletişime geçelim.")
)

if (isStudent == false) {
    if (isBoss == true) {
        console.log("Ekibimizin bir parçası olmak ister misin?");
    } else {
        console.log("Nasıl yazılımcı olacağını öğrenmek istersen, formu doldur");
    }
}

if (isStudent == true) {
    if (isBoss == false) {
        console.log("Nasıl yazılımcı olacağını öğrenmek istersen, formu doldur");
    }
} else {
    console.log("Ekibimizin bir parçası olmak ister misin?");
}

if (isMarried) {
    console.log("Kaç yıllık evlisin?");
} else {
    console.log("Sevgilin var mı?");
}

if (isPartner) {
    console.log("Evlenmeyi düşünüyor musun?");
} else {
    console.log("Hemen kendine kova burcu, kıvırcık saçlı ve biraz agresif Şevval adında bir hanım bul. Acilen evlen. Kuşlardan haber getirdim o seni çok seviyor...");
}

if (isPartner == false){
    console.log("Evlenmeyi düşünüyor musun?");
} else {
    console.log("Hemen kendine kova burcu, kıvırcık saçlı ve biraz agresif Şevval adında bir hanım bul. Acilen evlen. Kuşlardan haber getirdim o seni çok seviyor...");
}

if (isChild == false){
    console.log("Çocuklar çok sevimli ama önce evlenmelisin!");
}else{
    console.log("Geçmiş olsun...");
}
