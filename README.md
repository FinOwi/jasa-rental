# jasa-rental

Platform website rental outdoor — [jasa-rental.my.id](https://jasa-rental.my.id)

Satu domain induk, banyak toko: tiap usaha rental tampil di
`jasa-rental.my.id/<slug-toko>` dengan katalog, booking, dan panelnya masing-masing
(backend bersama Supabase, data terpisah per tenant).

Rumah deploy ini dikelola FinOwi Id. Konten situs diunggah bertahap lewat
skrip `push_platform.py`.
