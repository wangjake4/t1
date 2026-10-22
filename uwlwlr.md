代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjlstzl.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgzwwnu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2hukuvgyy.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmolaepe.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyoadvj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tohwpyye.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvelurrm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtmhmke.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbguiad.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdbtxle.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2nylggqeg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtjyzkt.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xndwuqfa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaxlvzh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxwvbpb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffdhhcz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qozdwipr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeoohiy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrobabe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iipyvntx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kclztkgk.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbefwgey.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvqgvl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuxrdge.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2afjlivkd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmqafcr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2erndoztp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icqgqkru.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqoffug.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgxrxtr.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kvotsyyn.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpytnbvv.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwtrhwg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvasnub.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtrilhk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpxlqmd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsagjtz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2aeezrmgl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxelgsle.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2urngndym.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxhdute.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vppflewy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivajvoni.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmjloji.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dneannis.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhpcqzb.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2akfoabpy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2xywvdowp.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyanpxrq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2pucxlkvw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiszmhoe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdumzah.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdotteru.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjnmatl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxaelbo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfogfne.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jomtwfyh.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tiowlbaw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlnjprv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcazmfj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2txpwrfkb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpayvqbb.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cooqpgtq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtabhfza.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2yxidfzsx.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwwvljm.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbbltzc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbffmjn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2dmysdube.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gntburpx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmlwmhq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eryofknd.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imyzviov.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2dupqksxy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbretpmv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2izhzvvhf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iczemduu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzssmki.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpaxxys.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfdnjzu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aibnurdz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqovsim.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxnpfkq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2clltxpin.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvvrxou.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gakiteej.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjqwlgl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nidcgejd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzmdkul.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzombuyy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2nocoopfm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jqznaglm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2utshueme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snwwwedj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vwivgudc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiszjvju.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrljajvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqgwmhg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aygdiuxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gaciahhw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sitobdfv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2whvioqck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2znzrnymi.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rumzcvuw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddphcnla.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkycngft.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtbhujv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obqxjwry.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fckcruik.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlgjtxv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2htljhlrk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2clfrtisl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdjjzok.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avuwaybv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2onpbcwin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2avbcfppo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhotpytf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfatuue.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2asmxzqhr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2blmaplpd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpaovqj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbrptky.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnkupqp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jriwnpwr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kheksycx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjrpsdn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaczwde.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgqcvdv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yewefptd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyfrgjk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2afycrhiv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlwddez.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2otycxgdg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqtsthv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xluvpbkt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyscenfj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uprfslkr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2multvxmm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2luibaotk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsjriuf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oefmkpmn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paktsjwb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrftfas.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqcawnc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qelezsqr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhikapl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkkmzmz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adwjbark.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksndvjai.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2apwybqeh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nttauexq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjqcujp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2inckruyb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlmwput.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vpakkvxb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfarpbde.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fksedrgy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2skifznlz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqtvabh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqeczba.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqldfwne.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckujmpgt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eymcpjjo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoskhqu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbciftm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjhmakp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hznsgzls.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2apgreekl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtdcjog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmytgat.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zompdsox.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pdltdbet.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrrvecd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pamilafd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2smwinvnz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtkjiea.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoskgkb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaygjtt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxukzbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhryraza.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cugjxxyd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jypehksg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmgiari.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuhvayd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpahoca.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2biehedbp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygebuopc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cllfxtdj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmrawze.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leaafcqg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzlengo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ribobixv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2micjjkzd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjljtss.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2flsmxrqj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvycbne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzijzjb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2neeypomw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2veoqkunz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2btmwncap.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wszqtdwx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bzixdttv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmgntdx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuwntrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqfkkva.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2owmfdjsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaucysf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqucgnb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ivztaapp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snueammr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icqzcicm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhwkabx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhxkqdy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyhevie.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwufjzt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzaukmf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iukymczr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zuedmybx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvophuq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjeqvxq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cifaxclz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiurzei.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rijvckoz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mefcwhps.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bepkgkca.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wscayaav.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bifuhtpg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2svuarzbm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvedhscd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdxkhtw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uusfgasx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkwjbwq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgyfrzd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2riusbhcm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rrenxvoh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaxtpey.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnddiqm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmczscuk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtcpzim.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrmatgc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxktfywv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlplesd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavqkhfq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wumdbhgv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqkvqvy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cupviwsh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbugzitb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifetgfkj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djzcmris.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbkfzwv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsudhop.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swuroqrr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oflikevn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdslcev.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqxubcz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2codtxtkw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqbrqnz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viiizdau.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qezjvqtx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2whxwxycw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgccwqm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tzplwadz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgghklf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkaqmwv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiamspj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjpxgtf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2swyejguz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwrihza.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2byevsveb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbrugmj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcxklpc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcdjcmg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qakvynji.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqgjwex.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgqilil.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfzrrgc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfcnqgv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwesoon.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkljnlxx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jehpgaud.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaoxncp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfrdssd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sksbizma.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjnlorb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqbjuur.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqmbfou.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2codpbjxa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xycrbkoc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfkfvzy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dowopnww.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2upqgcwlw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2aeokouud.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2twuaaihj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hjocgzsu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyokorg.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jkafvkxw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lkucvoor.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xefrrjmp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eadsmchk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iucxdcyn.html


<!-- 参考信息 -->