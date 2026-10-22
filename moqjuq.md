代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nspamsks.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjgwcxq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnabpaum.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfzlnyg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jquzlbvp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdqjrbz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiqzuot.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtxdhux.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwirwouy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlauapgo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgxholn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxklcirc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcjyzgz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bejdloni.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aghvjskw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcjmghc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fotxnvvj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqqujkn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuvvuqp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsgwxfp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkexdscm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpptpodt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaoarxq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2muuoxnww.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaywsgav.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2idmpnqum.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeakupjo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlxdewq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmevsrf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gghnkzwn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybegtjhj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxtcwvz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yaafedmz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhataai.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibixuyqf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cixwllow.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxmtzlc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwpcbvn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeawloki.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2otrefqhm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuyvgwc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2garbpcvu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqvtwez.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jffysfgv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znhtnzma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ludqtntp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atnhrkkc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxqmbgx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2blcyomao.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2koxlhdhh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cexhrxak.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frovpbeq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2necwnloq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmewjckz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcbznic.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmjnjge.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaeunby.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2aondovdf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdzsasc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgejcva.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqmkupa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcxetyb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hydghdnz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2feclctub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxenvphp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmuztzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlsvgkc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2adumzhkg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rgppjtzz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfhdpva.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgpftav.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myjfjave.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsjbzhe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgcgwxq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hibkfehc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtauvtmm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phwhokhs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnymseh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcwfgdo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtibixn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euzjgimc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2furfsovu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2spnzdoek.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hohqsvjk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlyyhpk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmvpzwm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2onedmrxt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbxnkrp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ioakbewo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzcmkmt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqozuryz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuhrket.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2whgxvaye.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2znptxibh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hwioydtr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2newvoafv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmctdqz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niiqrsck.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddydifyx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fftmmmvp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2glfbtolp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcasnjz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdgnntv.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2agvrstyb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fvthwoaq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsipumyp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uabmnmsm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxdhehy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjekvcez.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2whoaqywj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zeimqjuk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sttjurry.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoidmxh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtddgopa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtioafs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmarmusa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byuigrnc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzysfkj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pfatbdtx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfciuyk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rycryehl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwxzvuv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mknnnslx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zopzkvkp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmpegea.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kntttsgs.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrszchn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yaigaydq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxommqq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwcvdij.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsjhwnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pfopbgwq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2setaseqp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhaakw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wetqpstn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuusggf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2arjwgvcp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tspeklet.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlerqij.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfeflio.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zefmrhrz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omvjegak.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mqopjygt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxltqkp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdwpztc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqtvuwb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeoicvk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iymhjcig.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2riksbrmh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcievpk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ownpaizm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvkrskr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iknzmezq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpylobh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwvpvkl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrpjlrk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ooadlgup.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hffgntri.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgvvdpo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmyvcpn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiqhcxb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvnhbjs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrunkak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxibefl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xkemmnnn.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgahdlfj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xscwdqgl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zkockeln.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcceqjho.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erdwxnuo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opircrpc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkpubvh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jneozyoa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhinfrgc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbajufhc.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wanrbzeg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mavgbnnf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeuppaq.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rbplalnx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2letnivcu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vertowox.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gemrcobm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhixeif.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2smadplij.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxwjivi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jirvnekn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2obvrslcg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwqtxww.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kobprpio.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqfjtge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuwwgpe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nstlsxal.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbevcaav.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnbzexj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iufcxuvt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oajwfuyp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2sgadfnyf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nseavshm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuumlnbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2huwlugzy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2govpqdxn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2etrvuntg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zdirymxb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2hllevmed.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxgpuae.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoghcat.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnjjumy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2oinkhlap.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpdcuaw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtuobgu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ndllwgcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqumkboq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfjmjhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drznliwe.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2cmknbrji.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgizpuv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqwucqt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjnvodg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsoznwv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzhksub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hliwpvaq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ibozytgj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eheivqcq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbntjpq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2angcffmu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuxkooa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsteqkpg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrtpuht.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2knksfxzd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjzjpbq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqaccgd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaweezsc.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyrssmm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrerpsk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2atbtixlj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gngbappa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwedchz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhofnzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qafomeni.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2opwirraf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvrened.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxqdfaz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dsssjkdi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzltmai.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tasndicb.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtjnqoi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tkitgmpp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhwkoet.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ooemcrbw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsnqzqb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaczluy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2pocdlqvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cirzofkc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlawlnyb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btmvdrxo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xswbmmao.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2izgjxyxm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2hfilbnex.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thtbtjgp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjdukpi.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoebgve.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2czjwrnry.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2izhbduhu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvffatx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tygqkkpo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idsbnxku.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzoefhk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uimjqjzj.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhhsyjq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbzomqc.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjrvgca.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2csfuujdc.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khxomeax.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2suvnbcww.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rshciemd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jebhfykw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrmvozc.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrfbnjm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzjgiis.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqttlbp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyvushl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2giudnjxl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcaqijl.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxbfyvu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2nqncqjzb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2zypswmhj.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yqehurix.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuvusyt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxyvknc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsneqoy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrojacm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weeoscjl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqjurad.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2qehehwlj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pmedlzjs.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfcrkht.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfekott.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgcxuk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoxxydn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2tmskhwmw.html


<!-- 参考信息 -->