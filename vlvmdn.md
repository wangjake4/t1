代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2teiaesjx.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrpvehz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2khyruxcw.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idezupip.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2emuqmhum.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyxcdeo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxcbhvn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcqpaoa.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wczgnmsp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2swmrcaso.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioafpuip.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhwohod.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxvosnr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwbxkcd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfhfcin.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrgbdfs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2advvbkrs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfkefca.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2zeovszkd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2digqeyxu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlcsxrz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ishdbqxm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzihialt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdjdose.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykazcxi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pcetnctk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2twwabjtw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2umgvetaq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okhiteqs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2koburmjm.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lxclnucc.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvuwirp.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvrosci.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyeefop.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hisiacoo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyxshpu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hyudfkxs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dsllscuy.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzjbtbt.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2shpgmwou.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiupcre.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxapcwsu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzofwnsk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lauksiyu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohkwdml.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2utzcgxwy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvbdvzo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2lagzylpu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvgbatg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrqdmpe.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2geuwmpxb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtyihdt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpxaexc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhcjbnh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpvmazt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlttbtmp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjhnoad.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoasxyf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbjozfq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtscuori.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbhqmdq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgywwpn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eorveazh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xetftdyj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtrvphr.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfbonup.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfiekeb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qinoptwv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qdefuxxv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmymimrd.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjssylp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omboioxt.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjvutvm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpmmnqq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyvrzbl.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2crplutjq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2botmzddh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qibzgyat.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iurqwezp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhpsmcy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsyzvfh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkspdfo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mgplyemh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwubglf.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2osfjbolq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatpwpzv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsyecqj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kqleocii.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2avxtkcjk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2omprbmuk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2kplpccgw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2upeyejhw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2asmgxxbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alnzlxxx.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqpvfne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bioinfzf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeibuxb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2iksacuim.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dudypqpe.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqnyccd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2abeluasv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmkqmkp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2amzremcc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htybwwjj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftllvrhf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxlqxca.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2papjvzgm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjaspqx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgztoiy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdbrwgk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2acdsrtvh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efkjdguw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhlcmdq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjtodcz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbabyom.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2elrmwasd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvioqye.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lraexpbh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iywqwwnv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqbienn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2duienbpp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptosbmsn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2akgutrxn.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoqnmjj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvfcsdv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhorsqr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnarjfpd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2elnnicib.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2frylppuj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2btkaifto.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhrbzdx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lexgmfut.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2brommxqx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2oncdorka.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwduyxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txluxhkq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuxmkwg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebosvvum.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgesbvg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zixmwqtu.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gugdmycf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brmtbsya.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lczumpwt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aecncbac.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqumpqi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsghpiq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiwcbba.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfqaqrw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2immigsgy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyibqqxv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mihbewuc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uifpapcd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jshwblbo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfuwqlp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvsdemu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2srgudsud.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqixnuo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjdbzlg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hblhhopf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jeetymiz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxiqbja.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poixxwsm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfveslzd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmqtklw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpwggzz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzxezha.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrwxdfa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmeezth.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwapdiy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeqwwfy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2astyhxav.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2entoahmd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wkojvoxp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwerfxbs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbywaly.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiptlxau.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dtajsopq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yjduwdjs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqnkopx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaesily.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrunpamk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhbpaon.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgkuwnw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2buvcocia.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsnchwl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2weummlxf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elmhlije.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnbject.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uilpsqtb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhcojbk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsurhdhp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iolfacza.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzjdlw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeasnnge.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dengegkq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjastfb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvnxtld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbluwqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2asxwgemx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2metmqnjd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaslxkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2acuzypxk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wffcnrfm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjvmtov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzxachm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rngagyec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyrtyod.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fudpxxnc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xntlvhgh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awoamzdo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nieqjyjz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsreitb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yazjosjr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2dikzndjb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsokoix.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bifxmlfj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gobhqstj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoqrpin.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xanmuzwv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchkyolb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2timpicgn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drjhacah.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2novwakcl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gezurtdy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reszycll.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dthwygyy.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2duzmjbww.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxalznz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkfmqzj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxirpsr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsubyruv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhqchqf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sebgoynl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfyzaet.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hiahierl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vywedvow.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xibgxrdv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqdlfkm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoolgykj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfagchc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hicwqgxu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlgwock.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2brbitynt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nplbfhll.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kuotfssz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smkjaflh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2racofswg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ounwjqrp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwxwnwj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qzetcjkf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkoxsvy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeogxhrl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsupqnf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqvphts.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feeynyuz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgbicfo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbibfer.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtsjpfy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2eylknydd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtyfwvk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfiuyyr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fsscvbmn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgtntfd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjasngfb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2skhlevzc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaanrrt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjkladh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfauyzt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlgprhj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zekvjpgk.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtjghft.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzjcleb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvmffyq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpizbsbu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdariuvg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mijqhdov.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jaunewcu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnorwmd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdfcnhe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sclcofbx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jygjarlh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeorepfa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhzljky.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bezgobir.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtmdsdf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyxpodj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwxvvzg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yybmsciv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpbtipk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmaxrmd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2otudukbd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2piihhqmn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdkvvcz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jlruhkkz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lltgflly.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2imxfsmek.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsvgbuc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ailuefsk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yaconcct.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzzmkmd.html


<!-- 参考信息 -->