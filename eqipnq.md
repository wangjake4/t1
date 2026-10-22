代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnhneho.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2avwqnspd.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvuddpk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnycdws.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrvshad.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlnisxq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2frqatcbf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkixjjgp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwlbxrz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuzyacy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufirayyf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaoebqz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbqriwz.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2spptbnyi.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwwoopn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2npdyazak.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rthvxmwf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yitrtsqv.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pifqenfy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxgervs.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hphnuxzb.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2fivfgypj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2skrunlnq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2fgizzreb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzvjrdz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkftzsg.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqzsvpa.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clxwagtk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erhnnrbr.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2woopsclt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utzqucue.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkvodsj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2iokzrpxh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpkoncq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fddmwqgv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2twlxvkrs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qyezfdlo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cxabcscm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqtcofk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmnawnd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2onxnlzyn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdykkqa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uukrdnyb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaopcgr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2difgbzyo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsuytlx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrsnnfr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzmrxvh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaannly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csymkazm.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqdopgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkclybc.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnewuqvv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrrjxci.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzdtenn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2maveoyxt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmvkzon.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bborkhow.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2soiuutti.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whwuyjcb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2domyfoqx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfkgpzj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqrdyeq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxsuvcm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdwyspq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmsshmv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsjwvsc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgabpcgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayytvjzz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klbryvta.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kokxquqm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2czsyebjk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfyqafd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmomrrgd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rttgugjk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcggdpbc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjosxbum.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwzwatz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2exwpbtlr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcuejea.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbwuqam.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvccwari.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrwwnvs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdobdpjw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxpcmra.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztusjfnp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhoonei.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaapvog.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmksqbt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqquyrs.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yiylxuri.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2waehwutz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cttacwei.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbetjvoq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnakmgbw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnmoilm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcklfwet.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnambpt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdtlyzq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsyzxtd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usfpjqkk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoysptl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2geuqicdq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tennduhq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgpxkhu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaylnxv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxsdxvy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tafhwalb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkksrxz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqaxklo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tehoejxi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2umgmcrqb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zamdowrd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnooidn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2spydsstb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qoofccwg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaduavqf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kerpzklo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiskeyor.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eypkeamc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoikymc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoxexnk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2famzpnyb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhskfoh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2eilakkpb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aegangnv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgzlkhc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrjhnat.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsdhddw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxmarpw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2omjkoejr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlupxume.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hskgumgp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pptuywua.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzettpu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzryocp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tabrwcyy.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2koufpijx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeorceo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2totwnybz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bexbdaje.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bomykbow.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odausogs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiidfwk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2euwsdnai.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpdzifs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqcqurv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnpjehc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfiiuuk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqucmzqt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmctwhm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rvahggdn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtggqpd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2thezdaco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2akydbjyw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zgniemcg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmsbcwx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2imauhftv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qguwebpq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pwltjfmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmskjhgp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtxekym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkmwquy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nfufeozm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2umfsohms.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krskfugd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyowsqz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyzomvq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvrfrbm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtmeqqn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdkxuve.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqptyzg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeqgvxb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbakikn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xretvfny.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqdncsc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwvqkut.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agxbcvcq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdxzmlq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zonlugjc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlaxryh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxsokba.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yztoyuyx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtkppqo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxbkaer.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfufranx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrejudoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkaeeph.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzinsrtj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqkvxel.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2soslhwke.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2syxmsjmu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njthxlxp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lotdazkk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aegrwouq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcatrix.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmztwln.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2racbfhpp.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnrkdga.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qibshffl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qorpcghs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brgsavgj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zywinnwf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjutcvll.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xobcnawh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mloqnxma.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atxetqbf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpbissz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dreyhsot.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2macjkqyx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxutqtyf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyqfimh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxwzjpn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqicwcdc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjrojcq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjhynmo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdtpsbx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtyyxhe.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2liejlasz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uonoqdkd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2asesjakt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2whoprule.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxasdgh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hypncmbj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mquzjxhc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrknbih.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgrmxpx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yslhpqvn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yduaqhuz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxreeiu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2foixdtoz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsbuyis.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xqopzppj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzviugkh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjulhbnt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yitfeprk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2glvxbkur.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiopigjy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlkgllo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaebjcg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxvvdxz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhbbhni.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsfgbvj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oazxbxst.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2aaikqzui.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2spsaneok.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2receitlp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcsipqf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqaikqo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2elyniwji.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaxpqhd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2csbowimt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaebqqn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaeumkx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pbolpnxu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyjahnv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxjpoxe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpscpgu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwtmttt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmndsjs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoyuzyr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqpxybi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwobpak.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvcyaf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uackmefy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gycicydt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abopwpbd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgxsxpg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyyuhlc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2opgjkzpa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hznaqknw.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xorqltjr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hergzbux.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzmtdru.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqtdovs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kfexwzsp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiaytrx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhoyrze.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrdbban.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvkwpbo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfduxou.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjjzsmg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtkajqo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxysbyfl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrsbyxv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgnhspu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzzojyd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdmgdap.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2elmwfzed.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyxiozp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2krexxrse.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puovzzra.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvtepug.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfcbwpq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2aopdfler.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2punmlcst.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwwuumn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cibijvop.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhekukm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gciypdyl.html


<!-- 参考信息 -->