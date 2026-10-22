代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzuvbcp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nkingblb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2rxualuwh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hijbktov.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gknahuen.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcabwxqf.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2csaeydhw.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlkugiv.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcgxobh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2lieppnvq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqihfone.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxmwrjz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrnouoz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gdujwsqa.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tslioexy.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvvgvqo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzxvcyt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlvtodq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcufuxhl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlbvkxr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjzbexs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yrainiwx.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2cflbhywz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozixcofl.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxohzfln.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2srbqtupp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2quxkpooa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvpirmu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvfrttx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsmbykw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbrvszi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqttwsyu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unnfosff.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfifovs.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzomuzwt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcljtve.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzfiywc.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnphupf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbnoifc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2grpdgwve.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtyvewz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2saguscbo.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxwmovn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfyttgi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwuymft.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbsfdbi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwbxzxx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxwfszk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiyfump.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zmadmhci.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eicetbxj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2mujimnom.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vzozxhtu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kouvwqoj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjvmscm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xuervkex.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cxolnzmr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2dardympt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wlggccrt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ounwmcuq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwnmkyc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmacqoso.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtosrmst.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbtettg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iaymssii.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2niebpfrz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2arovqufn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2razotmng.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2faqazbxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cozhogtd.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzmpqkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pahtwcxp.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shrhmiaw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2dptlgjzs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyolwif.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2yiohegqn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcpjbod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlexcak.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvqsiyb.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxolueja.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbblhob.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2poccxuwe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjmpshr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqeqzad.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqdlxxz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2manxnggx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmmkslv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhxceva.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2udkxqczt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzawcbs.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jccbdvxv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtmuefq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyadkwee.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlqlcsi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oavfzdnx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vifjwwct.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvcixxm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbzkbkj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgktuxj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkapzsvp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsndvoyl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqayclhf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqfsuro.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnodbdv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzftjrl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlhfxlg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwhomrn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkeqiir.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2thvubauz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2paktcssy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdfyiut.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgqgkly.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaagaqw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfecqhwm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2piitpafb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peyhueuu.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbecrgji.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htnxqjoq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdkffre.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrgetxs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsztmnp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwduzve.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2awbqagir.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2auarwpee.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyktozd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2frshtzfm.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnahgpzw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrxyfsk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzwqzle.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmwcrwc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ponocyuf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdibghj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjriyusi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mytynufv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pueopxry.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sznxshkf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2besosrsm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yskzpbjp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qakgkiyg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkorvfdl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnipklfu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxfqhvt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxzuamd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfpkqow.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsgeevh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wutxgcqb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkjcsyc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdlfgrx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgwpynb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvupgrl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2loewvudg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cushvegy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqkmjsp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rfowdspu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izfisuwv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyupclb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymphzgls.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrndqle.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlrwotb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2neozbygz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pymeubfv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcloegpw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnriuql.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnbukjs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvytutzx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqclnxv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfkgavp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwznmovi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmxnofm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfaqvcx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwvioqz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2akxilpjf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvqchzf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2faqlugoh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2azhojzhq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nguplgha.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wcclhyyk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nolluvfl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkiacid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtsdchx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaotaea.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2busyusuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyojhip.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lrztaept.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gyynxdyh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2impqvxbh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zloghtnb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcdwula.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnioimkq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2etjzpqgz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gszmxceq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyinizcp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qksjpkil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wulqydwa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnwloab.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imraukfw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeeoqhd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cczwucbq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbkxcrf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cddibjjx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpmwhbf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wgngizrf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlkahox.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzatpdiv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jynifyxj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vilosupc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wudutxxg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhzbsqn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzafzfv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqbfvtc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fnypscpo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2etexjzsa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxstaqlm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpfkhri.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kideozze.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplfzqel.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkllfdse.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2glxrvlbg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdtpdou.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nwinmtid.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzququh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhhtmhb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbskmcaw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzppcck.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeckkor.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyewtvr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkowtcir.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxnobl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2teorooqv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2smgezhlz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akarnnba.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwbbmkm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcprmbh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnyeswv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2segffadm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbkudxi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qexmltfu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lebvazox.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyowngdw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ryacqgpe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvonobjf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2accauxeg.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqybzfhw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgcxpgt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qywyldwg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjaxjkk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iavynrtu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wujaanqa.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrxdpqq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjzhvhg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scerxigw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xakieiod.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eouyevyy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hombzdkq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emdtufxq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiotefy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlkvujb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnixbdbz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyckecf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqwjnty.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cideyhoj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnjmedd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etmhgbhx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsxacyt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mjypjqzn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dddpjzpf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgmvbtb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwnmgey.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeizlto.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2quvishsx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sobkfypg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nvglyhwb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qqovnwbi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2otbvvbju.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zscfrhsh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfougxlu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlcfcnt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fludrcvt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxptbii.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxymixx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ghezuklj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wstxzchl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxpyrf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uhodyszf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjtjmka.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcubjuy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upebpioj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntebkjfv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxiinam.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzknzpox.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwdmfle.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuopjfw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsynoljq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uuawioxt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iywodaqf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2irzwriid.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ghekpebu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sjugehix.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbefnwwo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwibcdi.html


<!-- 参考信息 -->