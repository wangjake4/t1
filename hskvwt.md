代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpqosbp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbzrpdv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2umriguet.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvslvjqj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsruhzd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaiaijf.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jgecnfkg.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2coyiwxot.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmxfvea.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqapuga.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2mumxdlwh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gngbxedk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2orxendqq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2psubbzwr.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnlshxx.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeejnmv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2heefwapm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2prypnaes.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrjfldv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyepqkcx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhalvapm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnmaspa.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2tjauwdst.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2fatxgosl.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oovidoes.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2luxielhj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2icvbxief.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkzbeqg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpfcaro.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fznwsagb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvenfjv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgkuzwj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szlfepsn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxzncrf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2adhjpshr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvdzqqj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpgzzub.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxyaqfn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzozjwut.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2afebcthz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xoasefmo.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkooiaw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2nltvlghy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2npzcxljb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zcikbmud.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgqzltr.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfzlkwo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2leilpqpw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coufnjgq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2rlitkjkw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtncilx.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2heblujbt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqppnuz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrngbba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zvleaffq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlixbvly.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ophsldgh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmtabpd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2whikkkrk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lcilcjkr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzyddpl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fksuiwmu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzzmrip.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2emnfddgh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdxstwx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fogosiga.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvuvets.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hquqebyn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzktzpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fneqdodz.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqkdozi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgajjknq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adjdelng.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbrzuqd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjxgeft.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2awyrxuxm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsawhdwj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phrlqqci.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2norbfpmk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjordyu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uywhlled.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhboxry.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pljfsdyy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrwrnyv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kngmztli.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwjpxnr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2oznwiwkt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2apsvsreh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2szbdcjjc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tilvkngt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmmftef.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbabepa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2awlncgeu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bamlheqo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zetzmwkj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzafarok.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjfyuco.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhswebgt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnpqcvv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpegbegh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cakcuwjs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxekxxdh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcejpogc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2efqbletj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2odishxul.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcipvwo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmihdbg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2befmwzfz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mnudijba.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxphlgh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2awkzpqwg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kboilrfe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aejsixod.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzimwad.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2edydtxia.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnmdsnk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnxirwx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuvbicg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbzsdyl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxypluma.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgjxepo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2teieldni.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrbmtqa.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kavnqdfe.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgaihed.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2metfbhxl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyamaqd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgfyigl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2svjtqoqx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfpgcyo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ypulnzng.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eupanixz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxqwuxm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zygbsllu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyswrkf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkuzyph.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpmdyyk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeesazj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmseajv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvbvptp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2meoltogp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxggjxo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2igyxcmgl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2avhfqxke.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2onqgyutu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akabavln.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqklwxmu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2isqghsfo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qogciedc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvcsdhp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wedmsgky.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlobvjpc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvrihwp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2sygrzlej.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdmnkfk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpnqvhy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgruvdh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsskyvs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pshlxcky.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rewacgvt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhjlige.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chevvdzo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crfxxuyf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxltxdk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytibybwp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtkboja.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxlxjue.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhenxlo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtaxkmw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzjngqi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2itebhgkm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqcgsmk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqfsexu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmrfauo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xfexvmzy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhuaaai.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2easuhwzi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrrjjnm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpkugey.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbfyxlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrprvvl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmswltj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnhgbyt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tmggqkqn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ugidvrvg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bloqmlkm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtnkfgc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlctxrq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okejmfhq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2baautypu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2erghpxha.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyrmwgr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wectwcpk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dbceoknv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jznccfne.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpghzuc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krxqrqiq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atnngktg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycytazny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2udsdgady.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfztuwxh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ejutgzhh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfurwawb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhghjfx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sttzmslz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpbphyb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qildzqsg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzptysm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqixiwnm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2drcprjzt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnzsrga.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kiceukrk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xirhfxsf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjapowv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhioahli.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfafgqn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2medlofhm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnyrdmm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbgcmne.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlmatph.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2paxnkcjt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ievcoofo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgbfwto.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neveuxpi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frpeyqyu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkvnyuz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2esrvbsga.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaawsal.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvimfuv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2skbxkdck.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2capintfe.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqaoipp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfzeban.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmafqtgm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdkdpkf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaqxwty.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhjtson.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjwdoxc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnhxtih.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyaclqf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2odppwggv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayorxljl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qidftmaj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpkaqqw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2abpabumv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2czlqhbod.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwmuees.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfbiqtv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbdkent.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpmbkss.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryceinvt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzemsso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqdmvqd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsewxwa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtipikh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rxncwhla.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pydsdphh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwcifhi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmnfvzo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wldreauy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrnvvdb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoytlps.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwzifsq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegrhwst.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ypktalar.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wivymfqk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qaroanzv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlfzzkx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhqaazs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fatjyoqx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ttybpfji.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2brifgose.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2puhmdoyu.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eemtexjo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrboind.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcybmjpn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naofmemt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvoajbu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmybacsm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2inspeeoc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuhzcph.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjxkojj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqeoaih.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ipopikqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsroqqw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqaulpv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqwvhkn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhuzfgm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwgpzgf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmjmuuc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkoocpm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oufamdsj.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjfcboj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2leniozwk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rwathmbt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2msazcnyf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvuwysa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsgupxh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuvnzbh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmnpqcm.html


<!-- 参考信息 -->