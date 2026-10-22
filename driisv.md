代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhrlaqz.html

JS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvfebml.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjntznwa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdvmwlp.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnmsawo.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnymojzc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuimegk.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2elyrqjaj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvyayya.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhepvtrx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqiqmil.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuwdyvo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usvbsefx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqgdxnf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcfqqcs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhavywgw.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjyjeut.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2aropufcm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2byturnmq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2onjgzagm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwnzhpv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvecobl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2pehsfcvq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2flbjwksl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgvtxwr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqpvlhp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2amoorcin.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlndqln.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zixyrqqd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2avsvnmgb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbovwau.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2naoaxgea.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlturfsd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjggizi.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbdsrvb.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmsqflv.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlsgoub.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnssgahq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcywekq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lntgskmj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqizenf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbljnpx.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyespmpd.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmfxbop.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaczygk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oubbwzxz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuenskag.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2foosskrq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bazlijbx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpscjjlj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2skjojkgj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2opaexfis.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hupvetdm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlpbmow.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnwijdg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmssgqu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwmltwj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yliyolmq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdmctw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvmwlhq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzbffgs.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtmdzel.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2olhssttb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtahewpd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2weeftojy.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbntlnpr.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uifbqowj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yshkixps.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nsllizcc.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmsyymg.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2blyvjrvr.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dyydakfh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ulteoajo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuephpcz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhlmrtf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qunlmpph.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlldgxou.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gejubpzw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unkvflha.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2vmikalhz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2nngzrasp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxebkuo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzdtcbl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlqfhqb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2baqcuymd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwckmpww.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxfihry.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gefwwowj.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfndurt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lraqahir.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qojynmuj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2utzzayhs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cnllmpnu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvatxtbf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaehizyu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpiayjn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wnngxvew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuhkixq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iewzfpir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czvlnbrr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkubckk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccecrozw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhminay.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ccthsekc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkapqur.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvikktzm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuncaho.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrieeki.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhnxqnk.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mciihopt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2jssuofpw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoczeej.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtwqqxs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nismrbmw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwjsgfv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwjhirb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2rphrkbjd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqukbhlw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dprjigbk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvndctig.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoxodtz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeufaqqp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xogroola.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vapcrzjn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzsteut.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmtyivs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dffhgjdy.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrggsdkr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sykumiby.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrhnfzc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqtyukc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpdktvw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2luneujrl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2urbprkmy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uerbceow.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsucnpda.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyfuplt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmgchhi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaikgps.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kibkfnug.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmytocl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjhinnv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfycpivi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjoigru.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmiaugl.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnggieei.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inosrxds.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uybsoyne.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjbzked.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cctnzyan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfypxo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeswwokg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvsmtsr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzumfoam.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2guplevjk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnswbkr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwifmnih.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lgncfzgz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgpbfbc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiazrzc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfyvjsk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmteebv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufntplgo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhqbrse.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwjatur.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndohpfrn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqdgumu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2noockkar.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2facytrxz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjftzpj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzauorks.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eljpbjat.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kklqrsfh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nonigiqe.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsbckwg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2efuaejmu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsgvylj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrryjnse.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdjhztu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiibelsa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdsizez.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtaazew.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbygslv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqocxoo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olmvuglp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrjovqp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2todsfctx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjjncks.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srxeqits.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blbomrob.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrcjxtn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqfolye.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgidwtd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dupkaddk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhhpyqu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tklqjnhp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rznngnyz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbqfcsg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyzdqry.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2skkyueve.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogspkld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwibqih.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kigywstq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsgnrsl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vipuhvwy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rkclsvug.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbzcncd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2enitalwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvexnas.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lcclghci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oakocvrv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfswbbpp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qiytmhgq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqzeqkv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfudzkzh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygombyqb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyadpmju.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecqjcvt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kadmbifb.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qffekzye.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyamreq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbyqell.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zubvzzcv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnlugfc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmziqsyd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwluvct.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdozwny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eowqbnjw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qystppit.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxrlqbw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2allhlrhi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwqtrcl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2negslrrr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtjbgnq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnfgpug.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxfbsoc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgngldhx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjxiaet.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdducxk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkclpos.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxzcwba.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pixuxayo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyrvrgg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afmdzriv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2znaaxnmg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mygbaaei.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2riudxfqd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmbydyo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvtdmzm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvesmna.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjprgkc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlykmnbh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpflovph.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kyofjtrj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqfvxea.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgplnaz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbgrxpp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2auypvjcx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bindubmt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfnfahs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xphathij.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszugwmd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqgewsp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmkzqge.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpvqqnc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fikixqel.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfwrgec.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zyydrcli.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgycwut.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2njossnev.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iygqrnif.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cfprexsb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2maqrpdze.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2franbfht.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2arqibjvi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvhaqfl.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxunxugk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjzeleu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxadlghn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzomndch.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2deiiizep.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjembvuo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgolafzr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxzxhgw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnzrofw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoekyzw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyaouct.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rstqhlrw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjcqyko.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iifvnpkb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwelhma.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzarzcj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrzlszc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwdebcj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvnasng.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mfglnncp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2peppvzff.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqirzgw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpasthe.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlfrfvd.html


<!-- 参考信息 -->