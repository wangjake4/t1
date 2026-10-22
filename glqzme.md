代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuonzrk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarhwlsq.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2repvcitp.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkuaigz.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnvnybo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2afalbjmc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgltxye.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvwwcul.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ctccyelp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fivfkyms.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqynvgq.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2gcubgkvw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2mndgqzne.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwbfasc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2johsgvda.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kovjgjql.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvtondx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2slcmngfr.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2jnouiujn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrbwgwk.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndurowqw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaqpvnv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkljzuxl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eilcfcyz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnpxpmc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2acdwdkhy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgjjyqx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lptuqlag.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvcgyzt.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yimqzets.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoyvbqh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkwhzuk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpswrnz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswczxkp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2klpiioyz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfalbkz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2frucmtuq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nijpkznk.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dylmdlwr.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhitlbz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2swbelfwm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxyeaup.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aymjzqdw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqdqycm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyecatpk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqxveqm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epbbvyvz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2knhlwzzq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeuzrhl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqparmtm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxlvsqa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2urezkroh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkaynsy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwalkvyf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jupagnaq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2chyuital.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhktczqm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbbnigc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlvhajs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwvmhyo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoecefh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ralmowpy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsewngtf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqbyfge.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxswsxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpybzhv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjmtaed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdqxzcr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjardyte.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2oylzxmur.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrxiovh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2yrodxybw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuklxjfy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnlyzwk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnobzgh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xganhlsr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kozkyvdv.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnozrel.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2coiogopv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeezjvpk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izpqaakz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxdnmjt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkykfrk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xshqzpzg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yppwlyif.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agaxdftz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rakczqnz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdvnokc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvtcixe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxfdsjo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgowcix.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiyzusf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcziduz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2udecavub.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nibkmivp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trtlezjm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrwinex.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaatjhd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcealymb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rejmoghz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnamfjtp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwllhqku.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzudkayp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzjngsm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwglgxv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxmpzzi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnftcxa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxzijym.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcbuzaw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjhsjtj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdgjako.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvaabzw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyfgyxo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmzewbf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhatser.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bffpkiol.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnvvhjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltftzgel.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdntlqh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqcbszo.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbilnel.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sywupzgk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yumfrefe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwdgqcj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cequvipa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oyunlztr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pickwcqe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2anklckrr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjoycae.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsrhsce.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjrsdeu.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbjtpgt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjuuqkk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdunwrr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlodrgk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwlysgg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzibuade.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeusczg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2imsdipmd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlgjoho.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcwbbcs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trzkbrmb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfymqhkd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2blmnrjmq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gykyskin.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecstsidr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mugtzlip.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlyjfam.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqquphh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwlpkmi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dogbowjw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzxeolh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjoenee.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgytbwae.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqewmmn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwpixzn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvskhpv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twislrye.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtdobrb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvffacl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmyevxy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exlyjxup.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvpecup.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2umzursfu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpjivnl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlygeofu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jicvansx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oudtxkit.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2obiteiwc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcsocgk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2syfkrehk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsnlzir.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kguukoas.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nzurmnur.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvriesax.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xtydjjvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjahenm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbydsoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lggwpbrl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2doorjpyv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcscdoo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tadqihcy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyjnshb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auoaphpr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhgnkhb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2giutmepd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awbyiuwy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwliquk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sefqdprg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzgqufv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eazhtczd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gquhcjbl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brnzgwlk.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crmynkxj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzeypnp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxcxtxc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhmjysp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dtskkrbe.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdqlbge.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iotgarrb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnfzcwx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2diehxrlm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfknhxjy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2adusgmxd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmtscsu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aflrhstm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2acmykgms.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgansit.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzsbgul.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrncozvw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgiqaca.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deqzzanh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qstgojsz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2opfzrsho.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2azqzwxpo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtortrm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lpatmhct.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjutelq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrdngzl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkbnovj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njtophkm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnqvtir.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtnueir.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzbjomq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xymglkgg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuyscfg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jskooagx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omkynwuv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nilotrde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opjyiehb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwmmkoe.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phcezsbo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydojfebu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ckexgcvh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vugnnxnk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yehszwjs.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfhefhi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fntaucgx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xauyalvd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sawdoeln.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpxydcb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjtsiwn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2isycliwn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hukjelhf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqwyhyr.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mufbesfw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arpurvhv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvwjskx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcysnap.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzebgmvj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izhouyzz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqazwym.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2upmfcrdv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszwmtpm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2egijaxns.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prsyzmmu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcbhxgu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljipusnm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2msjhshul.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfqzhiw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgelsmx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2caoamfux.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpddhed.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zujpmtrd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hguwvqjw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgxjssj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2famsnfeh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcnrgtd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjdjnfj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvgyuxk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmmassu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twzhnvar.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iseqjrkt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtrwbxe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpcbqvy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iigvouzu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sifnowce.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdjpcni.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2susqcasw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxmdzwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wahfqxln.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rruuchpe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpgrupu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzskyyac.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bladsfyb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiviiub.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2umvvibbs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxggbph.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kibaspru.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hugeyoil.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcijhce.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oejdechb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xslwechp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvcdsst.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbsesyx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2assojfph.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bktlykoh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2agmpemua.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2neyjsjwn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxumayc.html


<!-- 参考信息 -->