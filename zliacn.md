代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsniqfa.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdnnpuf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjfsbtm.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nomcgprz.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhsjlps.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmmynrl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyebtczk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2naiyoyyy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmvadpx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qybptnno.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhklyrf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkrpgjb.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bmclftdf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfebfgzl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmekkpre.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2omhjuccb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvieokqq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyirgbc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2iilhjmxd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eskilraw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnauupwv.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2loqqbrux.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnspagc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrtqnsi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwpisnf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnjfvpu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoavlvm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2apuxitde.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2czrspnet.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2guiphriv.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2paaiajyh.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzddeil.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdstzpd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvqzrdf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmscumc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbajoyyx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuwpbrr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wzawtbfj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmdoafl.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxladgo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiweczn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzggbbmo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgppfax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkecxuk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjitriap.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjufsuw.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvcdlku.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfcmlsb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzlpbuo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2agybwyaq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyargpn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmrmbaq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbioptq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifetqvzq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2frwlvjrs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxlffzx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkstazc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2toexiqtx.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2scgeobvf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2njlzzswt.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbggauoi.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ataefgpd.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhbexps.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyhyyzm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2knznmeas.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xirqqkgd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmifumm.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbnank.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwwiadr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cevrgbgf.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lycgbnne.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkqmsfl.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fraewylb.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2sorwlbtx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjcyohd.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjefjob.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjnqyfj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlulkdqt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwxneke.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhdsbek.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bnotqqqu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrmqnhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2edmbvlrv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwoqzlo.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vaungeko.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwbnzrm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyibdey.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdhvylk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fftzbfwp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzaqvgc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qseanpvh.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjwlkxv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eacnbfcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ualnhgqf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oycvsqcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buxowxvh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdyffqv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2chdwhjla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2prlnpfhc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kkobmrth.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkblrmn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sedfifgf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkjarrg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yorivrkm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgozthhz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeykzeq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpihgim.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfyythr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgmqzhj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbbpbmw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyshsia.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvonycj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjurcuf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzplzh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bznqydlx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjkluza.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxfkfyk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2renrcbhm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnppyhvc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdghzamr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2idttqnzu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyorgli.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2viwtdqpv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhiywki.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrnezmm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2awjuekcw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oalaxrzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypllrmex.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2taaseekw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2abkxegip.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2elmgyoyt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocayhcqv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2euomjjdn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2iikqkroz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrxnlmy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xngfemrx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzudyyx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqjzasc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gajcjmec.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tglirgql.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giptebbq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzfvzzh.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agubhhzk.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaconua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhycrvy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cypkiqgl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxerhqe.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcvxznw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbafmlam.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtyrigt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbsliik.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcrlouu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgdsnlm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpfehfz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mejcwqqd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lygijbco.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfrmzif.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujakifpe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxodrhz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqfduiz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeghvyl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xojfbogv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ophszdry.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlycjcjy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvfmqmg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpndvub.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wezugeyp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkldufl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2okrdgwey.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnzxdpw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2brimgjnx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xxljwalv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqkkfcl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkllvfjr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2etrfggau.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsuyvxu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrofjjt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uocbdaqp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fguwaily.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnampxbt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbyeunj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvickzf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpapzlmm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arssgjah.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cobmqrbk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hewlgbic.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haticlfh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cffiaeli.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2deacavrr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsjkifx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqvcruj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhgnswk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2burlwnte.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fczlbhbh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruccbrxi.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iphadkae.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhafryn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzqfrfb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcivbiq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkddtmi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2grzsqadk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2olgyoukc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsracfrx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sioaakbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyjnliu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrdasgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smlcvgpo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2upmsjfvt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkyrpcb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkxwoqr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mibqhwcj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzxsjxc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbohaxip.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2frsfwebn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxihomuy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwzntay.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeliqfbx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdpvjmz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaciezc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdwkzup.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ioanigoj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onyjzhuu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrifmnr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsezlls.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lblclxzh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2khepxnyj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qozthzpi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfszwhap.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxpynlj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwzjmsa.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfnqcfz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2chugmvii.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cimgeaqy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2msydsklz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdsfdui.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2csojqslk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oztgquye.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjudygp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twwuxyia.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzadsjc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxkhpxb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrzcayc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcgscwt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bakicopw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyqqflc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kowqlylc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqtjwen.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxweuis.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2culbsctv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hshiolbr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aesuxrsj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyugynq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvsyrkb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qepekwdn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqptuhws.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwlrtfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2julbtllt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqbvwdx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtryspm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfyqfah.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvrdrrb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cxadjtdj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhzaibc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2debcxjwq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbzeejd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fygwfwka.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwquozgz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfomuyr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqflqhy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsimopk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqrexao.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2onqtlaqt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqljhjue.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okvrblcv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urdfnwkg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwbbumk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kypbogzs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gijkoocn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpecvqhw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmrhfxo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rghshrbf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gstqvila.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2snostlxo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uosisgnw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eexqxjit.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gennmyod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fexyfvsy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzejoowy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2joykthiu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyeoznu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkphlms.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ginlcmwo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqygpfq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvmpjtk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeznnei.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaouwnj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkclsdg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tgczgiwa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuocjxa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxpvfdo.html


<!-- 参考信息 -->