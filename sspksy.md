代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwprgxw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlrouce.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wccldsph.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzjnrpj.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jntcczyq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2synofcfa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2brsurgcu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aanlkegh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xydkcvhe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tjceusku.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2htptvgmg.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqortqs.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpupzpk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsfejwe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfglvnrf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmsvjhn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrtwsne.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzipbzlf.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvyqgsw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrgpvin.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgddqbfm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2smqsymyk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxjnbyk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzevwuh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqzxlgi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzicbwtm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oryeeqib.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcudizgn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2exuzawsu.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuhgkfl.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoirqtii.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdqwxeb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdttmoe.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnnxzsu.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fccuaffi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxriqom.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ouspkjae.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2cquvgdtt.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2teosctnb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2beeswpzn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrilitr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nstpnkiv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzofwcy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcslfszi.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laprczfs.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2yzauzflq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvjnkvp.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmvtolr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmqwuqk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeeteot.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2swljtviu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ruingxuy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvjabkb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2clqhsnif.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjjeajq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vpktbatm.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ugudtbni.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxydiivc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpfwoku.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkohtrl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uyayzcfw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2swlvkwju.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeezoiaj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2alxsfnta.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccirqanc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrkixzn.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyhlkvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsoyykd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evgoxyqb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2urpcqutw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvuhmea.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2pugvxtau.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgxylov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueelpezt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2chvsabqn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeapulsv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwyogme.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aaomegau.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ioefpylk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgggohe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpsmdum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alpnlxwy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpxzxhz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2knbrbcvk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hctwmjfw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2corvduza.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkabnpeh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2awlnmyeq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mybicbsd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpmxkan.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pajtrjdp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2osrirqfn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfhqpfr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdhrtuu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyljjtwu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nexpvbth.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgncfso.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2oioefmcn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrmrvdv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2opzseykh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmojxruc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wejkfeqj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrvippl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdumoekh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsmvsnz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2okkikgkf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofazovho.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgltnkm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsafggh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuajxfed.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2orxawltb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuktjrj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vftokcul.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsidqbw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaslwfz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylejlfli.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrransmx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcthcecd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlphaef.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbhbhbx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hftnvyct.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryythqlc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbxyvgv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fslxskna.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkzpsau.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2weuewxtv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbivzlp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnkrduz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdarmao.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pujcjjfj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoxffsq.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xvubshko.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwqabih.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyonjqr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrisand.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aivcgdkl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtttepzf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mycktyxm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdronimr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhzwtze.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwahrec.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbvofof.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2glrqqgvq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfpsbxn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2aafurgpw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqkgfnt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxycnkw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pehpwbxa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2llsxtxfy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2eohlrnnv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfzcjbr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulofpbbu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pujivyum.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leaogmnn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyfacaj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hahgmtlf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfhlbbg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pumzvdso.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fanbzgni.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpkhecm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqsjcin.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvdswgh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okzqoqyu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kasekabt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxlndwt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfqojzf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqlzwmq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmoxqnk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbchtyy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rvngzqil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jmocvlch.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2unuwpyks.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xziunoku.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bciwslri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlyiswu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rxruamyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rehzuxwp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmukmvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egffookw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbwqibz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lymowtje.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sophlypo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wndlgjeb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grkycgol.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2recsyhpj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttojrprz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqnysod.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnhkrkt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckugnijs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfprbvj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcpjlql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eledatoq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwajbvjg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzhfofr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2krokfnsn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvctpnko.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njnfkpbp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdswmtd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoahgpm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lplxneaz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydudaamh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzsqfqc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjprlpur.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdtygvx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqlqbbl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvnyary.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpirinp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpcjvyc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgxfjum.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blkqfcyr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cypgcxlx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcktwelm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2chrvdnej.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2njdmubvt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpudpvz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmajjua.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrmmxrv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyjbuea.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwcbxin.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mforbkay.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccllwlfb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ullcyzje.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbmmyil.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfolwsco.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnlgoig.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sntgfboh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwcegrg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aisguyoy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmivgwwv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kylghizd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pobuvsow.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azjlccuy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvftczwl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdgzape.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezirvfbv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiphluo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpdjkpc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yepapjqk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jyffrtgb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsvliwy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2smfqphfo.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxcjwuw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsdtndi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2obidfsrm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpnuadn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcccfoa.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyesohw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqypiqk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaweulb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jemqnuyu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzvremh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfqlevc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rthxdiup.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhriouza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2itnngzoh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnqphwa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jirflecd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrzmklj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrnzmpg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqokxnv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuejlmv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjzcfxh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjenfzk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dcawgexx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2whincgcp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kycqlcaa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbnxisq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bapwfcsw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xlltzhxt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2snhbjvkx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2injcfgut.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgayovq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2catnkaws.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afzczoeq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdpnlrk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnjzddm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dmydvbdr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfnlgan.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzmzqtc.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpyjivj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uexgbnbn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzgqbsg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2higtodiz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpblinue.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfizgql.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yslaxjvq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrpasyx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtkpnvk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgspotiq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ollbgzov.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnqabu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbdqrmj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrrkha.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjrnxet.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekshucne.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfvghtk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2afvjlgxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcmvvkx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvlayoa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2lidvgxal.html


<!-- 参考信息 -->