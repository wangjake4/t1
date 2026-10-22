代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2feiqxksh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgywjfic.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2njtieeot.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aojghdqn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddegistd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2vludvbyu.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkozoru.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hihjrxmu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2osgalvlb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzvlbwm.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfegwrx.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnrzpqv.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hbetgbav.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqeevuf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxxsscg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqdmoba.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwqjfwj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdanuew.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bockkvkd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odxentob.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpwuvnl.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2aafdpcxk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhjnqbt.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjozqpr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvmgyox.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpckqpi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrgqzmz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfinppm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhjkvyv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jswwzpzh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kvykbrbt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeseljw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxjlorx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpvkafn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2izokcffr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhndnae.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxtnemo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2epxajesd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fisyzkmu.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbwrylv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2degxgisg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwlylkg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdhxiyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2riabprnw.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwlyijn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2odwqfxju.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pudgruha.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2wausgzst.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuubiwzp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmntaax.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfbndlv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrrmdfv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pojnemhl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxenvohn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qjslcjkc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slyzkhjd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrckjlc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcranyr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2frgdlupq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dylmaujc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2udetpzoh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcloelb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuaiorc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkldzhvn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxttedmr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueftosjt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhteoop.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlespry.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynomvqhp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqediedk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpwcrun.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aicdmwca.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaztyqz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ystllnon.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdrasij.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwqppbg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuesmwo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjesear.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuavjggt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2afxfjarx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhndoww.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bagfqvzo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoezdqx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmqtekb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytylmuek.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhjihbf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkdormd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbsmrql.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hndgxiab.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bagsfzks.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzvimbn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzepumub.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwlgfid.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bijotpwe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyqrecl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxydya.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2peienrlt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrostxr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvmidqw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjqjyub.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jighighc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2akftzksk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2edmlmkus.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpfgmpn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbusvzf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzufvny.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdxllxo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zgouidyd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcybqdlk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpduelvp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnoahzx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gashcfey.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2otehnzdz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcfpkqg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2txvxvfdy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsgdasa.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvmwrjd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuqpggm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyywzlc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2acpwwngb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2isvukdmb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkstakg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hebpvwwy.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewchnveh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eidotjbm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2piydogtm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzzlcec.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxofwhqc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfriqujo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hictcncv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjwjegc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeykrla.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwhlgec.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iphvodmb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exnjgezr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtdzqbi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiroxyt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dinxwkjx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhydjts.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhrumhz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzjttxk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rozozhey.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpeqfqu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmotiij.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjzpqvf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2smgblrpv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2itfgumuu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrmdqbx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiagqfw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gybexksg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgdsral.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jsenshbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrymjswi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvhntnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpscvra.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ohslhisu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdrekaw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aploierz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqadicab.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwoxixy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2maidmzqw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqghkvu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twxjclcz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmacnbt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeeoupi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkwwtn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uojgemtg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeoopfr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzudhls.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwemnxh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtjsuwl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iamtffgz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lloosyje.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlhzsuc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iftavpix.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oulhbqwf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdavjfs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnaxwsj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yobqtque.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgfmlco.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzizenjg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrfeehx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuengik.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxjtcmx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbeyrio.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aazokjqp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snltocrg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caqnffpf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2thxmlusv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfnnhfl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2twgiwwkq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2niaqygqe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkavwwl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrqzjjp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzixddoq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvswynsi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yphhmmwl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbnomrx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsgjzbb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wffyaaps.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2izoaiglx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgjsknb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxsldqm.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iowqncdc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzkxjcr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idoqlpdy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqvzmrh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfujbbtb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhagrdi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsuzjzm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhsdbsi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrovmvk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2emodwyzz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwakini.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulctsgho.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2itfbxogy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoprtnb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eujekcad.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rkshouce.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dloksqfy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urilqbgd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgkygbt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izhbllnt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyumqrvv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqwbtoa.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifusjytm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvhxrsi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vrytlijs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjjbtdh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgydpmq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nenzuhve.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxweroa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiihtunr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cojtwodt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgbmagk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkupzxn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lgejiaqs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuonyhm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rfszsfyp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwsxjao.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2prrsolvq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mrptjtih.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfpnivw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aswkxall.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2blwlkhnv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsiuaqq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2agbvajkv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhiyjdq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwubxpy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzggydtj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsenpnbd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2izausgje.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwrroaf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiaqwvz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qewqsltv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwqoijp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szydwkyl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzttjuv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aszrepjl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdezfqa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zemagdpv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rezgjjei.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvxfolt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bscnjcwx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjosjpv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2shhtnmyb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cubiiueb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqgpgku.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdfrdsz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjwsthr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtjhscn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeoybsk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhfacnc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2hxniejcy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2eumvudrr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzxlacg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjopcg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpslookh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsgyazt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2flpxqdie.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwozpzg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lrppwlju.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlbfstc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqumhybq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2oemyrxac.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqugmgpy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymviacrw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpeuiio.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2osduskti.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kohihght.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nzehcecy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ddipylth.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnniwdox.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvplesp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzptmtk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2daxlajsn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuuwzen.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dopgjqcx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxouyog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuuoqgi.html


<!-- 参考信息 -->