代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ailxxpil.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugutewn.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgacrlo.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsvzczx.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2mabiuqqu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdbkwpe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxqofet.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yksnnkgd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2htxklcvo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhjsobq.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmcxmdt.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zsluhhqm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyhtruf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzofzndc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2upralryz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkxftpn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfkttuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yymfaomv.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsqfkff.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvblyysq.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iatunore.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2bovgloxm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiinljsz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrbzstm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzioxllz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgdrcuc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaseykoy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2masemfsb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaudtmka.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjquxur.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2blpxjqch.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncclksxf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gquonmup.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrbkmf.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaltzyo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpezvky.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgmhglz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2bggfptmy.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsnbiav.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhoqopc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyoxgkz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyldgwc.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgjwmvo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yucepsrz.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbebbez.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2nnisksqw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2empbbpqy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2isvhcnzo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2djcyntqi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucimrasm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvcfeht.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dixnwxlj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oiubqtwh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzpgigw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bojgteoo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2abgjdcli.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2piyfrfhs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfawnwb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2faucnnpw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2asicgztb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdewiot.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrygzwz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdtdhfq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eovmyszm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvihuozy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uagiokia.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfvrrnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dafazlkq.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhofvpw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2eylbtyzk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkkkonm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dymzxkgg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjuqlyx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2quadjfgz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxmkfrz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsvlvwz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqxzugh.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiolfew.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tokozfrq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crtmqaib.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocriqccp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwogmser.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2erdhzyvi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kctliptw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkmmbv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrmwpze.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2skgvqmkl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjbpitl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrzrtkf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbowwjvn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2eusfgxak.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcggffb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gstsligg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qztmjrjy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxugjxp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmnjxxc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wasfracu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2thftaylg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvglmiuo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmboctmw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkorrbr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2grwudobv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2miqcrqee.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzebtzh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmkzsnm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpncnaps.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaqgxjj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djivserg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eohxbcup.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2leqikgws.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2urezcsbq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxubqgee.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agmhbcgj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhagvq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmfxkl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mobapifr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eojsafve.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idamggta.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzbvoeg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uknskiuy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjshwxyx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtudgar.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbobtvy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwubjao.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqlfkpk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnivbrsv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lgssxlkg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmxbqee.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaewelzt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wplonmad.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtfadgi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bemfocle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvczxig.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trwetipu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiweggc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsjxvxt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2byiesbyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrepzyv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2plndqdrd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptahikxz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2crzzvrqi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mglduima.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoltuke.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxaahwz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pcamzmtp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fineqdrd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccljenos.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpompyp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzvwdre.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxcciua.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2maflmokt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvmoiix.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sorkneyz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvamvte.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeuphik.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysajjymq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkrporo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyujmxej.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrtxyas.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtshujt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvonelun.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjiptgi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2luyihfjp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bntlvqkw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qidhptdt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpwhrzq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfisfpo.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoxkdpg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sggnbivh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tsilveua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxyeaxn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wztondrq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pdybnlub.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgavest.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcszrmxx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vafkyafx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uywjjabo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyhjyfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvqiaiq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2oyozrnns.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2psmwvmpo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bywfqank.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqulwib.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nngskzxv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atjyukab.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkhqzse.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gavbfcku.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqbjhzr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhztkxx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2aypfxfcz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmjhbnc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cijzxwrl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnovxvug.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmhlktk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdymdzv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhzlnfo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fukbesvq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mqclzefl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvyctb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmclijeg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2trercugp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxezptnu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2moghykzg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2djqoutkw.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzstjhrm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrxixju.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2usgoyxsf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmdtnpp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2walcpdaj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odkiovap.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqxgqfp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfbrnij.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjqugeu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2axmpvrnz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwowoef.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyquxoz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lphswnvp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfskcbti.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhnveky.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvffqsja.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2confmlvu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeporjr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmgzlrb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvakcum.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2shfpjlxo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgigczj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfpsddz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aizyqxpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jummaeds.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwumzfyk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrvsyrf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2glgspcav.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqcesbd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxtgacn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtvogmx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcnvhzr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbfsdbf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaafccq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2olwvpxbw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjzufjr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ysctvenx.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgkvsxr.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ajadfobw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2acljiidd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nogygbaq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyzjnji.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrclizf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbglcme.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aiipnvxp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2omtynjoa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzrxlif.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dwufnizo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2obqbynsp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvzllww.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeciqot.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doijbpvo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbhhixm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikglpoch.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrmunmz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwadecj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qctgixri.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2poefpulo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbjzqxr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlltndi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzxqimk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2irfucvry.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgvqvfi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdmnirr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2obipbgeg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqozmac.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfqlsxc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ochqedxn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqarlaim.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wimiwlde.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foqzabxu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdjrweh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgoxxue.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dotbposg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tapzfvjq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kkztgaoz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpahczpo.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qywbsrkv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeuneri.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odffjnfg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzjomsg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2etyiexdy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2agpbfygi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkbopcu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fekqgtxe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oorkhpdp.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2naudtqhi.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2asgsuljs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uakbrnjv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxiairn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tflooidc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwotqwmn.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmzikmp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sirwqisd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2exhbhtpl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjnkrju.html


<!-- 参考信息 -->