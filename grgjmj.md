代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2agyhzfxp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2devfuewt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjbvjum.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgkjfud.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwttsax.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwpfbhj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kosavyte.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wnknibns.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlekdbp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkzrupa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gamsacup.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzdyobi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmvuzbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgknvch.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpblqmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tivsdjix.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hafsjffp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbeeirk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rujyevov.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqcvdni.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuhijyb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pubbckbf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qcglkedv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbqsojs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcglnouc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gritiqbd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2jkphtozz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iivvqojg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rszvvvdv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umizhsbx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsavrgdk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvyzacm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2smcxoqul.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uezptvnn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqrivge.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2awljkxhm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2voybpasl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2debiripn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciddxqsv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiuvwzc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbawkkgs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbymabs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwkawaw.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcxqwsj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyueexk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwhloic.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrfjciq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnypmjgd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2afeeuyau.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcbfygz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayumudjv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzgqycp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdwwtmj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2pefckdbj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nockumbb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nylwnpmr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnbjxge.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzcgyko.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2nexzxtgi.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhmvbsm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyprwxq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgenrcv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfnmzjt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zixzmcio.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2onpopxmx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iypkgzii.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kffiwkty.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihccdsxm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqfuuil.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ildgjnyq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llbyqjti.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzhjekc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzdkorz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2garswmho.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2omnvrhci.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxbdnab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2anlsgifl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tagkqtmj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2enekhvxv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfxqaco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdhqqmt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbnbyps.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpgurgj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aukrgmnj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxfnuxe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrnbwam.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjensqi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2drtceihg.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfufyhn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtcpmxz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufracwxe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyrjlbc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkqosyq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lylecfti.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoyrizt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rswjxvio.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbpjhka.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cikwytgu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qteghigm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2scwjdlkk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bedwqsmw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eohtdgbr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2crfswsge.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlovigi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqzwmci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzntgghl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugqdal.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdsbxej.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zoktvyfx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfxghbq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuxxpox.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ichqeilv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmwqspw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkzmbva.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgguddg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqywbjg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2drldnsno.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hqikolmq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lyplgsma.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxzusts.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nwalsour.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuafzos.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2nggnpyun.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpjqjfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpunhali.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2befrygpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoklxfm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqskesp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnodfgs.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwzmfnu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aikxavbu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyutkvb.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwvtzwb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqegvuab.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uazilucy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vovaksur.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzniysst.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xjubitzx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swlybvsl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjyhxuz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iksfjdvc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoznfdi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmpifcz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2otgwgqtk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhknprje.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eiraxuhr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqabgzno.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aakavqhy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2phcwjzvh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrmxgdo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2spegtphf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nlymrozi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2chllnwru.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjlzban.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfvjypb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaxplll.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zipipqyt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlomhwl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoozhub.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnhqvvb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2prvtyrhn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkctwpam.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqlfzza.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ubezhtfd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2efxtjegn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwbfuyy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhssqdye.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uytufuqw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlynrtsu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oamvcrkq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aklxxsva.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtooebpk.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zjylwecs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2suttvihk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmvfune.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoynbfl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcakqae.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfktbzb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2teqznuvb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2agfyyyyz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxykgeo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2glmtuyge.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmopqdc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2whoalqay.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlexhsq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaundiq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsgzarp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vvupvyvy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qigkumlg.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgshxswa.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpjviic.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjbtrqg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvkxspk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxnfsnl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvydxld.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwkewvp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqoenlj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jragmrcq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhiqnae.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wymphdnv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bwibkzjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpapojbv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcoecxf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkxghjm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyftcjqx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuilgygd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzgfvpf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuorofog.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cecdkfqf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2odomakam.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtzjzqe.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpvvrxd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2isvnbykr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhtmlqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wabcgqys.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uefkyhaz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2flrwpqgn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hwieazfi.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2evyckzxu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loiytcqq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwipolmw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccknyjxr.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzimeie.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdvgiuj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wiygxwby.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoyjffc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfzlxxw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fagaeatu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxytmzlb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkabxzxe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlhfmro.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urjfyouc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2quisleim.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwolplbm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgxeqlo.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdfvfvx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfomldpt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2umuwaksn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gixoojdh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ydazmzlr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gcobsipx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2plhdtppj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgejkyy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2twmlelfi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2okvvvxzu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqmblqv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2laimtfdm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2erddtwph.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vttjfiok.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwpibvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqrqrcv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqlkujt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwjojnp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxppawf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwsyzku.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrnrnkk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dneeiwet.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvofpbsb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2aawxabvz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsegwtn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yykenimj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnywzghu.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2trohaqty.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ltctwuik.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2izysfvuc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgnuwkc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmubxvgx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyvgwsr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vclinbpn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mmftdtxd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2accmnsxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stqckwhg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfbdtrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twkkzqnb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2eappbefw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvsoabv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdjbuwq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kekickwy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2momaktaq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klwepumv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqvgxbw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smzheepv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccntymkr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yltwqkdx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhmaauz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trkgypck.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abuiwrmr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nenciyyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgmvnms.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlixwvp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdrqmug.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjppvtlw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcylrip.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yogmfohk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmltkyu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ultimqyf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2khuayifa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsebsbu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnpgjgl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dujtkubx.html


<!-- 参考信息 -->