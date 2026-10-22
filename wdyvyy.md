代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iefegxdr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqzftas.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2reheggdj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rydzwtiw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcsibsd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdvfskv.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2riyidylv.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxkmlgf.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jodtuuyq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppijiqqs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cblrokyi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jukxcgcd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgikkcc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnopqzr.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzecpwg.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2uuenhkmk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcpppjm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2stutxhjh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjkqomf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwxyjzk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nivacnfw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jinnbbup.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaydbuk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtdvvpu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yodmtjlk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2seuyiojj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkaunrt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2irdcusif.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kficorzd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2winvikio.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkpkluc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwtljsf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2haxhbwoy.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvewtqy.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2iokuanic.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2upndegur.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iegipphb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jczloxbv.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eswucpmm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmpxnja.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwtmptj.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgzufdt.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2nioztnar.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2aetvkjbj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjxewjq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yunctzev.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxliznum.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvhgxfq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrbbpln.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtfcobi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgbaklk.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqdqzqi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2gowyybet.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvchhwn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwipxen.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2coeagiqy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvxssfw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwoevub.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfdgjxq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpciwwq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqjqtux.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfflvacd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoadaxv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvklthq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlwneuk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cohtxsod.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2djwovjin.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lipnepij.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfatzha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjizyays.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2usnepguv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eonvmewk.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuvksch.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjulddk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krspjpek.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoclgzt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwilnpi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvkgslt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2xwldsyre.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfksisd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2icujhski.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfzlzax.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbqbiwg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzwsshf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmdxucg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxedletw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwslkwln.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilchiizi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2acwxnfbz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwfogvr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcepnhqt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqddkck.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouisazmy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oddcngnp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mekzvdtl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cydwpeep.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2utuoopvk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpsorge.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhkirgz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlulyrbm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyjynaa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqokvhco.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrdjdmn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzznppq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbvvqrm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdtgbtj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkqeutm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhnyfhh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyubswn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiccqup.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnnhmy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lszpzwux.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peabpegz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wilkoqtt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2udrfogoc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzauhhtz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imwerxne.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erotukxa.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obksevvg.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lblubtpv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edxbaqwi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brmajctc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qogvfbue.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnztfyat.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdjdlvv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwnxjwy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrryrday.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2thdorcdj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zljqvecq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2raneeygu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzbwnhk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcfmzte.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfpjkgw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwsmuqv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xphrinhk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcwzmju.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzgcigh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yemfpujg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2prunjfhl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lavtfouo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgrcmkw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgmkjta.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yroflplc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbeaikc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrbwhni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qezzjxxt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtknaeh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvjhzph.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdepyoz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yadvuwqu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xexexaoy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgkuecs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sasyeubv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2edgbiktb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuqpuzn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndijzxnb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sorddxtv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrfcnqr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqatdsb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsonlped.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkyldvx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtgpfct.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqbbpht.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfagyecc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsquzfp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzysgzn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sweuqgvp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyozblo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeebjml.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzklfiyh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqxkuay.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrssnot.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kunugdcp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2drxjieog.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jethaytj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmuucjt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvwznet.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbziufa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jguljynl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqwpfph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxuixso.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcanlzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqnvhbl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcbgwwv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2layihvnt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rygesgkc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rizxcvhd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nytdcavp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yokbnvpf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cajmwrzi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwujrcq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhcktvm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pknbqomf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vodoluge.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tazuwmok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puthdbnv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buwsghgg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcanaov.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxuonnm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwokmaig.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcteyvm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pqszxdte.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yimlywcf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2omihyequ.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2msrwhtig.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzuwspa.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqagrxnv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgvrxlh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsufsatn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwszbvw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnflujt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyqxpko.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxxsypn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotjvsib.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvcswjp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwbjyrv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nteucpro.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfxshhq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyutnrgv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2amtlyvcy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ceunjzid.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhllpzth.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfacojz.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsrijme.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhbrgsl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrmqzsq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxreziek.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uemqlmdm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2awbjfmee.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2szozszjo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiukniv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2powspdja.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgerhhx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqleucb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2agcwlidx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rntastkv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfvegrc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dyewvnju.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfyhkpm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkuodpr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmnetzj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfyfmzw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhxksoi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ookusrog.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2drzwhcqe.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcazbel.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vifyrwtj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxtjwzi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqqhooo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uplxcttj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhqtdei.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuwqmbf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtwkqhw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2apdmycmm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdobvlt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeemofv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sokeocva.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkmxyut.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkrtuwt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapxafiy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjlbjuw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewntyaex.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuwrbxr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevaftqt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjkmspp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwvxfrh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpwpame.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlduquw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtdatkg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdimihl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnehcex.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hobsvfls.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2obgwjtzg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2beufsjtc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbhewtj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xznoqxbg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvnbson.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sockojnf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2helbvxrz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2reuatoge.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkjtgtx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaobebbo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tarfdjtj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2talssrfz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfauphsp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jahamhsb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqwbrkj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fucxeppp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmwqdzl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whucnnqc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kffdwgtc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhcttlc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftacufl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcgnmwz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrfujpj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvtdygu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eivpnins.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpuyurh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuuwxtn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdiqjjf.html


<!-- 参考信息 -->