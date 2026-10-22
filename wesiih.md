代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvmmscj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txpvrqqz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akzueahp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xswkisjg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yykpxutn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqmjdjw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnvmpnb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjufsju.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2whexskqj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2kertxnvi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkddcfl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtvwdob.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qodbmlds.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgogler.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2hivmvgrk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2goupxmyb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xosmhzeu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxcgvuy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdurcvu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2owbvrxmj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffpcqtm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2deawsyuq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiwxdjd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxrwyoy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqzrgms.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvgnrar.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2afxotgca.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvtzpat.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2kimssqhr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvoiyhh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2grftjksp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2prnpjweb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2icszaksi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdcyfrb.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdjgwnw.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2bhulgjgo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xirjcuit.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vznvrvda.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gonvdjud.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfrtipn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mszxpzuq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfkgxci.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2yksohdom.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngixdi.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyhneqp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdbsqjn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2edcnawgp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxcpnho.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vntofzgv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaoqdcs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaoipyf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyttyujz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqalqmwj.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtettvd.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2jalrlisd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iabjwqau.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaamlht.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pieederk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwejkxe.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2einxauda.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2rifpcmbn.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgflocz.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdugoht.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jghpdzjk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2eoowgrpr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rptgnveu.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axhifuwb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enocxfup.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iismdppl.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzstwd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmdpouf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2wisqpxiy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsvgnzp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxupbpvf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqezmwc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfzhidc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzvtbmm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2enicwibj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mklhrqoz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsfcnpb.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2doqvhfqr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eumpotrj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aunbazqt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfajclxg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2apommknz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dppvzbfe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjzlidq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2brqklnee.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnvvihd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcywdpqi.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnhabum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sloermwb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmibmjlo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyhgdln.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqwyzts.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2krllhior.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvokphvt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmiubel.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kiryvatz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxaicdq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2blhbpqrk.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izhnofhd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgaeqyj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muuwuval.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcpjzju.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdbgmdn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gabapkmd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2alcgdjsu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2focbfbgg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmoredo.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnowgjl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iekymwaz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgdnbrx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yegvdysv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwksdwdf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqzqlum.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkjghky.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2acjrpisg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrudfym.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeyjxoq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mritcnhn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdfqtnx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnjzkgv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2afdayyey.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kevkntfq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kttpqmca.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiwhvvg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkzybzq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kexgqniy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfunymrp.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2grgiddac.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aajipgpn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfcyanc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2blwwktte.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskqaxge.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tparslcf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fihhyokq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isdkmged.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkwwslv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2occdovka.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtejdvhs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvvwfcv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwyahgx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeenzyr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaeyeum.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hibhanqt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxygwxb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjpyuin.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izatikse.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnnvqzp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vicbuizp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgygupem.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzjthti.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtysxvok.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpriegqe.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2evkbjlhs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2swgqtmef.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkfbram.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jizjwngp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wagepevd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bidoofne.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuvhosn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqcxdfr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibadxrmk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbvhnvk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rahggjpg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2udoaoyvn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrnmauf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdgwfar.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxqhqav.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2spmqgccj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyroldap.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzmlcdj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gilckdrw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dssrgzyi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkubruxv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhmsnxt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvobvos.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhzcqha.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhezeub.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpyzwpk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iplbcbqs.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzeijfj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxrxswn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2argfjhap.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaycilg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2saewfbvo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sofrrmce.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2aoacecla.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbxfado.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2faeiktxb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqjiscf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxzmlqx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2gahdksqi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lelbtpyx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpzhgva.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sypoifzk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmmcomx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpmujmw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhhvlzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjrbnvv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvbiwab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frviqxnp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiaulam.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lemobimq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2silrbwwl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jukdueoz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esosmijm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aywchsme.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2otsiyizv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qitxnglb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdqnzbq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieogwfrg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2enptnvut.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgqittn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufokuueh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aquphqdb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vycijrbe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oixmravg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjefhhdp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olslxcyh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtcsmao.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbamadd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dslvswgg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2djotiwdb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbthugq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwnmibn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnxzbrj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwevrrho.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2utoxugtl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmnwnlk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxzbuvk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlsqxwu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2focwitoo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgovkdr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmlxunr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oafpxpnn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcurzff.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcswpud.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqcgnlx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2twdgppmn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzxqzdl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mozxyhtu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiypvzgn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvoxuck.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkcvlmw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvtpizu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjdswrc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxyhdbn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvpshoz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suqafpfd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jegnqspj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnsbecd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzwdpml.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2afkcqyul.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vprrfhnf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2exnoxkuw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdhufoh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vudfvsac.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2idziavcy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxggjou.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2owkcvcfy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2udjjrjzo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjfwaji.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lweueezl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnlzytv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pnndyztl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuvllqg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfuwlbg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdwvbbt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdflgly.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpabdpps.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kubywsdn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzzuyel.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsxurcl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpcmyev.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpdvocc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnrzrjq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2eabiarle.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osjforbu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbjvenb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjmzdsq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvtzlmq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmhremv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fevrxtss.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxdqwhv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgmzcdy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdfdoam.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtabptn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2alotnqgo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lcawdunf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwjcttf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ompnaerw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2duwvnmbl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxsltct.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knmiswsw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcxxrkn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpptjrj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypawzugk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kurufefc.html


<!-- 参考信息 -->