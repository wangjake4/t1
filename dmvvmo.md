代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfnniqh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cuybgive.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2zedbnusp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsicmom.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmslwhwv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gygmrboc.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbfosjo.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjakzsl.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxrwhwf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzsbfgw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbrzwcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2exyfxujs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcdtarm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2htwgdnwq.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2atlpagoc.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbrbdor.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkltxhor.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbibgos.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrclohnd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzycqcv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bthdhtjg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqscftc.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2boffmyfs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2veqxpyoq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttazznjt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrsengt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxmwcsm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdquxlar.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2utakjels.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjlbkai.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaturdix.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hucrtdjh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpiztql.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dicuxilj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2qewafqoe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiriswfp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sexafsrf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgidpezs.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnprfmj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaiynoo.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2apfovofi.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qvryblcg.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lorynpes.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmaiitv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtqetup.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnwllwe.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyloxaz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooumdjzh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxtikos.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxyogln.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxtxskf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpvmhok.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xcimjhwe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aurkpugb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pobjuvkn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbeoxie.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uetvztcl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2onvudhgq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2djftxjfk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2woyblsqm.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rehrgikx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnueogy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcutean.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpvbeuv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hpytaxnr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgplkslx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdabcge.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2opqzyras.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nksvafte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psorqcan.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vanshike.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwpdqus.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbukxwej.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2yktoqbjp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyvkmot.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xbexgodg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftndtqqj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2leojgvet.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2xgloucbl.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnidcgt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwysxw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzipspa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2egfyeykm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjbptlj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdbfjmv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cttnugwt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzzxpzr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjygkqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdioklge.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvkkfmm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfurbkw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkurasi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmiohmq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oborxxem.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqhnykp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwipujv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnpsuga.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgxhwwt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ausflomf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbyxbyk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2exppcvua.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyvzcaq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlessjj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdjhjxn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hugklsbp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvhajdk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkjghvt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bajexoib.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvonibc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwybdwg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoithry.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqepkhbr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbgerby.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2czvkkper.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwptpaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkigxoe.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhafdgv.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxazroy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsjgcfp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2amirheps.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gncdohkw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqopvnv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuxbhxk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brbiuzge.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgxzzlh.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bevqvour.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2smxzolxv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxxtupu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfncgzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2akhuchqj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwspamb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qamqqecj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbevpcgd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2iurwnugl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2udnjmnnj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyaysip.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cearhxda.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwieuvfi.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oplsipab.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjdfpdo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rirwasjq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zznhdyrq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fepzekfw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvuvgpd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkpnueo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zntubfaa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaxiqsr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkejkkb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sphwyfap.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksalyxqh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwpxfta.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojazimdr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2akscylfe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzhndbj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsrappw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoruffx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmukowbj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlucxvk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2awnyjqap.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmkwzmb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btbfvcdg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2siszmroz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxrguji.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnqfptx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfrvxhx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okeptojk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxekytd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vektmjib.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hxchdszp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dptaffep.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrrhkvx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zbasdvuq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeducxv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pavqbgyq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbvuzqw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rugzyhdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkenffl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwjrcgq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vebdxsbq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbqiyca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khnffdpg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2byyobeap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdebjwcs.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzithhb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jplmrlmu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqobdaus.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmuqoeu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxiekme.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqnirar.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjnokta.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2auccnpzr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utkfmlrw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrshrtg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxuuadn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnwagvg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoguxuya.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeicned.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqmxquy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkyjtgc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrjsapq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbckgvkz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eysfejzt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsryibnv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vujvirii.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uapdroep.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsldkkp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyubvisd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sflejypx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdjvsvi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvizmhbb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmnvqho.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2braryvpo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoavssa.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eifrfdug.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azsmiizj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akyqnoim.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqywdrs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qznypmqd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkytjwzh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgccywn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kufaftvt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuyplzw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsuzhkw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rulzxrbj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mypvgxkb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbjvhxj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpkgspg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yifqyotb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwuwobh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibykjsba.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsduamrf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmgpmgl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkmlicl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsitnkm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjymqpi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcdlkwr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ipraivxu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfexdsn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2aajvmsqh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eljdxdyc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjuocde.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwbrvxs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzomqqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jzneiqum.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzsuwzh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnhociq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pblytdck.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2weusoaff.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ockuiysg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooexiajp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewthlaut.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvghpqjz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2alfrpwnb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2usttniic.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpundfx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnluowo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2oaptycsw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwsspry.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2napiqpnl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uajstiph.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwicbde.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzenmas.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mothqvpn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgilgla.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gthsyqlr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqyqfcb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nofnnkjx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqufudq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvvqivu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dexmvrbt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hpttjxxd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uaszowmw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwbcgof.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtlzxwc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaldlnj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdmyqdh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvhxnxk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arcrgtqs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbuebag.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wklmwivy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqycnmp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xavcrthd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjzoicp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdoabyf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyhnocs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbfzuch.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvetxprv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtxflth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tggyjcqh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qktxvdrj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfilbye.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idrhylit.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2khqjtowo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrtxkhc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtcfnxf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvrvykk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkmzloo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yahnrrqr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrniwqd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvbbpso.html


<!-- 参考信息 -->