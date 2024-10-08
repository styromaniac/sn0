![sn0](https://github.com/user-attachments/assets/efc82e94-d5e0-4642-b9c1-fecd420cd35a)

Sn0 is a Python program that helps to download and update websites. It does this by downloading the website's HTML content and all the files referenced in it. The program also verifies the checksums of the downloaded files to ensure they are not corrupted. It also checks if there are any new files on the website and downloads them. Additionally, it updates the links in the HTML content to match the local file system. The program has options to create backups of the downloaded files and to remove files from subfolders that are not referenced in the HTML content.

Sn0 depends on a PHP script that provides the current SHA3-512sum with the file path for each file to download/update on a destination computing device in the text file known as sn0.txt. Any newer, more secure hashing algorithm can be very simply replaced by a drop-in solution as long as there aren't external dependencies.

## Here are examples from a sn0.txt file:
```
edc952fe21b3c6f08c93b0901b321ccd24f3d84e1c5f95091541afd4d80608bf48554508a1e4a5a6e4fdc0f08eb3671dacdb3650f6a14e52d685d48a54780528 *dep/BlueBat.svg
a05f98b2277032057b50e986eacc00e16908358374c725549aec011626d9999ee7dcc16559c4a206b8fce8855cb0b1cb01629f4f61a5ab2db54ca03640682570 *dep/Copyright.js
93dc1b767395ea8fbeb4a45448ee9c5fe7eaecf0bfb213c8bc24b2f59ec0a00b1e84d28cac225d487c4e5d237baeb82e027dc084c1f4ebdaf918a1ea399f2365 *dep/Fullscreen.js
606c9482a22ce35f8c00fb69c6f5a22976451f45acd343f541d735dc8389aabf13a16c18f93716551bec5c0e3d2701c6f888be651841dca048e6ff31b2c8002b *dep/Kave.css
7815133ff2d1809b397e08b975f043fa705a5f06ff96962c6579906271472e578c34f31d60db330a79fd98da7036ba4203f34442c76458d1b4f813c771806218 *dep/KaveTorrent.js
dd1fda28e46ba7ba5a7e60b2081045750f8fc6bef53cf260a70ead4ada42b94333e03d0bd303d306051cd34b2c3806945568c834ed70410596236d0da9399c6d *dep/Lightbox.js
debdf4a41433dbc62d6587cfe46ad58ede3cee39e317e4b5ab6fbb9ddd2c0b8887477541f065c6310cc7d4019cd95975cf38cdc50a4a960bee91123057c077c3 *dep/MIT.svg
235e6574d4167dd0db6458414c30afdb486c5c3bc42cbb0e22bc25fdbde65ce7d48cf1a94718af01153ddb597f46e17cf54251a3caf35014f952e74a0e72da8a *dep/Styro.webp
5f37b321889854bb51dbae06394070351d6149b4c3ed386777f582d7d6e6c565c13951c66b3e28968069d859c3f5a51d196af366c77741eb93106afa82c422bb *dep/Viewplayer.js
2fad66050344cd45d65a50b2d45e2f65d3188b6d496dacb08b856645ccf98cc21503194ef233cd9ee2cdcd7c52ad2eb0167a0af37672a5088c6b6362ccc08743 *dep/favicon.png
c7fe12ad2e6741d66341ee52c92cff9d3cb32d6975d2d7d356fe18b934334f08c58cc9f0ca8d86a1c72fd23933b70038b56248795a55fa78e0a8472f2bd49009 *dep/favicon.webp
956edbe7dba51d78106e8eda10cd8fcd5cee47666c63ed4698e771b0235b093715d0c9ab5b564f0f90f06331639414e0eec3ce715f114f6a2423e1cf6046c9d9 *dep/index.jpg
fe6b87682474f466b47c30035aebbb8ba661cf31d8f2fae7a717c91d72d46d93fa7b4148a9d7407c4a7c03f90252c8528da7e9af2890b3da5a9585b71b0e55f2 *dep/manifest.json
3937a89d579fa548dfeae98066f1bb4ecbf946d1317781e530da70e2caacc292102365cf524ad2c575a440960ffcbf292e403ef65aeb177331a4a9d1f4d263e7 *OpenCamera/20220313_190100.webp
d11c3549079bc82ecd6ebd7afa42d2a712301dc1bab87018705ef5d5b345e58d09a78d93b884d088bc29fc6eb0a947a9471510157dae9d8a22bebda9670de4f9 *OpenCamera/20220331_150854.webp
69426883d96241bf64124f37969620e5fafc0b3e812f47ae7bbd69730a39a5d91108f8d9adfe374aa74d27debbd6a989e535a268e78d67a238b5ea66ff92b380 *OpenCamera/20220806_183730.webp
b9f0b257d7b622706a8e2ecbcee6765bfa0f508bfd508fe9a63124e3369b08703e820167a98064b2bbb567f859753e568d2c179a0bff1f657b869ee1df26047a *OpenCamera/20220815_123555.webp
9b151ccf0e5a421a44d853749ded6d52eb19e63a856a1ebcd3fd52c6d7c2c8dea57b63652acf4d55d6225651a69dad93c861d5acb0120d4a0c797718928390b6 *OpenCamera/20220815_123732.webp
3388318e8a5a4388f0dc2d477dc87eb562dd8e20396b293f13579144bddea31e927c3318e25a61a736dd307d9962c1a255dd26e92202c0bc8ae34218bbb17d9a *OpenCamera/20221111_115506.webp
b87b29dc5c7def42e6d7dc27641d4521e60a06ff74eaf3527a3acb98de4a3ad2025c1e170b3b50c7229f7104156d85f52065fa2caf1906a6bf767cb41ce70129 *OpenCamera/20221111_115542.webp
1771748b836f20d8174a2bde74fbbf6b39173e6714de2b58cb68f8c7018e23943c05406833aec8c4108bf22f30a8c2b53163ef2fa67bb136e9c36b5dfe4e3f12 *OpenCamera/20221111_115723.webp
4c20313040ae481bee85ff6cb46b7f5ed2fc1c47075dd14cb94c5ebf42d21a09530caea4fdcc404c757d8c1a6fb6ede3a2e3b345edcd240a9add108ea2d6c21d *OpenCamera/Resized_IMG_20190221_132142_230495988898008.webp
1b5449aa125fc6b94e2bfe234fd64e7cf5cc3eb58bdfee6bb1a82ef1b17a392d4aa1bf3af2c7cd34f19f9e41e41e7569e15a56f36eb7f071180f244fd73f93ca *OpenCamera/example.mp4
044185a9e6ceef9a751fa85efd445eb8b7353e786918650e6b7624c377c2e7e95b3f4de76e2cab87c2f7248da2b1f29f386681ed7c4f74a6f9fefec1c6513492 *OpenCamera/example.webp

```

## Usage:
```
sn0 <destination_folder> <source_URL>
```
or...
```
sn0 <source_URL> <destination_folder>
```

If you want older copies to save as backup copies, then use --bank.
```
sn0 --bank <destination_folder> <source_URL>
```

If you want files that were deleted from the site to be deleted locally, then use --melt
```
sn0 --melt <destination_folder> <source_URL>
```

--bank and --melt can be used at the same time in any order.

If you want another feature, please [create an issue for it.](https://github.com/styromaniac/sn0/issues/new)
