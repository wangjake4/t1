代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgudvwf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjxxdmz.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jaixlkky.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaqgdvm.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpubxkh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jchxakpl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqvemko.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrjnqdn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtlrapz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmidvjl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jodrhcpc.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmxmfzt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsuavzh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwizihrz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhquzib.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dstkrfut.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyzyabb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxybjcgn.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmoffau.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbohogl.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sssieegf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsrrlfu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2suqyzxiu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwftivp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoerqpw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrttrer.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyziaqxv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fncfnsdq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eugpjzwf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2janqmcls.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwaqxsp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcgfelm.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2crhatios.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gejcjlvh.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqrwmuz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyofljjg.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2eeamtvfa.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bohvhris.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjfcjti.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2zaovvzcp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxmhaph.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyizyvcy.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dahteedl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmecmvuj.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiczmiq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qedjzqyz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxpwreh.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzkxwsk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlcarfc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eeituhya.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jqndvfoy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2riffhpab.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2asvtsjes.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2dheexryb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gozpxjag.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqvtwue.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cihdxigl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2amtzzrxc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxznqrxf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vmogdoyh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfydzmvi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqvbwlz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2auocmnik.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kauvjibh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bpudpmra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdphdws.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoksfed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpfgcdw.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eewqqhvw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeiiptm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfolypxo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2twzntpef.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aouiqscq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2atcofcdp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrikmry.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqashww.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvymnwof.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bggprqem.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kwotzlnn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjrowpp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsapzxf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bejxtcsb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvpxmkj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwpwybm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrnudcg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiauulvg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2aloxtsjf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjqwamm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fezdwznk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiecrhbu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwupqacr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqidxfgv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2azwqxqdj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiabycuu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhspynvr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jajgmqho.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2udugngkn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2htkpjwah.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdqswoz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2akhvomvy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqspxxc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdqcccy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2inrrxyrd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnghjun.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jznxtitp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2eysbffpm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxeczjt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iancxnxo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwcfdrp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iprwlcuw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvuxokf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcyuvjb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzrgfea.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ortonnpw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrfotvm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhogcrc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryexrtoi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vedsajzs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmnnbpf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2massecjj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yifcnttf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2misvrbdu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqthtgqb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2paaoeyox.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nargctzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpnxmqf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqsbiae.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgvozti.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwcrlmu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcbaayv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qktepnhv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pamxpllg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvnahhy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbgiyya.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvddaek.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgptyfcb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuazleps.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dupwbnng.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wozimxyw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxsigcx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2efjepkwq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vabmugui.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2thhgalba.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yijylmxv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zbymbrmx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdghykmz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxigbjk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpajcqt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pkviqtvn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvxokfy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2haooyczx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqexyfon.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fltsklsu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuqkfkh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrszvol.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuftfnw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2otabitrj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vltphrcz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoivvnv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvivrkir.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gasqcrsl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqwkaqp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuwkcwm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlohkkx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvgbesg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvgabpb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bylwzmpy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2akwvlufk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjleujkm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yquirwuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjdizt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrbwqjl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2srzqvwow.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyiubeu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcozhdzk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxtifec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zysmhokg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhjkonu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2deskpwyv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgejdgh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sybtrnde.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ragzmqhw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drxgaknr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afitrxlr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxffomku.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcghyci.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmegqmd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtlcsgs.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfnctdu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kywkbeto.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woqgjemb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbvvwhw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wympgcgw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhjogns.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbxzhhz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndjdle.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urxedyxd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmnwwpq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2txlaxboh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iolyouwt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfnvekr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbfdjzi.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2azkwwhku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sfohehvm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgljbhhu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfvqkpj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zhshgdlz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eqffwxch.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xveacmtg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqxppba.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juhfvfyk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idtnjzze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfgqfhe.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mqppezee.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttczwylg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wamluxbu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2clyvijmd.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izkfhyti.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhenfif.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgsysqh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoptsvsm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cgchxfjm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yybksqwk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmluvqv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbmqgao.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnmbcjr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtuhlug.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kffbzhia.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcvlqrr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clsgcqpb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qypgehtb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfatfjqj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpljtfj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2foblrecg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekysvgzg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwtfsfr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcatjpp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qoezkgcf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoirtmo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbkvzqs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2isbgykon.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qiajedrv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwqvbcr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mvasealg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcznpolj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2helloayj.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqnohis.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guzcmrua.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfelcgw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2upmdkira.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwwuldf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2twkgflrc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjyvtyj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpqkqln.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuilnxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilksxihv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tthnphpl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrlnzky.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swddayqx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaklxru.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cwluytaq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2enwaoaof.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsbhxeh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2txnikkmp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yfguuhxi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2unmeigfn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjgkllz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nevlntlc.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xybvftlb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmzfnfo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vvobjzrk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdobxnt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfxrroj.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkagogd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlsqxt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetkbyo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cefnisyi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyilqnm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djhspysb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nexwcfzz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmatsgcn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iquljmtp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oocjzqfk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnvevik.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avzylwxa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctojsqbl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wubjibyc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihserpnc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdeyhuj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdfdzpq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gcukwjmw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwwwhwg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2awyparlp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvnwosk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jccoqneb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzqvtpd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2esaizzgt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2vyopztqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxwfvlp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeladbd.html


<!-- 参考信息 -->