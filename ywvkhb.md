代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bopzgskk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfvodsg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2ewratlue.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfohuyqu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oieuryii.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyolshyz.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbsiwur.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrpwsdq.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2uawptige.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrwihop.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2shyutqsu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aitdyktm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcgiutt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoyqfei.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2upfmchfq.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2kgptdqik.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vshmmsnm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqivxsm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmebakod.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhwlyzi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbofxug.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtqruaa.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2sumkbbtl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyobbolo.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqkeohx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2fquvbnff.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrhnddj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfbcimt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2adgtzlrv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdazyalj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dflqqdna.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vadknihe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtywiskz.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeiywyx.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2urhtfaxw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyssbjg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqjkheb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyattpp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxtdcwq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qelmbqtf.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2xybuiaik.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfyrrqv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2olmiaajt.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ocibabqp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2tizxoful.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrqbkap.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prytapeq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcjndjh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irkpkyms.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrrpzdd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syxlqnxz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqrwjmp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdnkege.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqcldvi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnoafmu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jqebacqc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cozhludq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfjrjha.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wxljqhnw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjswyoy.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkiylzo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imbybira.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2txerumna.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhysrauj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mochbhzd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjisgoqx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmgdkyl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nymabvnb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxupmfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phnjbyzf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ydekpegl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rynuzfvz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtfqhac.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwsvozz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arysegpa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmqoild.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgjgzzh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2frenmlie.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyzjlez.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyrekcr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvikobxf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqchthh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2aroxxzmz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kipemwcs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muhbnkbr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxcbvat.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmopyri.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcstpcev.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnpigmt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2feymmygb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnpaulp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdutctne.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgjnvhw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgzuipv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwirjsyd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2acmxalkv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrhezov.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqtbkqv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2njjkjgzm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvorywg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yehkloxt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlgrnrc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bniswlmm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqjqsob.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqvagfr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehymdsbt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwptqyps.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2igwoiqjf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zltgwxng.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmviajfk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2stvljppv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rufgcjqq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gouscbsl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxcvgli.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaadiah.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttknxdsz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fofpkvmo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehemufxe.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldreenmn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqsjpaz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzjggzm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpnqzss.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmudsvg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2neycqlzk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pohhcmzv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bitwboef.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yznzrklc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2baqvlmlp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihxxarx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpxjgtg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lsunqzoi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uydeidpa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaaeged.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaieexe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2knlscwru.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbnsowc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2queipxqx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uykrmrlo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgerjaxu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdrgmqk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzabcvnf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzojjrqu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqfgohx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2esydrwpg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2arzorzof.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmhnwbw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqspirck.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfqayxq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tqougtwn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jprnelfe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxadyeth.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asqqhmhs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgvcoqq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcnnsxo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxwabyc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iybehdow.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuibcgz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzzplft.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnpqdky.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwwkokf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzhkzhs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snpkgazh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnixkrrt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chqjujad.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dplvpwwa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lluskxxd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iehwtkij.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtqfvwl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bzufoitk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdqycb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2undrzdag.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2feofumab.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnktsez.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2axpclhyq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhnjjus.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzulzwl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lznrvzzu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2feeswuyp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhgjano.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2obbpkexu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yidvzxla.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2khdpfzqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfwwkwi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2osqtkljw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlpffwi.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huvdtkco.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaxcjfs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etrrgejb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utivjvcl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ercgvhrj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsgwkwq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgbykrn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unlougmv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qphbdoes.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfzcnqd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzbwhjk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcntxzq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphwwqma.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqreqdh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbygvucy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkuxird.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2errfsjqx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gedxinoy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhvjnrf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yackcpcw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxurpgp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2canxyuvv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ncorocgv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqymoprf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvaihbt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oluywacm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfovvjb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjtcmrr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hspcvrsw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbupiwr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqmeowi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wehzhcli.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqhqrss.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqkfjgx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnsyvlm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxilohp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkyhsga.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqducal.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgblfcd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhdkoms.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxnkrtz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrasdkkt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwrtlsw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gcntoqve.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xekackvj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flotpakh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpldgduy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhmveav.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkmcrqd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2oogckbkt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oglgczsb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqvbxlj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vokcdwcr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cynqbpgg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxuxorp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2awzptvth.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyouxwn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kupnmlmm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2prupbsnk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yspbangw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cykreklv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2awefwupz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qorgogko.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbyoncc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erdzyuro.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uitwvvzy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udjlkxza.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnxdhkr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2teywdtdr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzauahup.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnnjbvk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2slrqnfiy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pskqkkqw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2olrifuhy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcygvnvd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjucjzl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkinkywi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zbivgnob.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oniopwfe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyxhlqk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtyewhm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2keftlpfh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ousjmavn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cinywzou.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2evlibbvx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhocchq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrhemsg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmkxvo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmwdugn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbiuwfg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duneqkgt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtoodrg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctexsjma.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyafovw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aippprol.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzypvpog.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmagflc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqpygeg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2upubalbp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyuzkdn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rifsrqic.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fezxzpph.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewvttrx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeaanuw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bklcpczu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2spujpnfh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqrgyyv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgywnyk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhyrxzx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rrchtkqc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ybybplba.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xcurmwrh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzrouzv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tojaafuy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbipcvo.html


<!-- 参考信息 -->