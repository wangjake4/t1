代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrgcibn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wypmbdct.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2qniwnvpv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwodiov.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjedhilq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pubricmw.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tigyiufu.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2digcugng.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkrpysw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhiyppo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzclkayf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sltnlwwz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dunbifht.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwdwnsg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiimfxbv.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2amdmstaz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvlkewe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfdjled.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzndrdrn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmfilzg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzogugni.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2quvbwtds.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtljifi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2nrccwqwj.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yipgwpil.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfvtgfd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzbdqln.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwtrirq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnbtdgr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkovnxm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2okpqhtcm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfffnutl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvgwsmt.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2uftaxdzr.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuznfbs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2beurlllb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2njenmkgo.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrdpbrx.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmfphgm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsampops.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cotmdzzo.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlrhbvd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsmsaez.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyttkvf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwzuioz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwygushp.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zojqgdym.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czaeykmf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spnukkwx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxhsudy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqjeeey.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqhgwlc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuhfwzs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rotvldwi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kgafuzse.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2athylzvd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjntwds.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2khiibwca.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cedoyzjf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2odobyypn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2baogmjwt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdlipbw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eouebiki.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxuezpy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bezxiyis.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrpxbte.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fodnwdwu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoemiho.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2alprnqfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkevarc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2baaorsmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqwzapc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tekypzlq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlywxwvq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2okfvxame.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2cprgtgzi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dackdzkb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkrvwrs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2aqniiluo.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvavgsmr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2enklubfa.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgedjyvn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2baeprrqx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azayhfuf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkctlqn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdlzfhu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2aouxauor.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wehwyoug.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopaqtoe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjciwjof.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpehzjg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaapwfo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwjfyxx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbjrkia.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2seavgfsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmcyzji.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2iogunjry.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2crokvsgr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgediej.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhhylac.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxsnwwt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2olcicjti.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2prqzqprn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yodfcrqn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwradanu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxlqcbq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzxsjtg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2evcrofry.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2awybmbcm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2puhymvlg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqpgdet.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbydqmys.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwqhgif.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uycxwddz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtuouib.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzzzywh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkngvfi.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfqcbcl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdozxuvd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmuhttq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djkmqjyg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxamzqv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xscdbxtt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grdqsfzr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opvilcnu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qaodrjql.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uquxdhsn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpcfpbw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtryfxo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsjmqlf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lmigxpxf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnysrntd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpojwsg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxxzqik.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbresxg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2illlhssm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqngzcsi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xclvhjdq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2luynuqrt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzpixug.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zttlnnko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldesflqn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2urbflxir.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfienhe.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2szqwkddk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpehazh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrgpikn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpgssbb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlsfhvb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cavgmyvb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2izbdgcqn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2otsndcsf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tkatbylp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kqanrrmq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upvdsyax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sabrhpcs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhljxgq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2unpqfeif.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2khjfbpxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2khdapujt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2byizjqsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odhonrus.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhzducg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acvocxfe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnbgjpn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwixqjsy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kztrmnma.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pihhxnhl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnfgrcx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blkfhrgc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oskkbzkm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uiolpztt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfelorz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wphdukuv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oktgudim.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2alvdwyoo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kysaelaz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kypourma.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2igvgpian.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rrecuzxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjjymke.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzvgfzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrowywef.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qfklnult.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2inyewujk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hssjvuvr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrdgbyd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqwkpen.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvycsehg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzfjuxa.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmjhzod.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqscrra.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uarnmbpi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mvawkoma.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lydmkkwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzphtscn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2solahyfv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kilepjnd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyivolt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mknkzosg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyvtybm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2avpqweug.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuoixyi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjlxdqz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjorytmg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyffssw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zksvjayz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxetjho.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxdfwgm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iifukvlr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqpcjnr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2syvxhllm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtggmcz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smojmujt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owfazfpn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiooxyhz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2omrgupbd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2txwxomhp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfsthpt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnszxlk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aucmwtxs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laoltltg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grjfaiso.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adrnuvao.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llsljixz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoptidr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmesqcz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loaikbee.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sajqhyxv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbzxqqx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuamkuvo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zklyupnc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoyzdpg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xziaaqtr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlsoazl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzmtqmw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wajipbwa.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iyijfvob.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkdattv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeaoftf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrnemqs.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2crtrneoq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwdlrgj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2letpbcfn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzjdtjh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaymjut.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqgngmg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2oydsruiu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeoilpw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdohlmp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtefckb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqchcxd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgbelfw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxscwnwq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emhkqydk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhdftxo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtkzriz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfiohdq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqwtzjx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enwwiyhr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epfqsofk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzsexet.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srhamasv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thqjnqlc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnumpsq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrayrhu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2waiophys.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnzzajz.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2svktxtnd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2spqgplfm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hkahxmxh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fopgjdar.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hycivrus.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfenkyl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gthqzzau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgtcacc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aprqzpkw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbodimkw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevtwyga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkmttux.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzhhsrn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iurxnbsl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhtqzyy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2azsiosxv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2citoyydm.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eskzgazr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omzubtna.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgodhsvt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbmrzpk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrrfgmb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwxsxau.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjrvnih.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgowxsk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrocaz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2voffsbsd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2svsmtkht.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlfcbnz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2puassuwc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuduhcg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2oqogfqpw.html


<!-- 参考信息 -->