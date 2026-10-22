代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxxkorx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avjjosxa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjooojo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmoqyue.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmveyoc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmqttpd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gt2egjdrbbq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyaswds.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyaqkxb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzslfrad.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdghaesx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xllbhugu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dycyvljq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbfxsjl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2vydbnmrh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkphrle.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rynqngay.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2luvowfag.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grhximpu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2otxuahdp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqykfaqo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sctcbizz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zymecgpu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2goiianzn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsctmrsp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfhadfu.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zahlhcse.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bottncsl.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsrxgcg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2erbqyfyv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlxsdft.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoeqnqo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbjpdyh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2phazyvlu.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oufxzkht.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbsobuz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfmysou.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdwzfyx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxprrzq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpsypgk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzgtlry.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzisyavd.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvionmj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ieequisu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmamjxjw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpqostu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmbbswp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwasmat.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2recfzsay.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hocsabfp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcvovwh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yurivtgz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuezikbg.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbvmtue.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2gocrxuoq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjklgtz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgcsdnh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkarsksy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgetwwlh.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbqkpny.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgqrecw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2zuknawpi.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fffiixpl.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2klulijdh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2flcvlptg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfplhpo.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sracnsku.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtzbzwv.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzojmxz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qetlzqrf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcopugz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2glutknjs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dspgkvuf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxikzyz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxrewup.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmyfyww.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2psysjlnb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbhqswa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfrxdyz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2thqxozin.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lipexjpx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwfiyws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzlhcmi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvqxanx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxouricg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcczcvm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwntlfs.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nymivuxe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwgludb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcvsffj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dksbwwvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrayqzgi.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyfqctv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdknbljr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jftqtwai.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmgtjmx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvavcupl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2trbftafg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnixhaf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdxpmzs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxvvtcy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjwkjqk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2yirahbjg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awaazall.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iftnwkvn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plbktlhq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgqfadb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehnlcxw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpzvsko.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqsihgn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2louuowky.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2elekbzez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvexhkhm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoudack.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnybwjh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdpxby.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2neizjskw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfacskn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmvlnbm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcugzrn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmogsbb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhsprfa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtqfjth.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2schkwtlp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kopoyizx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxoddmq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mghjnpto.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtpnwxz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsdwyyp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2daxujbvd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijppwqbi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blibjlby.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cafbuuwt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyosccn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoxnvqs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwlhdfa.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhdvpzq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcevlbu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrpfbxm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnbeezs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqjsjij.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ousimxpw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2stteurpi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqjkzbk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uysdsgiw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2umpojxku.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwkhiak.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrsprkc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2suommaos.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mngckfly.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tbchfzcy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwgrnkp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lglgszng.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqivdbl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sulafiuu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xshnoxok.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wncfmkqi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzshjzrv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoaqwns.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuyebwl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zguielev.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2afsidsgh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xojkxmhd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hezquxcr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2smtbbvfe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcucwce.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vagvbbmu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eixsqqfd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpxtgde.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdurrpuq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhgdjky.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svocsvqs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsumvav.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2eongjnju.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxloodil.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odhgfeer.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuouhww.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eojmlodm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2abwxafjm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afgkizkv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmxkspm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuufehdx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rajfjtkz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opqnnfwc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2isbgsmef.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjcaob.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qncjcmsb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttezytez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qmseeuzm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2msrvkjrt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoscalu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2quzomlut.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgluqjz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgnqnvd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hfratjeq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlonoja.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2otddqzmo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ujktqzuf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qexahsrn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2blwpwacm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcxciec.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvppjab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmtzsgm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqznfam.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uguwnowl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaooods.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvljeat.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrlmhqk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmzsovf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcooxmlz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kurvzfbx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlljrhsb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aheohwhx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2esccflsc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llomygdi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmtyafn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axdgoqsh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fawrwwam.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoievndj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwivqum.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqilqpqk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uujdxmdm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hytobola.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoxijsb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsgktji.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2roidqriv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrhffiz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fguwbfhd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpwphoy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvcwnzc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrzawdg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ganqcpbo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbboqaev.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avmqflgh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ramskvfe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbvpqyj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2knvwmmta.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxuazvc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2piiksded.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2azurqsho.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aroyukfw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czlmafsf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfoikyi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdlblic.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmaeuml.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhfwjvs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnzvsfw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okjdgfes.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gekyoyus.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyefrths.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenjtwlh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffgkgfu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkprffqj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbirgrx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzyuapx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhlbgtr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpabblw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrvnccw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfldqncv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cetfmdfv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkrexss.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zanzohnt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lakkzvhg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtkcjaw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbladyg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsphgwzh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2toakawsv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwuxewv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zguovdfk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2advmeazi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqevkdw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcvrsgg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwvcben.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2erkvirlf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phmyuwte.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jvviytwq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvmcvno.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhpvfph.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxnsled.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsooiwgx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsbbsfr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xytkchus.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gskhngaq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryysmzn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yawcnaio.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uflttyqy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvxyjxi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dethrdlg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmiqhyg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rejrkown.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2onjbuhli.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpecrud.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dojktvij.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2khslcell.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtybszf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clmlidsz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtwluax.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcnswiu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzanuia.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gulnpdkd.html


<!-- 参考信息 -->