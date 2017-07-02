---
layout: page
permalink: /konfirmasi-pembayaran/
---
<div class="product-big-title-area">
   <div class="container">
      <div class="row">
         <div class="col-md-12">
            <div class="product-bit-title text-center">
               <h2>Konfirmasi Pembayaran</h2>
            </div>
         </div>
      </div>
   </div>
</div>
<div class="single-product-area">
   <div class="zigzag-bottom"></div>
   <div class="container">
      <div class="row">
         <div class="col-md-6 text-center">
            <img src="img/transfer.png" width="90%" alt="" style="margin-bottom:20px;max-width:400px">
         </div>
         <div class="col-md-6">
            <div class="brand-wrapper text-md">
               <h3 class="text-center">Setelah pembayaran, konfirmasi disini ya!</h3>
               <p class="text-center">Data berikut digunakan untuk mengkonfirmasi pembayaran, dan tidak akan kami publikasikan demi keamanan data anda.</p>
               <div class="sparator"></div>
               <form method="post" action="http://shop.keluargacactus.com/api/konfirmasi_pembayaran">
                  <table cellspacing="0" class="shop_table cart konfirmasi">
                     <tbody>
                        <!-- -->
                        <tr>
                           <td class="td-judul">Nama Lengkap</td>
                           <td class="td-isi">
                              <input type="text"  name="nama_lengkap" value="" placeholder="Nama Lengkap" class="form-control"/>
                           </td>
                        </tr>
                        <!-- -->
                        <tr>
                           <td class="td-judul">Nama Bank</td>
                           <td class="td-isi">
                              <select name="bank" class="form-control">
                                 <option value="BNI46">BNI 46</option>
                                 <option value="BRI">BRI</option>
                                 <option value="BCA">BCA</option>
                                 <option value="CIMB">CIMB</option>
                                 <option value="MANDIRI">MANDIRI</option>
                                 <option value="LAINYA">LAINYA</option>
                              </select>
                              <label class="info">Pilih bank anda, jika tidak ada pilih lainya.</label>
                           </td>
                        </tr>
                        <!-- -->
                        <tr>
                           <td class="td-judul">Nominal Pembayaran</td>
                           <td class="td-isi">
                              <input type="text"  name="nominal_pembayaran" value="" placeholder="Rp." class="form-control"/>
                              <label class="info">Berapa besar nominal yang anda kirim?</label>
                           </td>
                        </tr>
                        <!-- -->
                        <tr>
                           <td class="td-judul">Bukti Pembayaran</td>
                           <td class="td-isi">
                              <input type="file"  name="bukti" class="form-control"/>
                              <label class="info">Kirimkan foto bukti pembayaran disini</label>
                           </td>
                        </tr>
                        <!-- -->
                        <tr>
                           <td class="td-judul">Selesaikan Captcha</td>
                           <td class="td-isi">
                           </td>
                        </tr>
                        <!-- -->
                        <tr>
                           <td class="td-judul">&nbsp;</td>
                           <td class="td-isi">
                              <button type="submit"  id="cekbutton">Kirim</button>    
                           </td>
                        </tr>
                     </tbody>
                  </table>
               </form>
            </div>
         </div>
      </div>
   </div>
</div>
<!-- End brands area -->
