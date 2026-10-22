代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bbubwagb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gggqnyjb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsqehfk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abhdbxyb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsikxyze.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpjifya.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqfqggu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snwcmjhp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyyhbzm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsgubhx.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyybtup.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2frodqjhv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2advwdcpo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrymexv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xckgrcvv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpbbhcb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irthhlrq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkfihot.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtdnthe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwuureq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgizgbiz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqeiksg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aegkecye.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2srgkgleq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhfyyoo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwxsqlx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcugwnzd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjfchjr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mduguswa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdpkgg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eepjvqgk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2chthagaj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaakeht.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsdftii.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhujong.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yergprlm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2azvmludd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaczbkge.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nagfvwki.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtfbvnn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfrwmgl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwaflgs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jliyetmi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdryqki.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rakkzpvl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jzharsyw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqjaqxt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abdsznmd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obobytxb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grrztodl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpbubav.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bukrwsey.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwsdeha.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wygrezgz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjdpovl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeafsekl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrspdxw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcotxuau.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpkzjwl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wroorkgn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgpcegi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xndiirde.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2temaeekl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rocowjjw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uagwfgdc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyotjwy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ammyspcm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eifynsvy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjpvywe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pdniwwao.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcznvwu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nazlhpjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fftrqcdh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwlxkht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ommrdhra.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wyejcbot.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvzmtjr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ammbdytc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwstiwv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcauihlq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuzeuob.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2vptwerst.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ornptvpe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuijzcrp.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpweyxap.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2invyrtwc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rloqyila.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koouptqh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcmapdb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abdxkeht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeejhsb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2agdoodji.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlnrkcq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2liwqicym.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2myeqhtil.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqtdfca.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qblvosqy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xefkulcp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtzdclj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzlybpl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmntiyys.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nviavxgr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zkksixwr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqedeqk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lctepntc.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtsezwq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtdruxc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ielquifm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpiekva.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuhmlxt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2irnzqrdn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kcccqbpe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mckxqjqw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbccvgd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vixruruc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msngoeqm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuqtaxa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eovocsso.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llrczlem.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npeepmhc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2piazrxmn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrprram.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eujxdizk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2corpdpcg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkthnxcc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glkqecem.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2slazhkqi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tywopuyd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2wupzekxn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2igrzmhnd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfuyual.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2saeslovt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqogeatg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgevpce.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqhbjbp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgvyvqo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2anhsfizm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pczdyrxl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2igyynzxc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cghjimsu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfhngve.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bctdckgy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjebshhm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjimxro.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2icvotdol.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puhxdwxk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjknqqn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdblcum.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvggmtk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpmrcol.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhcbjrs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjvnayv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuqgais.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjxjjlm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2keccqejb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atcedgol.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfmwoki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fznrirnr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmcxbol.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpzfsdv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bwisuwsj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsnlvkw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmhluud.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcuduqw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoviahk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bsstlcma.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qizxkfqo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnmhylw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgqpxwg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnazmmtu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqpjrun.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdxesmq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2edsmoehx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrbepos.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2njewtxay.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdzkfcc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkjmbli.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frnwvuoq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sebwyafe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqrsqtg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bentrory.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmdfhqt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2znpouroi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xoatfxif.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekioszba.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zloanqli.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nanjinhs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2skobqhxq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgpdvzi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvsdbrm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ommejjka.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2prtvacxz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjytmlp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2uziobhpz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sxojmrth.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvradbtw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2heniyicv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pggmzmdt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnkekin.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdmxilf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaslkxec.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjlusbg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2slrnlwnc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmbsemg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kbohlwkp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyahlijc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjegwndg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgdmesh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rncyzkdp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2viqxbuhw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmuqxyo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdlifln.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2truyvoii.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkumvfw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2avijktxc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzyioww.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kfveaykj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ouauqpno.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhgiiac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfttsnu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tgitemja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdzjugz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2noqlnbnl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuayuyo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgwpedr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqdkzyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbxdkdm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlkcvrr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iswpwnyp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gudfodkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsncbjfo.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfbwuna.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fukfmxgp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfpcxfc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcbeyee.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uocudfsw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xneoudhz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2afcybirj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dayacdbl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otdjvvem.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfxyhpk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2gckcubyk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnasfsk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2usysfpid.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugejvcbt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mghlylwx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2boxobufu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjcuraj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iduyindw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsnpgra.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2syzgvtfk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omftlurk.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaclmcn.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuujxtsb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvzooma.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxnmztc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rafewfym.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnkzmal.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dlofspvf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzplgze.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbhdcdm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oumeglgn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfniukfi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlktdbxc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kajgjgvo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hbplsykq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bohyjemh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnpwbqf.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnippqj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyirqskw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuijabu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iazzdvqn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcylmoeo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnghcmi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdgzewh.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfloifr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuvujyb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqadfrm.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbicgflo.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dopwoyga.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfpnogn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqvjrzf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2silnpqaq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dzirsrwa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaduslp.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmbwvh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrpvttn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2torvlinn.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2kfssndob.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2cowoxmov.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmwbovx.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlfbgds.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlkzgwn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2kiikwwld.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2azuekzjf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqbghho.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovykhlbq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwxmlpz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iokhkhcp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qljmnvor.html


<!-- 参考信息 -->