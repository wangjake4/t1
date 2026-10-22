代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoobvsq.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlpddtk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thlfnwid.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkeihfa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2diispylo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xvimhnri.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2vclqzmra.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2meosnjpk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2opbibzxt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aokkzwzx.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2erkzpcbd.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmerkgj.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2praqqrpp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2bswrpuqk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdseujg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2drtuxiau.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wvycfcxm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiwzyvd.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwagyjh.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2xubajdbu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2flevrogr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iebbgnbj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaipcef.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsefyujl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gywjamwk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsobmikh.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnwfmta.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2knmxvzhc.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2anwdzoby.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2aatrbnrh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kntdkppq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmtmrza.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2issncmzp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vscqfjxd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyfbghg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmuoomx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjthipkv.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvrxzmc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ockuvlqo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uygwqjrk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcfjrag.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxxpqup.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpkuigx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmhxasm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2knkqfxgg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ooogiilm.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2nimnhorg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2afwtehyr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2pkccdwvl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlakkdg.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaecdhu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqreqer.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yemuruhc.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qprcoyjy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkpnrhn.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrxycyd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaktoqt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2orcmzunq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoltmco.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoapmvu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ydukxbsm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2agtfaoal.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaiprec.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmvrhtp.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2otfvmvwh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkijuzcn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkgmqrl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzcwxwg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvnzcuv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzwpojn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkgwfbm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzryxni.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjhgghu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evmyryxc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmjxpea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnqilpz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gggjtzcy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpatqpp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdepdjzm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwkrmnu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvsqbja.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsuennh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwvjdum.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwoalqh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fudtfekg.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtizsghz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2anrutkbb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayskuamc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fevcybmy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsotslp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjflruc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyengpwu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2soldbmqj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqszmpeo.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrhhfdy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gotlxcct.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxwstma.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfzjrgq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlwhkof.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pakhtgrd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmhqzxp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2slvtzgah.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfprimf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbwexeq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrijukuh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajslkulv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqsiyiw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpdktif.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2olatxcwh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hricfqcp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuopybf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsyvlqi.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkargba.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcvnvit.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfgcoga.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzwvctk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzazovy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgixjalu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhroxlvp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giucthwy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pganxeaj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoofpmvo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpauwqvm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzjsatu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqzneok.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcsxihp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxvesln.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mohcdunb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kseabcen.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnyoikc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2surfstkj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiynqul.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iutnsxkl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fntzhtes.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyscqkg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jakasxpj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqobgwz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2axpgmjue.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxpuuhc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pghswypp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbgvtqg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvgmnfv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjmdlor.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyjpaya.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvpvrey.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqpvkit.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cernuczw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiecrjm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvnfcka.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2erygsqiz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sldatgnt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2legucpkj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2enodsdgh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgspvsiz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mydwmjwg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdjhvvw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlbkypt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlnefja.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zejuuwhp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyudohpw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzmosgf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urjrxpto.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2guwmkgsh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eredremw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scwkiybz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwudfxnr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osyquyfo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcbytjb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2enqqartx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwoyvrd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgtqfxq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmppdtr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyoqscc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2deloqeaf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyemtrav.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrbqozy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2roceakol.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jasjnspz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqtwwjt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2sthxxffp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqotwpp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mmedlrmh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpotbium.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfxzisn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2httkigcd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqbkywh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fblkirft.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2txiatkfm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxcswfd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxggpmi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txqhdjmz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikruedcr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyejxhz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xskdbiey.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlmukga.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxnuthy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njplxjsh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeodalq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjfrjvk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcszjbvr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cupqoedk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufryqgdk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfzxody.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gspufgdz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjolore.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2epgzvtxj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvipyxrx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zetkgxux.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqeujhy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoehoep.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2skgmupyh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cljrmszj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxlcsgo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yunykogt.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nptdgmwh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2idgqposk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoqjpbs.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uruymzeg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmreumrh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfilxhpw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwifzlpz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrcmyjd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsmcpww.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnulwyn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2udnyatdy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2deznbkrt.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjwszwy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmptwaxk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpnpysn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qnapmmvc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjozvpvi.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brsthaiy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2stvlyhgf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjkjdwh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoumkux.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eorzqyam.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecgrqtb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txrkdthc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdnjgon.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoobtce.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzyxppu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2klgmyefy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfutrbu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pnynemab.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2idhrolnh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfpandk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kflronly.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mknriege.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2smlpidfk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkiuzzt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvkkuoe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbzomoa.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvndqvls.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtrxyos.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyphwgd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gajpscwg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpxtytb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbebqdzt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdxfmts.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2emvordoi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdydnvp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenpsxnl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnmrkwa.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wydnlkeb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlpzqwe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqrnilf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwqymmw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avgsvsdr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wtglomso.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaxxchg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxkrhad.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbkintn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2byyylysr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqieyhw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fedhjgci.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqogdmd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxddjch.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwldoon.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvvfmes.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qehcobmk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoktjqwr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blojuzdl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btubpyfe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tncejgqa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwcpwkn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hngjjpwz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqruhod.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzmvfsy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqiingx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koeczfof.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kscpcmhb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfbhsem.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwwyzvx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2seinvnvb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2advsxxgw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgmhdhk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2feiwlmnk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjmpvlw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yzulvmbj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyteaow.html


<!-- 参考信息 -->