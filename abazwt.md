代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcmsyro.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfkxguj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nchxrunu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyagnkqy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhshohza.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twwomtgt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2drmdhkfz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqylvnfu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qebsihcq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdovmffe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwncncf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhkyrjf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2txfddhde.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bivxzueu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdahduvx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eezrjbqa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzlpdgm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcwuywi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wewuayka.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeskvexz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxgzbtk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcvbpzt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dluqaimf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnpcitd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ownovmlc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuxxymi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyuonfd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrrxgws.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyjjwsg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uplzfisp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaorkrk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrakduj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wxffnyst.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqalqxpa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvspmkm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scwcmthq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lorogamo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrgpaco.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2skfyhzmf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdcxqrr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyikqax.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmlayce.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juaudugt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flrbkgui.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpzatym.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sghtffun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmonlbuj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ersnxknz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmuoujw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlrlgyp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvrdkwm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgujlvvy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwacxdwy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjfxvvn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zghngpyp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaunjcy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zulfhcpz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2eigytatd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwadluxz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2temztkvd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvvtxc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjyvfyn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaupxiz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhqrprx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxytkou.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydchvoxp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbdxkyb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmgyzvf.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ivivydyi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqjqnjj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaxsctl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ekywicus.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrsvwyk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbyqzzj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnleydm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeosuux.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdjcobi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2edwybchd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjapxwe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2houvylci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjzjgbg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgiract.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtycmfwl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpzswkp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efznysjg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrawuum.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fphbdkan.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xipfysqz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzwkjyt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwunbbkf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbofqlvz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2geoadipj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wnseavzt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbvyglo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2noogompx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcwqive.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzkxdla.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zijkpgxk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnjgwaw.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwosnfm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbwacho.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpeyxxj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2euqzxkoe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wobvwxyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcdhcqe.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aykcmdja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbluccp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpknjnc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hibmfoaj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waezsply.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzutphlt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfngzrq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrfcwmc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnocqpzv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxkvwly.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtrleya.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxvxfbt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpmrovp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiasgqm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vghsrccr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqllswvp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgbqxyg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyscoidw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bavqifvv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orevvfoh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tfryyaal.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2imaflfli.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvxherj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqdwwas.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqescdsk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvtefws.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iauobtpe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjvufpf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2krabhgaz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfapery.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ruesefoi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmbreni.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lowiokku.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tynkhazm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jityuewy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxwtotj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2owzcewcc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxejgzue.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2twhjednh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2muquryck.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ridzowro.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnhiiti.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfgedsi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wycmgbhc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iczxtbto.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2clupatqm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmymhylx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjixlhy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmmhtkr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rznvzkdg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjddsfsb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvnyocm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maeyksdj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2foiccium.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrltkhck.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ophvffnn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnglyxk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoyeokk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2toavyyum.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phasedtj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2srtjgioj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wianyjtd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tevouthk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qukbkyyh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrxzpja.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnkeowp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jixylclx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azpmndsv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2regvysmq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fejrsbio.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lflfpnpa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpalpkz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtzospg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeszgouq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxdpuba.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeyesdo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuymkxvy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiisfly.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pczvvvzp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihoqyy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpthgcx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zwewtlwa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agujhwjj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrfwqro.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkrxrnx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjauipn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrhmosp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvercpm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2zzepfima.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xopvbuzu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uhchpflk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvrrusd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxjryzn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxmzvyv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwqhzsj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcukirlm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxgnofn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtyvmmj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgpvyoz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qapmontj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxsgyme.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmdpgmq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkfijbf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmkivfn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doeyniau.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnwerhf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjrqxaj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudjutja.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2umrqdcze.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bffnvtza.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyxdzrk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2djegkoyg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zvebkdnl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqdswkp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rniehmsl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zasurdej.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cghqcxly.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbkwqzf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2erfttued.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qsomxqdh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xiewnnip.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdnplkn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgooqzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnkggaz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgouxscq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eceqiine.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2avrqrpwc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2sijprbcv.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lwupqbfn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2amzqwnes.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcnctap.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnycyrq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgzmotu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mffjjzpl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ondjdsje.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjyxeab.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fujjtzra.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqagwjc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfpjclc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2sffbdcpx.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypujajmz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2smheonmc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rumeejyt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dezrhzex.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrkfmti.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzlwdts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rreajooo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnoawmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmwiyxk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqujyda.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrtzvra.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jszyazam.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmtknjl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdbbfif.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2goplgspf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2foydtmuw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwlmyue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lolyzbqa.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjlktzv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwmxqsp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqswiapy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigtclrx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqphvtc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmrzpsy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiuulxy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hcltqgce.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhalxpj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnmruhp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvmnokm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvhtrfi.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuqimcc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwzfpbe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cimgtcwg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixffcjf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cesfcbam.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcmrnql.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uihcvsxl.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkxrkic.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gstbkwio.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuiakmc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lruzbuvk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irzvqclv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnnmuxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2daifpyux.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2algnxmhp.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snzowbef.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fqllrcrz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkjywrd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiuvckq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgrnohi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzobmoot.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzbactt.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgszsbq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfnwnst.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2eaogcisq.html


<!-- 参考信息 -->