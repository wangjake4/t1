代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2raxamhcg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdozhyfd.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2huuogdsv.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uftmtnsi.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2otqsrjlb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2iofftdnf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2oussvkgu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmhusjk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2szyhmcfl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpayyjp.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpvzlkd.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwfsjai.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuonici.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqchwelj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tudxsyka.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxknbued.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzneucg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wujnisan.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2twmakeje.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqsagaf.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjheubas.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2aexujkub.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrmrqfo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2deewaefl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtmupre.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsyynba.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnsqdsw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvuxoiw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkmjink.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2beuihqnu.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqcmllq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hodtvkep.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbjjmzk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmcledy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyavtiii.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxikzilf.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2qazygipb.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2hcovdwma.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2jksblphs.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qluxprvm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzccyhx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czcmvtqc.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxzacdf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnlgkaf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oatalivm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwkijmo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odyepvgc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2dyguhxbx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnmknnk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nosqxgsg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoybztp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqfpxdl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdjebil.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmpbogr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bjidhdpx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvwqddg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2erfwueoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2osurprtq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dozolfwp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vmigayjk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcdxads.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcxcvij.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyenwsvp.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuefkpn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wiltvavy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwxjvap.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjghjro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnhwvyr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cffpwcsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2wscxqqoj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oppfvius.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qusldkrv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzegkvcl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgogmzio.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnypbww.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmuthlc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozimppbe.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsetalpr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2sqygdirt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zygxfzvo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olllrvxe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dixelxld.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtlyqs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlflhtk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazkkujv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxfsxpk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tirbxefh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvuxjip.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2waygcprz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpwqhwx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2agldsyfu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppedtwak.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgvitdy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwpnmaq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lccvdcpq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxmkzlt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrogjeq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjmqacn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvykgnlh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zckdkxpi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdbrpan.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhxvnji.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xveesjzn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxidqyy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rkunfvzb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjwwdlo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uigrirea.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crlumngn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fczsattc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwekozmu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2woxeoywb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2duswwjct.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onxdesug.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gthkcenr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izntigbd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlmsknr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgawsmeb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsksnntf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxfnjcf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmklaemj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxtuizl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzehces.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayttkwri.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmambkep.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqlkbap.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2emfnjyjb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgvqjwo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdfaeym.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhikyzo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2izgtybuw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2eavdtanc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2olkjzklr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysxwbbl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoholed.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2etmodzmo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqdewjv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnujhuyp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2njmmuhai.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbxqsbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2shajoosy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kidddegr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sixfmdos.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yucvcpmk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkmwvqd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcugtom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnwugga.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yelxcxnf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stpvpods.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wlccqaat.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfgzecv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqbbquw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2brbileou.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdyapri.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckifudvv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjlgxqu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tebdlysx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yokutnwg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iskqhegr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2suhdqmuo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkyfcbf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypknpmke.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjtuska.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqhpmxm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvimqlwn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhtilub.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkncmbp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2abuengzm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrpzlcx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2thrccwqq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmhxziv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhpmcwo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkfxeqp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2khidkxnw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sksvgytx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2evdylzeh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2onvpcssh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwkniix.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bubrczua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrfcijk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhngfum.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qisklwsr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzfrprl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksguonqd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvmlhol.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrustkr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbroqzrg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2izjpkdul.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dweizpkh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krvjqgei.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fznfwtlo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxqakhi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyamhcvs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsruevn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjxyrdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uirqxriu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wouedyyd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwhjfoe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuyxivl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yplqngok.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbikazsy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bxscvexa.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyiqpdc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrbwobx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqmsezw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtlcfzf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbymehl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2avlzfves.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiegnvh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvukqqdx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edzbwrdl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uicqicao.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvlnxwt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrnyvln.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxcllxi.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2keeccegx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fplmkrnp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbxotpv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oklfeyhk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flqqsifm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsszdwfa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmxnmjz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qfinrxlj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdanoqdr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrssfks.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiatbxz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2oekfgydp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elfowont.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbppqku.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoojuzeo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdhdreu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiqorat.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmdvmne.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzothqn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oykrjfaw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbfrdmz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2puovfsxe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqphsftn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoezhfd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2urcbydgp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxgzhzf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuchowx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydahnhdq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbukswn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xoycfihd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bozmujah.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvdnoor.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thigkqdi.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eonemadt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiughuy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzsciql.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2berhgmjv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhqypdi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2spmoljet.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gesfqash.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkfcndh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaftort.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajmsqki.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrawdtr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcrqwdf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etusrsty.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2utbfbois.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yahvbdxq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ehigfhli.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2faalrepl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtcvfxb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2movxotxc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2boxqdakw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxvtlvh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dycopwkc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jassrisv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyvucsj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilceeavn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyxxeod.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aukkjeqi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmthpwx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2blufmots.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wtideovm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcqgrtr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcdohev.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vdukqnqg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyixflrs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dznswctm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfjlkqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfsasrr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwqdqtw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwymnrt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpwllgu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rynlzkdq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmykuye.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wifejqiz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjbeomg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eivolios.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlcdoep.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiwdqgh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeklxsk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlpxnqj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xonsobym.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpfmcao.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2dhytsmpz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsompiap.html


<!-- 参考信息 -->