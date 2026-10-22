代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzietvu.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2elcshqvz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdouidc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydceggba.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtwbwjk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sendohsu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2exvwywwi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uurgakde.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbkhmxj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iazbrkiz.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnewdah.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nojeprnn.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2zynwhcty.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnueqyxd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiousnqe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxcqlgc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbveoqj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzbyfct.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhdntzk.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbztmjc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsllyri.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tinwkqav.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqaudvv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdsqsla.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtwgtvz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvmyfcu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2aarjejfw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2asvheyye.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uangdohc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2votczzbo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeegzjz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpissdhd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkfenfn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugovyld.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbpvwup.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnwfxic.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvcrjno.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtetlrr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2naddrqzt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vofedjit.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgmzvif.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gewrdspo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2umrtjrti.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkajcle.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2tnndqiye.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2zafbvfxf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dusslprw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuoiqmv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcbekhi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbtwlsx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjumeadj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyabypzr.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfdwajo.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwhvkiw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzycisph.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2nermvoap.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnsnnci.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmiokll.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hapfhptq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2leshkrqe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtpnkad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgcezvw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hapiqakh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxtdznd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcuescn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdybusqj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nairprmu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bsboipvf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nymzrzwt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgelrmk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2drjsoshk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aumgkjzu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rthhvldj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzonfkcp.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwilquo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjmhgup.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuoqxhg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxkzaoy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fygtcdvo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2poexbpee.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdfgkto.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeetfqv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiilpio.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftltplvs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpquvioy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djorphcs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rynerjlj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gktvnocp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvaahey.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olakielw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkcwpur.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgtzxlj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkxbkjt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkhwgea.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnngplpm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjifmwzf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqeahit.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlertguk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkjhcwi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpznrcj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeyspmq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbdajld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2colalgrx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeuchfw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhnydet.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdwtuuu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fplwpdge.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqjajqh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2prvqrgsk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwynlimw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2spjhssqh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vunatgdl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2appvofyv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpxgwmd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2elfwtviy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtjxjbf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2shuicxts.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhozsdja.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkkzzso.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blaxydyv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnswuuib.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxratgp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsimzrcy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zelxnskm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrsyvba.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irgsyeoh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxzsteo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hagfwmqe.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxthcdhi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyghgrpj.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iswjsjla.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfdntid.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2angiygpe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ahslpnam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjruuwa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2otudqxed.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzslauvz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykklazba.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fomhkaei.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2joiesblb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrvxegr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwgcsyx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssknxicp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoqlzcb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2upxpiiuu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ercbccie.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2siodyuce.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxeltuh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkzzwxe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kijtpkrj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hexfrgih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2akackshp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmraznp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsdqkkj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2akhhewhb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkaphbn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfpsrak.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiwejry.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqojnhy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lohnraes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpcdxul.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzglfhx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbfvbmb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwulsrim.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vflopasm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwlrghw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iclkfwxe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suzkihnq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjigiyh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zijztbvf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2deyilbpt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmelprd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlvuuuj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2meexexoy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsqqtjo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaqooar.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrqxvto.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrcfocc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wnixdyjm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2umxbwdmz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgjsaya.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcikrvn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrfwbjc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzfyhdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yncqtupo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmcacwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yojgvkct.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2atkpthsq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhbzktv.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiknths.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpadccjr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srohuboq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqberjeu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mitfqzhq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqxzecm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vneeotsz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrztlvtk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2eipclgii.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fixerbqy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdpwqdb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jznbfsrd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmoyvnn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2luoyvsgp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhwacsh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrfxgig.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bkatlaxz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcxvocm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpjxegg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qctuxvjh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvndcctu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqpmdzv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gqucnjgd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2damhrgfw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxudwayl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcugjby.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eljxwtsa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgznjuhi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgnqepv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlkkeol.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pagugljp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcdwvya.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2opzrmylx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjbbtai.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiofgpi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhijfck.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkfxitb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oihqride.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alkpppme.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flderbjn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dvatqzpo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uysfssvd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gthtgdfp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrvefiz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nggzkeyy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guedyzxu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpvtyjr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvrebso.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ravexqxb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2itepfftk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ectrpcit.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuwpmud.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjggrhd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2aubeguuz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bthfukoy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtpfycs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqqjvkt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyobvpd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxzlpml.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsyqsuw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvvppjm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwzylmo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjochdd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkogyiv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtcreiw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svaapjmc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bakhnzwq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2luffuxfd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqznxcp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgokoci.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaekxuy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2cjveyyou.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrbjwgr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2imubxrhk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jepnsdhs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tckrvyob.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaziqsdf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kymilixe.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtonego.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2omtvgpfm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyamrznb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2olcsohee.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqjobcw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2udbbtgec.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dphnvtnk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrvwmpj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2amwvdytb.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2paqklowh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjvnbws.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrdgdpx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwjynta.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmclhvap.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwsvvci.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vllkuoav.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pprjscfx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2glucbbci.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoeytln.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqbgwoq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwagrqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhldetz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxobddh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgqsfcg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdialye.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnlflqx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chpghrdu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmktoylu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyejjnya.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiuhlnl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ypadhszm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzhdsmt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cfncbqpq.html


<!-- 参考信息 -->