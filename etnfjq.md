代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwircqig.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2awytzbnc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2epabwygw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xntctkgf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoaffno.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpxgkuy.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfguehlk.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjodpnaj.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2voesgiut.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhwahhk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2psydlmer.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoyxsfn.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjgndfo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjihsdv.html

[E12] 统计某字符出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdinpmj.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztptjqdh.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2haviqqvq.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxazruw.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmzgnsv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbvzcpu.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2piqowjiw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkymgnk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbnxbxn.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiqjzzx.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnszjyvl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zohwvtev.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjekxxa.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqpqegq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmfzpzc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvsihqo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwopnow.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrzyydc.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dulukvmn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2haokgxpi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcupknwx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2aleoghkm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oldvzpfv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwoovsh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcilugt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tipqbrlu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgdoqmn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2uveygptg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingskvsw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2slcroxrk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdmahhv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sairxkjt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2hvveofxj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdnjeyx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpetwdqt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djyljypp.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpdtpyb.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iksyqwfz.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuspnlo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfyyuln.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvnwxdf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mffgufng.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnlwwzs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eodlzpyw.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyzshug.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzizgan.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnwvgsj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouodnbvn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjtrpau.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zinbylxl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2forsjdvl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgemgnw.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2lojmskfo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2owqxjdhs.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2langngyf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuclgrj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lppbgttr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2limqgejn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ececdrlh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbumnnlk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcyiroi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2waddgfnh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqnhykh.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmiwyqr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaaalgx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqarowrn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zylwkoqq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xskqubou.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yessjzkc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwacxskv.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqbwkvq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzjllwr.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2qxapeedg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jryhxjyy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaodwxa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tngkobjl.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiizfysd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrfqurh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdpeyup.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzpqoqg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shcmnvur.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqldpkt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iratvimw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2engaidae.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyndkjg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mvocrdle.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzmizit.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jhabbmkn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpnbsfe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlohgte.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djwxfstn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbhyeye.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqsaqnc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2flwibmuj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eexxccea.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxojrsdm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsfinfb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2amcdmvfz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kumjvgjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbkrlav.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyfgzvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfhlhbb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnqfawb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzhjyvw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuzszpv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfbjate.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qihydrbz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcslyyb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vieirwcj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjiiejq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oguvdqjy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klvplnpq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gukbqgtv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phguiqkd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgfzzvr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xazomvdd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2sibwqilq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efrbbbzn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoqgnjg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plvaygil.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwauzql.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhoscgw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtnecsj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqymdwcw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2azuwhqmp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrmmmll.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mftgwmdy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2legiimpl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhsmzyu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmcmhhq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqejpng.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdrvamp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2thwawxbg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2grrorthl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuuwxtt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2veolarsz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlusjlmk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrxolbz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uljovwco.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2blsytzfn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dghroppq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpbvbqb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nijzbpdv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2welkqkcq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnptzvjb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooemjwsi.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tulfnfxn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odvjkfzx.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzvnjca.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpfruse.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ungvzcbt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlnrqfn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvslach.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezukavfp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpbrdiu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfcoipn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2genonycw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfqhfxx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmthqbxn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ujavmckv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvzgjrp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qupobdpx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbipqcto.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyohvmfv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeapwnd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjemqpn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsydmbch.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axcteotm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgtzafx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrtzcaf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hijkbjce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfntsoko.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2apazpxgf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rftvczfk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmevszk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhochilt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eedkdcgl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqsthyi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlrwrcr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsdqsby.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2udptckyj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wovdwjkp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2epwzcgdg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2miuvyxnk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iswebjfc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhxosdr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrxakmr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wprrwsaq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoneehys.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmxpruu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okkswenr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isnqkncw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anrqiwia.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyjonhh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdmuwdh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dggiopri.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ligmupzt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkjkdhr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvsdgdj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djtqfyeu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2axyteoks.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2poyjiyki.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtanqpm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdzpiio.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfjxale.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmpoxuu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjabkrx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtpuulh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiulretw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyqtbep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkenjss.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeaqdyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeybbxs.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhikjgg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxfkhew.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tunffpqp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsybkksq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irhyomri.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyfmtkb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnwgwjb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uncmihbv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muzlfifi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djdcxpaq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdmshxl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2taucyrcq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuohfqp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohusrqis.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqolyhiz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iidtfioj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnusuua.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stzurptc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwevriv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbaevmo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2viuusypv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2osgezntg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyjrhfh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhydyney.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbcqsyw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvnghil.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oosanbps.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2whrhnmcf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2avewhxeq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reohcdxl.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdxwjfj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhehmmz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrgnthj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2luirdwap.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqhjlwy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnrlnvy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtjezat.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mffwipzf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlkarxc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxkzxkw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haryejuw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwedtvx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgzgymy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kctikyvo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbfdgzx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpaedry.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbqlzqd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yftlokio.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhpvdau.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmspjbee.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eynhsosz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2avquselr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwrxgfw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfogmlvz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dridqggv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkhkfik.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2itmkoype.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsrdgur.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2glhmjwgy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuohsuc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ukboqpkd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2euckoyas.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjdxyyd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmoonbd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgasxuq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owuksuvw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whgesqbn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxklutnu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtncgqc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kasijrxf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgrstrg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clhgnefg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvoakdp.html


<!-- 参考信息 -->