代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvvmtyq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvwjogs.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vxieuqbb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2overbuld.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbqdtbj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agbzxvva.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trkbyvns.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwathw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmahotan.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2mouhgind.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvqaaoz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2oagbbarw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmsgnfx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrnccby.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwrulqs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2spjcdhxa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cugjibyl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnjmpoy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sazcwnxz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hagurmox.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2spslbwfp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srynycwo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qclxpzhe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjdhpih.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuztcbv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbndhvny.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjqkuse.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqghtda.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqmtcci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnqdmmw.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxfcahr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqljdeuo.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snynqqoh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2karparis.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdcqtpv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiqkwne.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtqiiah.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2plkvqnhj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmjwdzn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnhqsbw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjcshud.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsdnwgp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzzndtr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqffrkmg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uveikytx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuveogz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2auubwjdp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2usukispr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2rynrgnil.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2toygfwdf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgzdzun.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcmlpcw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2whqbpuev.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rukmlgcz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdbirdh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwjlgzs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiegagd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgxcghz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lihscfmg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyfupgf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cttdwdmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvrnxkp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qojrertv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsbrkii.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2gduojerw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzxsbvn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2voejcilt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekojjsvx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wzthdsis.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2aecnmnjy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2divefwmk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbmbvpz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdxuhxl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lezacpwz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzjchia.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csifxbxf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aelfmwik.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjlpvff.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2otltajkv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2btenrkin.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtavtmxg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abzmryde.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aydwdhkg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lshoitzs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkbbghn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqnfdcd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxworno.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiftymzs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2spdsprra.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jvevzvlu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlpfzek.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzlirwq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zicmejfg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wswyiwzt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxhvtnf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpllhyj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxcelcw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbyybyd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsbgisd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2clevsbez.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvfgdxe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqotpafx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgmzvvh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzbwdvq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fwssvcpi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwzzdqj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhumbxm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rqasyitk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pqloqshl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iucbhqwm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfguwsg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmvwlum.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgfofiw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zmumwyfl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzwcmpk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lslxfssl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwsqmtb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znxhgsgl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2atyspxxv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uavuzhkc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aflkqnmq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqyhmrb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhxocyv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqqegud.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2izfuljer.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reqdmgrj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjdbxif.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdriojwv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdulkbw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srbyjaiz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwsqirb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2chmogguz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmevlfi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dngmnpqx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yperzefp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dqceadds.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kuibfmfj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2edvlarpj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2omqqzuby.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2emscbthn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdgnerx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqtpnwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwlglam.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2emciiyyp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gsexobqs.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxluylf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hocfcfez.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkunwmuy.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbvxekr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ietxxowt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwudmris.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fizpfeoe.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ninwiwal.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2daxojond.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jffspdgi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmtxysz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxtfdnb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laiaugbo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcukmal.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2btriwsdi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xygcnyvv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2thehlwzn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rafacowp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyflafx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aoctdlgr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqkmuil.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2awpcyuny.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2twglhrvs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2drdjzzhn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlnavsx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrfycsx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vesxmvvn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdspxnfe.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcgpxfx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxyxftp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsetdrfl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxnwzuj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfmshfe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmzcdrw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhegeqf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2onxvgdba.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzecusp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reyjeigh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnoagth.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjgqwgc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2htpfgtxy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2teffsaui.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsugckv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfntpva.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2aphfemlp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrmhvuj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwmwrxn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcvydkw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlxgqc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yirziheu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfbganz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jyikeykb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aucuxtzd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2afudhnko.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmuedef.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwaibxx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ioroilqs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wmydgxej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mffmqdkt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjxjzfw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fchkfqvs.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pffrgedk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuwzbwc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgufwlj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyauzko.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbehiojw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrkkbqn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iahpyerq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkiwozl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwtgcwe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xiydiuwh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zlknhqbk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhxpjun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcdlgmr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuvxbis.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvefpzvh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaksccov.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkvmpuh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nusmysob.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfdnfhm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmatono.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wfilgqaa.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2okfzkpyw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhrznhg.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvvahrd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bbroifrr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxoyotv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxypkyv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tciwioin.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2aizmwqxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsusdiq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gftdiekg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwttkctw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lirlbbpz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2frhleufg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbvcnfh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrbtqny.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2abghsvco.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhpclcz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fstyoyji.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafwgdfg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keohhfnl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhemait.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcvmsqw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuqsscy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjqdjpu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lsitceem.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqtsmvo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pulryhgd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kbizrfqk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxgvffs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwsoyix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqlwbaj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2auydvkuk.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqtuhgz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnihfnb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zsabohri.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tikjular.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzegzwkj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjzlxsh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trmzkqjq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfeggys.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqfrzrv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgigjbiw.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjqoznu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hncurftn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sugncvoz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mliotzlr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oblvywpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2masuowfy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueagvjeu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2nsglugxe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdsfllo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wukbgbpi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hzancxcj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrtqfaf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvqwpkl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxyjamc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpbpksy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ursdcias.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrfhlrj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zijckcjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpusqmt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrttfyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brmgqybp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfeppgt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbfdcae.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxwegj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqrwjop.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnisoawn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjnqpvw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaiowww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjspjhw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkfeoie.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwsnhez.html


<!-- 参考信息 -->