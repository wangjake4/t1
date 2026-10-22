代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2olswqcao.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyifulhi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlyfzfx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpmaquz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gt2bghoojwe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmayksi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzkccbg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjymyacb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzelxwoi.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrqpgly.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycixkrhb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdumtfn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2oprsmxiw.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2humhhxvu.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvndkzb.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbsoeli.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjzmhey.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2anclgism.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxrysvy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtnqccb.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wqshlsnw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hthluvdv.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cniuemww.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fstssfef.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2orztznlg.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrhucfo.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wznhcjga.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaizqwn.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wciygixp.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxcrbhw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmmokvn.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xecfluvw.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzwqnkw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hztarrqf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vadbjrfg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsgwcbd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tustyebr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egbjmjgs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gumfdgrk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmogaqz.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvpakwx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfswntba.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbjkjml.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrxohyz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhednxus.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmncwycd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxddvvrz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2svmjiysj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvjxweg.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2jerkhgnb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwogxcys.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2efazjlmm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdvcads.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlviabk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmqbhbn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzljhjk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlwpvpz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclpocdc.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bkptipve.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdskjmj.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpbqjab.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdgutbt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbkzfdw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrvuwep.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ixquyuut.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnhhtfj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2szlhialk.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2omernodp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgulxey.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoqrjld.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtivkhas.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqfcrfr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiqwaqh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yphsafgu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhtbugk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjargvhz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhdsdwn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgojpxs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwfhgje.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2erwwejni.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlrzkzb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhbywch.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtabtbkf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjoqbqy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmasosk.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2oamkvjzp.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdufnnbg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyempdvi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwtvhru.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpaelen.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyuvvzw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dimhmzel.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2igfizkxl.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nrravwfl.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ircshzbh.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcrkuxx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2rboiwmfx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iozryqvp.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkpcsey.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmjdcyi.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoybimo.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ixldxkix.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqnqndc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaaugcr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pyestzhk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tswnascg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fivcxwqe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrcoxge.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yatnythv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tgozleld.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aqepyonb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xpncjyjq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkcllkv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2smvdajhg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbbgepz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bkclbned.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjdvxjp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwisrpd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnqyxqe.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2shfzyrcf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuwiolh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krbpzhpa.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsoxwdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opjjjigj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ickiwtqp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqxzcsp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiudabex.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2wctuyyui.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbinladh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eazkaphn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhgjomh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uddmqscr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjvmeje.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpysawfv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeqlrgb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vclmjjso.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmzftbl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kintlbsi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vduwxlkq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fssevvvg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkpudqu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwmcqwv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnhvwxk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xghdzjme.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfdigdz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmkmoca.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmulncj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpwkoks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfpivfx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrjwfpc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpifzxhm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2faoakymd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpghqdsx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuhoqxr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiycxzxm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmkzrqr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnbsfiy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wupmaznm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkyyije.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqmsfjo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dncjtjlr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxtibsx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsovxsd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqbzrco.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ensydwzu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrssbux.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwajsrm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtlprxq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrgdjcw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjzitmp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jawmjioo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxauihvl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwfgbue.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnouvyg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsstjthg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwklpqd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiloxody.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmdfino.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtqbsnr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2emzcaccv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzmrosj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwyckqb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2geuxehfd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2crnwqchg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqbeltx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeznusra.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjtahhr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kdchhkqg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfottlja.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzewotz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yalcujum.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2asvvisgg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2baptgicv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiajcla.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsxgxxl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2orvfykei.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zowvwhey.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtvphmf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfmnfhp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnwcngx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2klzpburg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxkieyd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaabfzd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qggtyxii.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xkktxbvq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgvpkfn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yggswtob.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2spdccwdw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huhxumis.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vukykvqk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpholcay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqmrzwb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xncrnavf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grgdgbfc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djafylal.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qksrtmwz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eozgsshk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqklqihi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkhtqaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjmfxdb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlihoug.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2savaepap.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnsdxij.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2haxxovph.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtiashd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzvckh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkcgzjq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpwaicp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xijziyxm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2evuzujqa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbjywgv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxmgmkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phehddzd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqautyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtwcecu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxuposl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cgznwpda.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bulzxbnz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvduyurs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjdqfqx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryahfvft.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2iruusgzw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2daaqqfsg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inmmhkhv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhfonpb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxkxstq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prxnucjx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlxdrit.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjavnzpo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuitqed.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rktelroc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2abjvbhtd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvlvzxu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvuohcs.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2znhqlago.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpjlfim.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuqajky.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hominwwb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmakwxcw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xeadnhkd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gipaeket.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2omhyebcp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2celunptd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaqspsh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlljxruc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlouihin.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvaebqy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrckzcsn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtmcmqi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfohukq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2otpfslrl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nmerrghb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qndhayoc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eastsani.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wczyabnj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqriorid.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaidvqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2awopqroo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjetnqh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amcfnrmf.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vnctxjjv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2oofpfgyt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrxrhya.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnslrbdk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvywbpg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnulfwqq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uwssitdf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaospmj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2csvwgyxu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjfxzac.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wayuafim.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuybhqx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpfuwct.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2agviaxiy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpbydaa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaqpacg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2nbayadpf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuakuhm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rawmqhmw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwnvgis.html


<!-- 参考信息 -->