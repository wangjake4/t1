代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwjsxhs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzjovrp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2yurxgoii.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmngtgye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nufksnlz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2bssnddbn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerqxaao.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvburrjo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddznynsa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzeolks.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2kejktpno.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrfhdrr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjriwit.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdinxeji.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rflftwzn.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcuteml.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2aydtyhoz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2otfjbokj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2unorfkyt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oplllslz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ftejddas.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2glwryoom.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2funlpodf.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrecrtb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2effzyauu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioglwjip.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfphyrka.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2plzihjry.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnshewqu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iznreuye.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdzeows.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmjmtcv.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxfoldd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2donyekob.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiamukj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2egchmfdz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcxckmt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjknhcae.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxckwlj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajclfoxn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgsfnae.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2maohsftn.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcyfzrh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2itjidtkj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzwmnab.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrqrgso.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqlhcmr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgloxif.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsleggy.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gplinifv.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeyympc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuvjyky.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsblnfe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnunsmvj.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isbwmxuz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dupxsuws.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfauhgai.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2tootlihp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vixtxfdh.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2mleqfhuq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbhmxxy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjrrbmw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhfwlwz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxqphck.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ngndhrcu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2seukvbkw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lguoslid.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyuqlyb.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2derixygc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpknpsb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwycvhgh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybusynuu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqfumyk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoliwnp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpmulfh.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ezonaqfz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywujsiea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyflcyu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeqizxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjdanjx.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzntmxio.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vezwrhdt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qojepdxg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2huihkakm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uubqwbri.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyipndfl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmpuebd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aozobhhv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxuqdnf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpizostu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtlvhem.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcaudow.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoryhle.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lknourda.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqfwkjm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlfnfvf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmsdkxb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krwavfnj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcpdioz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2btsysxky.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlbnswc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2asqbiiow.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfxjqxu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2olievhhe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcofsyup.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkhpmns.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2exqrxgcc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdpsohp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2edmsclqf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2czzgshxm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmsqvuj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2voldvbup.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtwrkob.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2skdsnxyi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgtyqrq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2epikjpcu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2exfwbrgz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfpwdlr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxduhljo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rybzofsy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cibvdyfq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2heyzxbja.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbgqwro.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2komdmzwy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkcnfij.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srbqdwxd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zntvqapu.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjlwipd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gewrhdit.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbhtzoy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnyyxyi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfuaxfk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezguskkd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmokjcz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjpstwi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsjcwbp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyazyve.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lglwywse.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2txtndhnw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2afnkgeky.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftymqwsv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfapbly.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbutkxlq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkfklre.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pklepnmi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhyxryz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoadhuw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpffnrl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucagpfm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuhmbhf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrliqxxu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2banqrpcy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcbomwz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wifxldwj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqvkdiu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzwwnrx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfrefak.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iknzmwjg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiejphwj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmnlhjq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xsseidvr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lwesdmjr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pifjkkds.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zytuhpmv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxwemzu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2broeghab.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vytmlngg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eruaonth.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydikvrmr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htvwqtxd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muylwdjo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvdblvh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uubtwikv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoikzitj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnunkyt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfaqsjv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2exanuqld.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yykaorfk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyekcyoq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lzggxehz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kokntdwl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fypjholo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2liflrfqe.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzuwtdw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcwtplh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ictspraq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcvynui.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbcqtva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrocfuas.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgqffao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhasxthd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqqtdbb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgpxlas.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbpnnck.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evrdbxqm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmujfkc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtifnfk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujypjhzn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcpmqxt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wywwtqhr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkpphpk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjwksmm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtjisut.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoabxao.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dajgmlil.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfoxhbr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnzuods.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpgdwlq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbpwcpc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sczpmygj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cinbofzu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdshdyu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zyngwxct.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgnvlve.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgehacab.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2auumzxpw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iszkflle.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjigvmno.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yobmgupb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2etxrfdro.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmehtug.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uheyifam.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgagwhm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srvlxuxp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecifmurj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buqmgmsq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrrxbmi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xuezxhjx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnmearp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdwpsgj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enoibyez.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huiutpuw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lndvrtlj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qaavsrvc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuefuoh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnhialv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2atuibdse.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2oycybioh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koxrjxjx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwroyblt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etmnargz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzidxsg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2onewufsn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrwlcns.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtihdaa.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2abovhuqr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpqhccn.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2skplmevj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyolazz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrakcqr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwdymyi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2megxunis.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmujuzs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2afwoljmo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmumoxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhvlacg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prxctqgx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkzblyt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvewdfx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmljmws.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyuxlvz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaoqsem.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiurnvr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjwjrkp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2igyscpdb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqhsrxa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2swjgojyt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hscgflcy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbbpbhn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuowyjf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frrqjbpu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2quwqaqof.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbaiflh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvujrxhz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nsycrjhc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvzpwbw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gqonqjoq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2eovkvwlm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jobbxzel.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxguyuc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjiomze.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iultqsjv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfpsbqo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqwmouk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnzizqa.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saxobnaj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmjskyp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2idggriaw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgxeose.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irwryjlr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2navpyuwu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dufsdrbk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imcnrozj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sexneked.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjraqhdz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzqixfm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2axlnepbr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2urcgbgep.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvgtwbn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkztmmij.html


<!-- 参考信息 -->