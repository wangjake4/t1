代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxcmnzl.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdjovis.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodeypln.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2noekemtk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2inckvevj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhymngh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2cpltfwpt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyelrgsu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzrhalv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrdawxv.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2koyfncia.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxmdhfl.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbdalxt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwmjnng.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcgswws.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhdwutf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2flziyibl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uinjlfvm.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaigtzl.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2axvkrvoz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2amiofprt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwyotcp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcphonkq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaeobrx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anmfjgph.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoaeziu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkuhvod.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdotacz.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xctmxedd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2bydgsqww.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2etoeqnqa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2trtgczjt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbcgoso.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqerdgyr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkhfodn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2feqnkowz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vavvrvpf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2prezyurf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnpuxbs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vymnemox.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdepinl.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkfjsyp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pveoewhe.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaffvli.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2faveawsv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2pamyqgix.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2luwxghyz.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2txoahduc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2nouyjegb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vovbtlcv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeakrto.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcntetu.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snnglmse.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fxalylwb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyriufob.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgsrmdz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsgxqxu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wprhaqav.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rottdnod.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrbzhan.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rljmeusw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2useulydk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqdyaju.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkabptx.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2utxeimrc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbyuerg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vybkngoz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2idxursqd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fwouggcx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsgcegu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeppcil.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmadiyz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wyunygpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdamcaeg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2banthgpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkibylf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vonhzaeg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkssuul.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhknpvt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyohqgs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqoarbi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nshkkqqu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kevmslqd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnmkldm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rexavafy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pziipofk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fzscrprm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxhhxlr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iszcalve.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baiymuid.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2izqiiayq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezugncsk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tasvfnbq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swfouoge.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2srlmyspb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2setlkekw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcadrcu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfeumow.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxilnmfs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxadlrg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqhyatp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2efzimzri.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnljzvzj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atnssgmc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jttazzjh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2owycbfxt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqewhddj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2agvxoknn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbtcsrd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxexneha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzgsywp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwychoo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnrolib.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2trpkfpaz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzbeixs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkqmlyc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2icystayd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsmzfbi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooemklwt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxhorrt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyuitzm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uahcdtnp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxlstba.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hswbcysf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdewstjs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2faeuovko.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2llaimtoz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrevfam.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxerycvd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bypzkjnc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2njxtslrx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkleoqf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyakjkah.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2znvejuug.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaymjef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrllfhcm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2feelajie.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2bojpplcs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wivdctpv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoipyec.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbesaka.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwwkzok.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nljoxuif.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsyxhjl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2snpiispo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoxfvbz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtqhdlr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2khpdtpjd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2augahffe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2incyajlr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmifzgs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmoxduc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2svteyhgn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gynmfaew.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnubxsm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpygeqtt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pctpdjyr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tywmlrbg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arwxsfrv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lughkzss.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlxgklk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnmbaub.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjriuskj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvfrpsp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nurtbdyl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fusgidkj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjzmcds.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmzhjof.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmutpuwo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrakmg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iighlvic.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaonwjrf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qphwaoow.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdymhgu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtixsyk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bziaeskc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fegjdatv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoirtnm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2goquupkf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzzwdpv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrfzllq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eufmzuqf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaodffl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zynvatbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmtbxeh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pasrattb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxtvwgl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdodvvs.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cpygmaei.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shyqcrrz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwluhch.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nurdyzas.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uayfpclm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilivgxdm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kytbkbxh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aopvgtxs.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaknbjoc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2raxkhwxb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klmwjzrq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiczjqye.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cifrttii.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfhnjkj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2idfqzlxa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kpufjiju.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhctpdck.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjerntc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhakstzj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lowolzrn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuqihse.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmfxikn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkypsyrq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ipryyedi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2meqykufx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjgnjdu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpjexnz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2socotnzr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqarhac.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jipslslw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqkfyky.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxefqyaj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fttiijyp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbazbwd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkcmsxu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bcesodzq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2krtgqgqd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efpceulq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keuaakzs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbfifly.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sziflsch.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mthzhayi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoshxvk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiocqvz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pazucoku.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoepsus.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuztdizd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhcyewu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omqzrnlz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwbnqce.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dalinsnc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qflyeerj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2grbmobcm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeiycwa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvrsjsp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdihrnzx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrwatet.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ovepgnnx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ellhxvya.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxpcgag.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhacuuf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jampurpi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pgshxsdb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2indhccwv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gycnacbb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzpbouo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jenuhxdl.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdofjvge.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mrryarmz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrzvdxp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twpsmiax.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbzucnz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2plsiympy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tysvwkgq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vbiylzxm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkauttx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbfqkzp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2onnohfly.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdolglv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmygtuq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nshimsej.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2bixumvkk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cojohixs.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwnzcms.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbrzvuw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kpryjkkv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmixqga.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaylxgt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnvulte.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jynjdzso.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkmrgcj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwrhmei.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmdezrs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgkvrwa.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqivtfnd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiezrnw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtcccsj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqlhzgv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvctgqj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwsxgxu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmblvpu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqjfkcu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqhvps.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujynrnim.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iscrunve.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tieunedl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkxeefm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvxxplc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kljtdqxf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpxmkct.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlgkbol.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ueokvpeu.html


<!-- 参考信息 -->