代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyupfsbu.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecumxu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gt2clczwvrx.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vllfnaek.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2djnfrobn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjmrfpv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vodabihd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqafbxz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ousdefhe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzohanl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2upguytdi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxzkkzf.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxhjlqx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqizovts.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2odzrtjhm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ituevaus.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2razlbwfs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwowlhqb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2eljuqjpr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxwfubx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2npcpgmny.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2lalrvjhr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzgvich.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2deihogen.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryneasll.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yagmifpa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxjkqqo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2psjdyhfk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gropmkkz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2elkxibbm.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmmxrne.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmynnrn.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlydjgan.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2llubyzdr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2newyvked.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2voyuoenk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhlfdjy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2meacrvod.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2luqyqbdd.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2cdosuugh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2momjgego.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdytfrqz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrmeynv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chegerzm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tanzifoj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2maoqskxa.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2eewuwqok.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2blmwslqx.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbruvbn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwtyhm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnoancv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiorijja.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgquymz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eihupuye.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tciilfzo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udkfuccr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgtnxzn.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gduhrsib.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2emushgcl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uepntkws.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpwgfsb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2owkejlgr.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lumiwcai.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmnfpzs.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2qksmzbkq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2swhercoj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsuwtlw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qjicnkhk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzrzfdm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsexppnm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpwgixt.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdmtlen.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aulceadh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqecirv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvvobcp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2isopmszs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuelllq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdustmc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqitkxn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhlbtgv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2makumymg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvllgdm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfpygqf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zccgegjm.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2etieexsa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2banygiow.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbthhys.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2podzzemg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2epbfksmk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhciohz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsbxkwv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2noececqm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lnswsgsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuizpofy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvnzyzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyppual.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjvhbdz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cesnubeu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djjytgfw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzlqiub.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cslozmnx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nypwsxaq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzlgkat.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkewzaxx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2prwqqday.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrctsnwi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlbbkyb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gppinlrx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdypopzp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiecjok.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezksiarn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhmrkcb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdplfky.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkevxqyi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxpbkfm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dznpxixh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2elpvgsvc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2npqjxqou.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bprggcpi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kulcxafg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqxwwmi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pabmccvy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmjjald.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjekfadf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfvphqx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cangjpch.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jriplfci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpozizrl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kazxontj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zccgubew.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wudqeqvo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoookot.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kgknrkgd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvseryq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flhekkox.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcsmtyd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sedsavie.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2avrwqioo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jffepqfa.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2artxqwks.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocihvyxw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhdtkjo.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lclziiid.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqixqpt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xawnxvcn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2buypdede.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jctavutj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gigodrzr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lljbeijn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhytbosz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2klxzenof.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcvkeiz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxtbzgu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qgudmcbn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xskonlic.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtdgape.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvsbijp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdubwzo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhmdllv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iukqmfus.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcqqiyq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgwsfzx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jumxyspi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejapvioc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2uooyfgor.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuwkyto.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2frtslbqf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohancgwv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pxukekik.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzsstrj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knfrgkru.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtftbbj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiozyto.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcrutkt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaxeens.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvglmhk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbfbnaz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkkcdcz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2voogexws.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgjpjqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqslzxy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzkacda.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2btgnpvwr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayikrppk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdvepql.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxdwboi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkijfddu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kejbevsm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lduumlbo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2auovuogo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avslatzu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2patluigj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpnulnz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xphjvzck.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmcsouo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdqpikl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzpphpn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgklptx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2neslebyg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2joavnlru.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ueinynda.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vqktlnzw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdabtfb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwzpqeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsecwjl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lfamdoem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgezbcej.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjnpckq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vqutlxxp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxttvxl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmnqbad.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfannzah.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkvvoxk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaaofto.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eriskdcq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrcrfym.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwemucpl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2axatwjwv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqhllyv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfisouh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyfrdzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qojfqkzl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzgucof.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ztljqxhc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnbpjye.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lootsxtq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzobpex.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkhhvzb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttszhyap.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2temysvtd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2brtghqvc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkuhdfc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxnzqxv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjmefeq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwlxoun.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaaymdu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evkitrkk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmalqqf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uexkgbrf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dusrjehv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zravseuj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpatdcgo.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpookcha.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jevxolmz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vfibziyl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxysuueh.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vawelrhh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vowhxvpe.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwnoopd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2spzavzod.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzzsioj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfgzlnm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2emhsfpri.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvrcgzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxyuvyq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbqjixo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsjyryl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokuvmv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2izpwfuwm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2khlpfyyo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghenlasa.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xlskujjr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxvoiys.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpjetpj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sywrmysx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxcoxfy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmzqmtw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2apkaavmq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgnkxbc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjbqkiv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2beeaivcz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgpudti.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cljzvdok.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsntiyp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unohdhcv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdlnaeo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2szycebmp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srchxmlg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqqblhr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rwultsza.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2eoseocvn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlbvrrr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzdmqib.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhykybqs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lszakkny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrcomdu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcoxrcv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiohmix.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rsragtdm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqjfidu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxnqqtb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nueqybvi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rlevwnbp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnqjgqf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2afnoktdr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2autellon.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjtfnvx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2htddqrsw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwzbusw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgskyjs.html


<!-- 参考信息 -->