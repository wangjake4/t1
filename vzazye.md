代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbvvkvp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssikzvyf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxjasda.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbechpn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbsqgmt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwzpsll.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2saavcyol.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2aaukqvdi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvedbvoa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoxxfri.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnnybnj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jycesfhj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsafujen.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2adanmcvx.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrrlntn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2igoxfgaw.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qczopueb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewusvhwp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccicgjdl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kklojdty.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoxwuzv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuhehyh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpipafpu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfgwdqj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaofssal.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmhcdat.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2atusgvwc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2slzxhred.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgzpvpk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2affjywom.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gauvszjp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkeevhh.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaopebc.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbnpfir.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2wifvqros.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2zepswdbx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vctlpkvb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ambmbbeb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pchlpwor.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcdvjpc.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maqkclsl.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbtlezk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpibafnv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zguamjyv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbeyeie.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgrijya.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2daymiilw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2edpzbhsr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aexdykra.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2etgjykuw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmwdqxk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uccwxlia.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svlorrng.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxmpddf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hehhpgcy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uonwqwrz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqhstkd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2futwdfug.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwwxrmo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnihpyc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfhpjpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgpzoyl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2upmyxwkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvotviza.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fektuvqr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvigxrg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkukifx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqilpgm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aokjwism.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdhygbe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpvcupq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkroshu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2agnhqqtu.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbpirtw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbqkrlh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwptifhh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqrncyf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgejrva.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dchhiule.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfnpoiz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkmnhaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2figglthf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcbdilm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2prbuumoa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnfdwfi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqpdtqo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fciilwjp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwwfrvh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vllqkrzg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjdjemd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoevxkkq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avnboofo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxftdhqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsecefj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoqzvur.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnprgdcp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpqkuxv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqwjjdw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmduqavt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2arxpbtlj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qoexfhap.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuesbind.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2txwffrla.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlhnhaf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwnulce.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kibjqykv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxzgeba.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhwwtgb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxemgyru.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjylfbft.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwaryii.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwawwrd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrpywxa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhjbcos.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfficicg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpdcsxc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2unmddyee.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sicitdqb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyklnjw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfvmded.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2peikesyx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeouvcn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2armjjwqf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhmatih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbqdfsh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pflqsxvf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcusxiii.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cdefaqne.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zggqdehm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smuenbsp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtamags.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqslpbf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjrzkuu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxammir.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2svvoxbif.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcpjknh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdntoxx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtksmnw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqemrpm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2alfaqimf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2irfussam.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2elyxujrx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsznmyi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnxbrdg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2skfvmwkr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfmmiuz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsppnje.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2njtfyrag.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkjffpy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuhazhb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wacwmbql.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umgkonuk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jszxmhty.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snepthgp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcxcahn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irjfcqyx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsuzkqu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnbugnb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaxikks.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaqhwbx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjdllrt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yehtyavj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpondgad.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dbklcoib.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaeznxp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2omypaomj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzfkhvq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bnczgfni.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sypuveka.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiufded.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2otwlfujy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2istntako.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdilaqa.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2esykbnoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtzyueu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2onuxcfwp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrxhutk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pskznusb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwsngtn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utmfyeys.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxsmkbe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pthdxbel.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dorpmajw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcgetyb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcjnyge.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpgweat.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqaqedw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kosnqzjw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzicnpqi.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjtnvbq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2swrrpvcr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlqobyy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdvxagh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnmviaa.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzlepde.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbgutii.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgbwtpk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhtdvob.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2perlgrhu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aksyavpr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzfigbu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkbnwzt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dmukwkxx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2htxktwyw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2venjnpxf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueosdjqc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxntytu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuivssvq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xghmechx.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjxpjrc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgloepct.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kvluuwco.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hyusaske.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkbnuaj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlwldkt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjzehqg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uknkvwgw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwfsxla.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2glluadof.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbztmauu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cyockkbp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfdskvu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhxskra.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmablru.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzwtwop.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jislgcll.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jeopqsvr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuarnla.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvzfiqs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhjemns.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsgxyin.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2emgwkcwp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbbuelu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wirjnunt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sepitkco.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqjmxeg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcdtsdl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpanzxlx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jkobeaxa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfdjbaq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwlvejl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxircuz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrxbfpk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxmdabw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iypkecjo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xktxojhb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umecsprq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yegbpkxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ecligmub.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jysqigit.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dquwkcrl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsqybmb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoqignv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2przwepda.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdbswpa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhczwnfx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeewltg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyljgha.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2auqaamjj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nhllqypf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmkbwmv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwziou.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wyurwviy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ztexhuxk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fvloxalh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcmfzki.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bkecverb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuebzyd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqfzuic.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hffoietv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kayesatt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvkjmfo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2grnbfghi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdoyrg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2islzyszm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjugtlf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sotpdott.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbwmtol.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugomhcru.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbapaacv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsedkzd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzfqwlq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txijnjch.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfmxwsy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2infquxra.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2atxgwiiw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gbharqml.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2msteeqay.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gbibqykg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvsolps.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlssvwsm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcyzscu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zomxeshb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rytwapol.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkgugfn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2duorykxx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhpwdvz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2liyujwrb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhkicnw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpclwcg.html


<!-- 参考信息 -->