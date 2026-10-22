代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hkefschn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcahclzf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dazufarf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpbgkjy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrgszkl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuuvqpa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2eksouyeo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctodpmyi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyyacyo.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2jbviaitx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2huigslgu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewctorel.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2suazyxgt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2unkzkdvl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfeweiu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgghmowq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoqrvvy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bixpxzmf.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2caocdnqu.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtnffal.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2apmucoqd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgayvngb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaksvkjb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulclxisr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwwrauy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwdhtgy.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuzwqvg.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzpjikk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkowwlcj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyrzurx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqevbshr.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxuixdn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmvpwte.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfbuxfc.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsmrmhb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2azkazowt.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tupkncij.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhrzlbq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfnmnzh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwdvcty.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlapbers.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpjpewk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2quvpkxmb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxasouk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clcaxylg.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaxpdqi.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dirylcjc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nposshgd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2flokcslz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2poqhydxe.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgxmxlz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoezsub.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ycggvlif.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2gipbpscx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwgbqed.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2stnygvlz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcxjvqr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiytlpw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnmxipp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwogjwjo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urkbhxvj.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ordrylob.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stxcemgg.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwbkayo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfkiktw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzamhub.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsihahy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxebldn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qtibqfqo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmvyble.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2levhpili.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqntytz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xijvggdm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtphvful.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcttjgkh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzavuemn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eiljeypr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgkliah.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjujyeca.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2btyrnusu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hflevmjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egcbfvrt.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oytunbyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvwdytq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzawrcfb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugudjrbp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfulxcf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kaadujoz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lctjmjsc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepkuse.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gvypbzxl.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpstelme.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrojohd.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmmqrgc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gugmhkvz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akxpcbic.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyngypd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbduuxer.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwvpomh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjsyxck.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsnhubt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2seuazogy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lecnifrk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnzsbap.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpktpbxk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2immkmotj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxfdlmq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrepyuk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2adyslsrf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylahsomp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2niamsfik.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppufefkx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqunprxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxokwyhg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpblbybz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeigkaq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2azweflon.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jayypuns.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iadxjeni.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yndrosiv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkgoypt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vorwhhpo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nplvapaa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ketaggsk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzkkfnn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyqvemj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gujjbmay.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fecutfkg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hopotagw.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuhouvi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oykvuvph.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iayncoqw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrtjuix.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tblqiysq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrysesp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2osgfkiav.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fodctejz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwquffnx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwulrwur.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cauuzqai.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpbdajo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wczlvjxt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkmgvfh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxolkux.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvazzbbq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaohmgd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqkenrn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jiatiacw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgucgela.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgmpgor.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2guhjuvgg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2awnappil.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlqfclq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcouymwg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyopxsah.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2scwrlknz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2riszjqzs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkdokoo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxfynla.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyubovp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2unrxfzmu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvlxfql.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmdrsjd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leipsgmh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmrbtfx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cuikjuzm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nolmncwy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kigoamak.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiufckw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2soycnzmm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifawjvzg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqlpnzs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnrvpao.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahekybkd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcywsvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmksdzg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvunyqfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiuxuxa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bklzxwao.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrkosol.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2sehpiecq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnvwaes.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ektdvjay.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2chimtcan.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2khbfqtob.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyvbpdf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mokyerxd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2amrcukur.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjawmre.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnmgqox.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2atnukezr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2asbbryus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2votltonz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ssapohap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzdwcnb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rppbacjm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2squkucny.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgixlqel.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjcvmzw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csxlomuf.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emazcaji.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdyborj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyzpmjt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkizsqz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmqvywx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzsople.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjkyzhs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wukskqvb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrydnsg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebemyvyd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshiodjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eljdajdw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjkwuvt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnvxdlq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2svtaszxh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdyfqfh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaiwzbw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gonnprhs.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiksgife.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgknuqg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdaliov.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2keylpqpl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2neptljlq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzmquld.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlrvwoi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqtujzb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvewtiex.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlttvnvw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpvruqw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgmlkxp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjipcgtc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmdjjcv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2imjcwrky.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvytqqy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeoehfi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sthehdyi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2filhgjjs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uucmspby.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwecqfjz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcuhcem.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxixsej.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmxkakl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyemzaej.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qraoozdp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gamxwzzf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhzytgf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hodtkzfw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puffndft.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2alkciskt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhpebia.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uybbxvta.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uaowxick.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjhbngx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjigaxsj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaqckce.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pdffiftl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vrttsmlh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqppqcyd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sezjvdiy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fxljoxas.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcmwpec.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvphnqk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lttbmuil.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwknrpv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuicdtk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaxgmhl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gacrbblk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lximrted.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtetlmq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqwjahy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzsaeqy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seywrmpl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fubyhfzy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gufxcter.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfkpqir.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2febemscj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tikjqhun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnaxlhi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wrienmbr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxuevdd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpjzqcx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgsbkle.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nghzyajr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsciorf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbzzjmz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfzkwsv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2neqetmlf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tybzofrw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwdppuq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krawrmjs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeuqali.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyatzkk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2avqifdpo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xckovufa.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfgockh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2orgnepnu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zreklbmw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcxrwle.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzucaarw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfivihez.html


<!-- 参考信息 -->