代发 wailian999

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nobgvqlq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxegiur.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuwksqm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sapcaeyw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2efmgxudb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcihglvo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoxfoax.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfippvuv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfaffzt.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkmdtdu.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvdlieh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oflbyhyg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yntosuup.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrawmvdn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdccywv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlesnur.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdevlua.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jpthnjqb.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmkfqwp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2baybjgdl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2turbihti.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oczwgnzb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkukpgy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfkiyio.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwprzwtf.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zivtftpo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuaviop.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2alkotabo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjvozj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2huqwdygp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2txmqcoqv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tokogvgs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2znxhvcdt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cktwloeg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rddwhqvi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrrrmyb.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bnarabaq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxevflrp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlvkwdi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtvkawf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vyokpqkl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2caamidbs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2swjuuqio.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhovckc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dagueied.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kejfytdu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eetesgwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olgqocoz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrajzfd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2aakeayqt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhjvwxr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbymeic.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjznesw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fymoelcr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fscixtzn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoesqxio.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfctvjko.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqxcxor.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkfzjou.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmcoyxg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvxzrip.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwyemsk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2djluolqm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhryucs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmdbotw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkyjwmu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrqgfrn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqosalzp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2txcovfwj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoxlzfq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2swxpyjfn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrixetcs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrxeota.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqmdlnp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2csrkgxum.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cttwxjpf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kigmqlvm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaektlo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vghluvuo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlqvtga.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxcutlg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpuwuvo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoydofzu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2thbrajbx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoqaeia.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvdxosu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpolcmei.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vailyomc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqjhhwi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yycvictz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2syxzyxyo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzexdhxy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cldqpkok.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thzejgsz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cynbywvo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqniwmm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmnjihd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeviuyj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kctwuvbc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhynmxjt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoqooxq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxyltsk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiffmzj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuqexxn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2stpainyi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkisnin.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2owkpuhbj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgujpzz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2glfmfqww.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgohatsb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwnmrpm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xulkgucc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgbpkru.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfepwaqf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2izybnkwd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2knbkdgeo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyaudxr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2txcniwcs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpejgzzh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2swoiiyho.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdncgyw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbxaljv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2runssvki.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeegwwp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxwkvru.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2esbuuyer.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncekmmmb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpyzpyt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2atypsxce.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxwiyos.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhalnjgb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgphlir.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qafygxcx.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qabieann.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfkmmar.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjvmesw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrcplgk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzdpckq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2celanxmj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmnjpnu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2awnvazrh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixposcby.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuftzca.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvroxtub.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2owghbjtk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2smffqkjy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfwluvp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbtpzrc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmuazre.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjrlfdz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgxzlsq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gdggskrl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrzfhgu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrcbbqm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhzmxus.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrdgiwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsonovue.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvmfucm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2daatnela.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2vsglaamc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tgienzdu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiskbvod.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgkripe.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcwgupe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgycottm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2njkmpqpj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2amakllab.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uilpnqbk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdlvged.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzvkieo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awlpaauv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudwyfee.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnaiems.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkewkks.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbfizgr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpbgzng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqsorbp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjxpezp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnmnnoq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uslepzhk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yahogbyj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nucmngyv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gotwysmg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbnpiks.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbaomhv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbrefbo.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmceqqoc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eabmobuz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnedekqn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtxikwy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qitzagdk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goppemzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2njwyvfly.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkcgrrq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgttgsqz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaicnfo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgibmpf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdgopqm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmohpwep.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puugmyva.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpviujv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbxfhjq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mddefzph.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dixjpshh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvavknh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgasnau.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujoznml.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwrohqo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyzqvhb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfpyaxp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2okslyuim.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msjztmfn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsylqkxl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ssknlpwp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaxjplk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlypbga.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2regzznji.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qexpnfym.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxiwxss.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hegnxiqe.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdgsjan.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvokyjn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qilubatl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2iivpkptk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2webeewip.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kixtkiec.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjyahtz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvflscci.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfjhqdh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xytdiigg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2invgwles.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiicaxm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwjxrbt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btbogadf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iunuinsh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdkddzo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxudkue.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiscymz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlszpufs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrhcumx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bszbmsri.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwofwxx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgsmauo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2drirdwno.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2meehavaq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lbduasvv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjosxex.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwkytqa.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoyioxj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pijhpikg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuqqejn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvilixrd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcasguq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rktqjukc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiitjcnl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlwwyng.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ruavckic.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjpdfuz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwekkdf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvpmwvm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzsrjni.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdeomzs.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkctkiwx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krowlwgw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbmakpf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwachrf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrdxrho.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xavjdniu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvobvkxq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgxeieh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbxctmb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iezasuji.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2egezbnjd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdepihc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbygcvdb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmefdxf.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnmqybg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfceskh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pltgzazd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgypklqs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfvcndf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxdmtag.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyhubfh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2caxkkirk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hztybbqe.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsvxzxh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cirysfpu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqymzpsf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiozjcv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eemcrqmm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxbtigt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtgrwqx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fmibripc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nepnczhd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bpngoysd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrjbkwp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2llopszrs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2thaypktj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrrbsct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2atoqffod.html


<!-- 参考信息 -->