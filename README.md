# 5.-hafta ödev
import { useState } from 'react'
import reactLogo from './assets/react.svg'
import viteLogo from '/vite.svg'
import './App.css'

function App() {
  const [count, setCount] = useState(0)

  return (
    <>
      <div>
        <h1><Biyografim></Biyografim></h1>
        <div>
          <h2>Kübra</h2>
          <p>Kavuk</p>
        </div>
        <div>
          <h2>Doğum Tarihi:21.01.1996</h2>
          <p>Doğum Yeri: Çankırı</p>
          <hr></hr>
        </div>
        <div>
          <h2>Eğitimlerim</h2>
          <p>Önlisans: Lojistik, Adalet </p>
          <p>Lisans: İşletme</p>
        </div>
        <hr></hr>
        <div>
          <h2>Meslekler</h2>
          <p>Yazılım Geliştirici</p>
          <p>Girişimci</p>
          <p>İnfluencer</p>
        </div>
        <hr></hr>
        <div>
          <h2>Hobiler</h2>
          <p>Piyano çalmak, yüzmek, tenis ve basketbol oynamak, kitap okumak, resim yapmak.</p>
        </div>
        <hr></hr>
        <div>
          <h2>Kendimi Tanıtma</h2>
          <p>ismim Kübra. 27 yaşındayım ve aslında hep istediğim mesleğe başlamak için adım atmış bulunuyorum.
            Eski bir profesyonel basketbolcuyum. Aktif olarak spor ve sanatla ilgileniyorum. 
            İyi seviye de ingilizce ve başlangıç seviyesinde rusca biliyorum. 
            Bir mağazanın depo sorumlusu olarak bir yıl kadar çalıştım ama göre olmadığını kendimi iyi geliştiremediğimi düşündüğüm için işten ayrıldım.
            Şu an da kendi işimi kurma serüvenim devam ederken aynı zaman da yazılım eğitimi alıyorum.
          </p>
        </div>
        <hr></hr>
      </div>
    </>
  )
}
