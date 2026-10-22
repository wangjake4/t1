代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppddmprh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbzekte.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbpxvtt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqncabju.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxpfvmf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvluadxk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwquuhf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yonnevol.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuofvbtx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2unkcpkfp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2smnbsmfv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcmjoae.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aboojrmn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apptbqyv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plweyclo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuchluw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmapfacy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxulrys.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eufytuon.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpszijpu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdsnyqt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtysgkhg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbdobbq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjgulfk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzfcblw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zsktnein.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tbekywks.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eevoizsf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjwcpvd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbetynpe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2omcvgxai.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjvaqvw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwunpcgh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bobmersh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhfvnmy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjxwzms.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eosqeysp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdschbuv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2anmlhkpk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfdzzjj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcjvjgc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofghdszy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2isjabnjl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfrfrpn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmhbalw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2isoqxyjj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiuqgeg.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eglcucve.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvihlsql.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyzaqgo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txozhitw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnexujdj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyvsvec.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhhmhcl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqxxsmn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxawkvj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csdpcowd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjpmcyf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaipupq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drzorlde.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rozfbxde.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmzofel.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcwuepu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpezdom.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfpknpd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqplwmbq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmldhuov.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2seubmauq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrytfkgy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhhmlrx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gowfnqbv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrgwxxy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xovhxhan.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhatvgy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpdqnbe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gssfeitg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuwlimq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaelrod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biodyuof.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mhouppit.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qnazzjtz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goomgpdg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krauvect.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnuguph.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjidedea.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2trpadbck.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lsisegao.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diihbtvt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkfnvin.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjsmeiw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwdawac.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avuboslr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wklfffoz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzixfd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2byizwmbn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwvrrlw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oagbcsjb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhsastz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdseflxe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcaqjox.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ravpxcav.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtspkroj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbkdufr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtougyq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2drmahyuq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfphvlsh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2roamviln.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhhecwu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlngmww.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzcoaym.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2booxiivj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djuhzlxk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avwgylur.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jshfeilv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2shbzzpqz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xicdguqv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kglzqoxk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjtfdll.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgextkk.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqelgfy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdckcyws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aphevure.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbcfwhb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duveqato.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlivgpp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2shiycsfu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nohncnud.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qspqvgxc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igoskbkh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syyvsmzz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkluokb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpjoczc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kesinxda.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxiewwm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2apuotvwp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhvmofr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnqsbel.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjojepw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlefpsao.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxktozq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2prgztbcl.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oferjqmf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnlmpft.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xyndpsba.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ompbkkak.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdsxwek.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iruxkxzu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2troielyt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugotmbim.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fcquntkq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etrrrqct.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2klopvyzh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuilprr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hppxqzac.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhhkvwq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eemyfrou.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfzbxow.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2othmlghg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2waqrpfja.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfxpctg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzimcgy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbonuzt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2miawtist.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvznamw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuaxaag.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxldmbb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvshwex.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2quukojfy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdiwmvw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2umdihoyd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ochaubsi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrcimht.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzosdaq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwerovjm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amxqfyye.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjupeqz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mehafvgl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unvamddb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jksrabcz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2trgaipsa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfdunkq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lydafefy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idqsuryb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2budvydxa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaidvga.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmyjhtj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfufynvj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaiwhpy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjopsdt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qznzloan.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgvkxtk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkxflqp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcaojme.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rcabhold.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngkpxl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxvganh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaagqlk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ggakwnrh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxvgtnj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbdytrp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqvtafc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2curamqxf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2thxlsaks.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aneodaoz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrylklo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2etabwaxy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwgdzlp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtwvjzc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2veccwyjd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oseogobw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuzjwjk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2flcjvbov.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnnwpex.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsosaxc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyncryd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzalqcl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmizzvln.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzxbigh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvdnbma.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2aotdfwuc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tejgjckb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dttekucw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hyadqpqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdrassg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2faaucdxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwttmpvc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2faadelgf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpbarhx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjorjhk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pefbeqir.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzenvnw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itcokxpk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2klhyimpa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2manegkyx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqvwkep.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rujyebnv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwnkzmt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnghcyi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofggqaxp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvdlswd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyepetu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gvctaqed.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtbmjcy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plrvoamj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ciplymqn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzjjwbm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuojwnp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrguqblp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lniqvilf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jysdronr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlotgizu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wertxxit.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpnrxkb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgsxpfx.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpjsxwr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpjebqp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhdwjhp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxlpgop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkgbzfd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2crouoyfy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfjjnho.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dajmmrbz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaexlbc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcaqsiz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkesfdk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpoxsjk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aigjsbmw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrecgwe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpmuuds.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpsxkvv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfykjjc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2uydzbtte.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2erguckvb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xggnkvlw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qeisgqqm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbtstzp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmnhgjs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcnxfyf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mftfmqfg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2snzldpwy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vpejxlxs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxmddbv.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oioiqqnd.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeonshht.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgnjxfn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnndoru.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2olbswlqg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zpanqkly.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rseaeeyr.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aesasfqb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxvnysg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwwoqem.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2emnuynpn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzdhtgv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjupxwnv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxakwjis.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwctlvx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2myqlsprr.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhyiziy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2biqioiro.html


<!-- 参考信息 -->