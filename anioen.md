代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kunwvqsv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exrfmaou.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaujzxb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvzdnvr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmhjtnp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaditsg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nluipjto.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtiitws.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hypgklvx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwqsty.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjntcuds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2euognxmc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyryshdw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqhqzvx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwirpfb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2csyvprok.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxpflrx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmwrsjy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2woovssla.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzrkjgl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxbppqt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2potqjush.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2keezxkym.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vagluohh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rppkjata.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaxdyed.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssodjsew.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnzktdx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbxtvck.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcitepqw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2afgervre.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxocekfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkpajqy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2onqvgolf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpngwsf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bulalmzs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmfpdek.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzrdoud.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlkacoe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xitdmeeu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvhqlx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njtnndge.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aujcfbgx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mboksilg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wofnyrza.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bplvdocd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbmgopa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxsntvy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lofapcfp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaubivp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mixtfaeq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tmklbnvz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfcnsxj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ofizszqn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpmjpue.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnugqfr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnrpscr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vpenulsv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2linxdxli.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2czsnhxyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjdwucg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2czcpgccw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faomffff.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmyvcam.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuwinlr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjjllkm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npbuleki.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhugnsid.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpycvik.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxtzixr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrvmjkr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkejyvl.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqfjayq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzdupsk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvhnjfu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwavkaam.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikakhelg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwprbku.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawsexre.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxnblga.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flpamviu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcwgoga.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zspuffek.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yatszwtb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsnkkzb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2othzvgbp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrjhqmh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtuzksn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nareklse.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaeodkw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2krbmfemj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2odoirnhk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqlovzf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbtchuz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axturxfq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcchqabk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2klceevfr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoapwri.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsagxhxy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvfdlws.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wviyqghl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rovhszzf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djmzqzaa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgniofcd.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emfztepv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aernscql.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrmgchp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvigiija.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbcqozk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwkxgaw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjthlhkk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfbntvg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emtdzyof.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuovieip.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcchrrj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpvhclo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrquegr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcnuwef.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaxljaj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhgmmyn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2emiydwii.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gilntfgq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbynwrcn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaizwlt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrsgruc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgshrdzd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbmpdrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mcopzxwk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svexfvey.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnegunl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snvyobwh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srejscux.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wemvmuvu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiegmyq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiukeib.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hitkydka.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmjiuhn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nemvbrmr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2guwsumtb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbmjgel.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2muqltznx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2poynxiqn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vylksszo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rovkivps.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhllcvv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2anugogby.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbshajg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhjazzs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwgtitq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2stvrdiph.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2taghljmv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tocapsjo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ochxgfvo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dzubnpvf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ndswvwuz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqflepav.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtavnfni.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfyacrf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grhgwkiy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eruddpoy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uszxlral.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afvbffyv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdahfuih.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qblnshoo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxzozgu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzwpapp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meohfdjo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxixzzab.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2szgygtbd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzofmonn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpxeked.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzwqqls.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgthovz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoeriok.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xosyudil.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bsntyyeq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjuuekw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvbcgtl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqtbfnn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdkrktj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2coubdktq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2emimvoco.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2slodkyqy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmrxskf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bucmtqrr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdujjph.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxyqxke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tmppppeh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwqllxu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2boiyozvl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyhcibz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwvxxyl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwlpnon.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejlyqmn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2umujjita.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfmnuta.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zqatrffp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dadncown.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wharvpjo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuudqbw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2advovcyc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mirmxcrz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgydrmek.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rolkyytv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vumvmsgi.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnuowqr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pcayfkis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xobnyhqe.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkvtifr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhevwbg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kuozrxqn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vefnagve.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmpeeft.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olfmcwcv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2llmulwfp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgcgwvg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2srqcyuee.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrvdiow.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eytmgmgj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2busoenzt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhddvxbx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlktsjqe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfmtcxu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyjkmpu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwsaged.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjwutug.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbacitv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbrwpxr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmwthny.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmslfif.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdgvuxg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2akmvaiff.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmpegoj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpkysuu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdoxbhv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnglyap.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnhfykn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2risbmhyp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yvblcweg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zknhgxht.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvlznwf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoltqcl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nppnfxkf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzgnseu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxvccbg.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmzsvxu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iauyhqlq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ykujtzgi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qksovbip.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzemrnr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbswxve.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylichddu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2orpvbswr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdkcmqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stvscgkm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjhpnv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nohysnjg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsdwtde.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhgcaie.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nrirthpe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeljbahq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwakwdt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgkhbgm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiaaatc.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2savvlcvh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfipolkn.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2epkqjhem.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaptqed.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlisbvt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2svzolvrx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2myjaqmjr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiahzye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrfwexe.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hccmdgxf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsgznrn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdxpyfg.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2gledmehv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdjpbam.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2urzrhoam.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvpaihp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2esaxdeui.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mglkzgzn.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwmoixc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ushwdhnx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhxlyvd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2rciwhadd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhlcqoq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjirhipe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlmezdi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2pylikrpc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gt2snnmrqca.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoaexif.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxmnauj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2noxceehx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgvpoco.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzcnycr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcpcvsp.html

Go:   defer f.Close()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftniskko.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2orasigao.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzibzpo.html


<!-- 参考信息 -->