# QA Portfolio — Manual & API Testing

Kumpulan dokumen pengujian saya sebagai calon QA Engineer. Setiap dokumen dikerjakan dari awal sampai akhir: analisis, perancangan test, eksekusi, dan pelaporan temuan.

Repo automation saya ada di terpisah: [QA-Automation-Practice](https://github.com/SyaifaTurrohman/QA-Automation-Practice) (Playwright, Page Object Model).

## Isi Repo

| # | Dokumen | Yang dikerjakan | Temuan utama |
|---|---|---|---|
| 1 | [Bug Report — SauceDemo](01-saucedemo-bug-report/Bug-Report-SauceDemo.pdf) | Exploratory testing pada akun `problem_user`, dibandingkan dengan `standard_user` sebagai baseline | 3 bug valid, masing-masing dengan alasan severity dan priority |
| 2 | [Test Plan dan API Testing](02-test-plan-dan-api-testing/Test-Plan-dan-API-Testing.pdf) | Test plan SauceDemo, contoh test case, dan pengujian API (GET dan POST) dengan Postman, termasuk skenario negatif | Endpoint create user menerima body kosong tanpa validasi (201 Created), serta catatan format error response |
| 3 | [Test Summary Report — Job Application Tracker](03-job-tracker-test-summary/Test-Summary-Report-JobTracker.pdf) | Pengujian end-to-end pada project fullstack pribadi: requirement analysis, 16 skenario transisi status, eksekusi manual, otomasi UI dan API dengan Playwright, serta verifikasi lewat UI, Network tab, API, dan query SQL | 3 bug: reminder dapat disimpan tanpa tanggal (Major), dan dua kasus input tidak valid yang dijawab 500 oleh API (Minor); cascade delete terverifikasi benar |  

## Keterampilan yang Ditunjukkan

- Exploratory testing dengan teknik pembanding (baseline vs target)
- Penulisan bug report: steps to reproduce, expected vs actual, severity dan priority beserta alasannya
- Penyusunan test plan dan test case
- Perancangan skenario dengan test coverage matrix
- API testing dengan Postman: validasi response, status code, dan skenario negatif
- Verifikasi data langsung di database dengan SQL, bukan hanya dari tampilan UI
- Pelaporan hasil dalam bentuk test summary report
- Otomasi test UI dan API dengan Playwright (repo terpisah: QA-Automation-Practice)

## Penulis

[Syaifa Turrohman] — [https://www.linkedin.com/in/syaifa-turrohman/]
