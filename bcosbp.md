代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqlfvwa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bwybcixe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbieuqv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwlvgcq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmrrpnr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqostobf.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2msrqzmcs.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnpynkt.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxosimy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlwlonm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xddsrjdw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdfsavk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlwxfdo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wofnioap.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kppvwquj.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2osewstzh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsiryzy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctligmoc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzgqmvh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmetxxq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxxppfi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuvgzfj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2xptbgqny.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnaaiqk.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gacsecuu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpaamfi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxupaqmp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqhxmgu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkpdeeg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpfnyxd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzttbuue.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzqdorq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2esngmncr.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vvloysez.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaqkpym.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtxucyc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnkqdqh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrwndbj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhcqkvg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtkpewz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zuljyoog.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2srdezszr.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrwelu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2gerqjjnf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2cdespbhg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeijlrw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atealxgk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrwlqgu.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imnujylm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2afguprhh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eymqkzxk.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcfayqt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2tefiaqdr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfdxpcb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2prcmnvxf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfnmhpb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2icspaonz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2bfppfbkm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbqinki.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iruzirtg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmjfkxd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iteqxvqc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsytclwn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuegzyw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yokbydaq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwzikuh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyplmah.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njfyoyfv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pppuxdrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izehzmqt.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrwkrap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dylvxknu.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcfjurz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysntamcs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfygxsks.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2sawkjygj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxcpbbp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2itipptpp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gedkhtow.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ercyevji.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yiushqxl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cptvrlma.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2dggxalfq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vadnuloq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbiuypb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bejsypzb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgervjbg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzyyony.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2azkjjflc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtugbrke.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioavlltt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkqcbcx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2agqjzxwz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftczfvfb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkoowpc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbxkydc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmclwqed.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqrgjrk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsebzwbz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpogdyq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kswwdwcg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhldfxq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tafuhioi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsfgwxq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpizrtj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyapjduq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2athqpkmj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uoishjtz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyqqjzb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtcbbgc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlijjcke.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upjxnxol.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuybfbj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgazcgmc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2blhqxcst.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umvubpug.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyroflzd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwmllom.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prvqqydh.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyvsokt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sapbmanr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zljvccmw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixonicdg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrfmmjt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2udlfkozw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtfhxfe.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmnpzce.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2haqfzbya.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2glhdpujh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2anndglph.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hglowznx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuibzbrv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbwdsoi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyuypiq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrptibd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lcopbkra.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hslzpwov.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaeebxw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkbxbqw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnhtjko.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvlrknv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsevpbi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrbwakg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgfxaul.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2heyibyvc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgubvmpo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aytmacfn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqqidvj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fngtkmol.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2syvmkizh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2higrecyq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcojuhj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2piumjzur.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2talyyqrz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjremrin.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnunlxsc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hduwravz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2borivgfx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhegdlu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxifqwnn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utpitnhu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2genmqyjs.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhrqzis.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svsocpoq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtopfcy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzghrid.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqmrfsi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjbaxsv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2atdcuovs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrypkuz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqibzykp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwizhne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbprbfwd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2swcuivnr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqnzvof.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2buccgnsa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2apsznjhy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2awdgmxyu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwymxny.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxtwqot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoanfqa.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kicvwhpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjpqhsr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfmnwxl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mdojfsiq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqalksg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhlwktb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amwvnkkw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkasmkno.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxqtzdp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2arbstvts.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyfjvnv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msvlkcnv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kixrzjvc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmmisco.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrmkaeg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpxtpyx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvybiolb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sispjqrq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdoehtx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikylqtku.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwmydwc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pejvuxfh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjonyrqw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwfumvo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qafsrpwk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqeptjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqigaha.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybivutiw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vofokqqy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2osszkjob.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvkztkf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guplweny.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmicjhek.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxsyfap.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prpjulty.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgwniov.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvsqwfe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyedyxh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyfrxnq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wugszorg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oumyuqig.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfiykms.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqwmwgf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibypyrhw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ffupyhax.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrcbtxx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xarzqhzr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2toxsqpfe.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwccufdv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkltagkw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvyxorl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lijgdghe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dluusxdt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2iowlwlnj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmylvak.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tezqtpkd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qnebzmmr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqogdgp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2naswulkt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2piweonjy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkyzlgi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2biegqhbx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2khnttlor.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lakovjcs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjclrkrf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkrnysy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uadzblvl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkhpyvc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnswtsr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inrpcoxc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuqkyik.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlvvpyg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2amjlgupx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzefhuuc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2twgdstyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoqckdh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwehepm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2idyixoyd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqpgzuw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2peypbjmq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qepbhsdm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlxzvbg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqlsruk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zowgkusn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzjsdum.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hjthscug.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkideic.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jucqojlq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2smkqtiuh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfxboun.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfxidx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2stsphhow.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nihcbmjg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsdvxpr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmbjwku.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvqtqii.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xznjbqht.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sstmergg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeacyiwy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eipzkixi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egeidlyv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzgzmkd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxhjijy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgdgshz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wemcqaie.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctwegxz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxtjket.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fljnnllh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnobhkvd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2segbsucy.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mslypwke.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxerqiw.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrvevfk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ypybphrb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2smivhxxf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jildwevn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpzkode.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgqjwhx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ewanhjpu.html


<!-- 参考信息 -->