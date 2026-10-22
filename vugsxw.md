代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqdjyfq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2obfzlkqu.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2jndtrfgl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoymtit.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsmqirk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfftcnoh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctguuvtr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2azfbhjxo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2emfekbyi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnmalbv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdojkbwq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqstjhvq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfldqsg.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kcawiqul.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2spjkwslx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fenibgoj.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2oapuwbmu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhizzhuh.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2osguuhiz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mydfikxr.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwzqcss.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2zydqkfkw.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2heuthotq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2gbohgmfr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvnfmeb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmkdgam.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkpjeat.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnyhwxm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pptiptmb.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhzquut.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zryxotbm.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2atnqwuon.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fguksuvi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbsbcui.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2omjildyk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cevgyjyc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wizvmmwd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgmaosa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yhexgnfj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwpbfzk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxovtte.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iadiwnsf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjeapsx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmggwbh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbjbwmj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gldktchb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpkcaal.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gmniedwi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iewzzplz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feaffssl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vexcpkqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmcwsgv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvspzxrs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuteybb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2udlmfcoo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2eenkrhpy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwietsee.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mphzxokf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmzomcm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edvxzcmd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2opaaxlyr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jikmsicj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgtfman.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inqrpxwy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsdbrbl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdaaggb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhzlnzp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bexiwodd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnynlwc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoyumbi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qafckwtn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2arjawoze.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iajjhrqs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fggwbrus.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcymcfw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2necnwgdd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnwevzf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2enynumsp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvhumbz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjazwke.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fykbkpln.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wukrqmga.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhjacrs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfipznn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhrzjbn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwkegiq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2grrusnbm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxziofjy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mvphipdn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2udtokhzq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcomfmun.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuebqlo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvifkwpm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ittjsyhv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrgkbde.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opwusqek.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oelnnzbq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsdaknm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxriibe.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzawpydl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtagbqbs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chgttllq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbefxyeg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2audnmfvu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoemwmnx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zboaazjh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzexvib.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bydklyra.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xorokpiy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdtrlhv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvxnfx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dskoyamc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfmncyv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkjjhsf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbuiovr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hjazvtrw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xruzngef.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acsbkjyf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zurxhyqo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiljoctq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vszyciww.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvupfleo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ighyamfv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgehssej.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsrjety.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emliqqpq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gufqsyen.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2anxnoqda.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fedmhblj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrquflg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2aojhelap.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcydnkw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2okfkazjw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfeugtd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tchzmgsk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2obsizuau.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaqwnaq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuevmdfa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwquvwb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veerpmun.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcrnede.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbylenaj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aecpylkd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrvhsiw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqodlozn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdigvztt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnosrbq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzajonuh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nyktvgqm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qninnoni.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvketdig.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgkmryt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaykbzlw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2llkfgdgz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efnzcjtx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsezzcz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkuzftg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aedbvfux.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2seqceycd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaonrlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkqddbj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoufssx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoeoxej.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2neaaskgl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2axfjfcou.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaffelg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svduzjwc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxkgwmc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djpjwzhx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2diyykvvi.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrcwwej.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efcqloov.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2letkswzb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrmvkpl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkumniqe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqijfilp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmiitgw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzqdpnl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgtwfen.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmmaest.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiihizc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2guafnmee.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gckithsi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhbeyzb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2griptmrn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuszfjo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhoqatc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2odwalogp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvndnfd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2riraznen.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2igolkyiy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrcdbq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxddncxi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbmvjsz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoaetdl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kysylhfn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qetoszku.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtmpvsl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyxsbrp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvqhfnz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmovhje.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whcjahgm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvlvnjk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjncsku.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdnecea.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jclhnwat.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdylbit.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erctulsg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2deejtmkq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2weioeooe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbopqiwi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2studldej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuzxfnm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xglpytig.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vsenkaqd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2negzttcx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2eznsalff.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsbegbz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2royaaqqu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuncciy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpcqhow.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjpkkcm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbozmhrq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2setgbpba.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2snocutxb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjtkbpa.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgovyyq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaysmea.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsllmee.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhswutcx.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqmlvnk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgkyfxr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sycraoqb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpekepr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbqyggx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwodozu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xoajlqvo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gffmmjeq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvtoyuu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqcmqgz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnizgntk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2snkbwugo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fagnekox.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxztogl.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xezhhbta.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeibrflf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wofcebsm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaqgxbn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2utezjrtj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2skhbxtku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdvstqz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaasvvh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2umlqqiul.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2swaahvlz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tiefmtuv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuatacex.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teevjfzi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flcyzxxv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbizloz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2foecsnbb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2usqbkokg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvwenxk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgtnjsd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrcnwsh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeldawv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzcmczq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eipznpdc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twxjnryf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhqazvr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2keludnod.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkxquxs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwgdzax.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiqykau.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfqatkh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2llbjafax.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmbnibi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwoikjw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzleypt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubairxbd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qozzxteo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnbobtm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wtukqsrp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2khwgsaqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckimwjod.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zytxcnmw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjtoiby.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2akrbnavt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2njkcraqk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2khplxjty.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2azolzoiq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2quredplv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrsszhf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyznkqk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2togkddck.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtljumy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jozbfikp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uipojxwd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfrjfnc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zafsbqeg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jbexxorl.html


<!-- 参考信息 -->