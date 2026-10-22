代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvhibkm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufchjpvo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wscncxlq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkplzzjv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qouqrdhm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhliiswc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfgsfun.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2homkvtvl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2srjhhshu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2txrtukca.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiyusuf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeemlga.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkenynr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqptmlx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2awinqwrh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elwvmgxr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvoloey.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuvapqd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrhlygi.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeejcju.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhwsbpy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvezbpg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lknoetrm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmorbadp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdptwvd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwilyszo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lljpqjqd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyjxuwr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2prcuwewm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmrbjfm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzvcdlo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mleuopzx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhlemoq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuvwxbw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnueaae.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnffoap.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsvhzax.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mthkhzre.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsebhab.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uivrozyp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2okwuifan.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgdudjl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlljhdwf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmigntjp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwwunng.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyptejk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaopcfh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuimcxq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpybcxr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwixedyl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fizeetga.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsgttws.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiznake.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfltbvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkluzubj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyhmlxk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grllfjiq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iydqlanx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnbhmxl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwbnnkg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrszhsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukehbsyg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2loedczhs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcngficd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2refpvsxz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhgmqdp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhpyasz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsyidxx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvuhyvv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjrbhjf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfylhqrd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvsxsun.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2twmfcmkf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yejijdvx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjxolr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2szzoocyk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpksjuq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxwgcqm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrhdzyc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2amydcttb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoshghi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmjkhmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snzjrfam.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jjotttjr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sstrumrw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgfcshs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrczyxg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyocwlo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzdmtnk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmtulxv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnmwljz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxutwmr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggazwhzn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyebind.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwznecvq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vooidlht.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmxyuht.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esyjczsr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwaaxnp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxquhdbe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgxtzvr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nyusjsmx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyeclyo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvzicbe.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2evdwxnba.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfhzxnq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2batjebxu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfevyzs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vewktggz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvdajzs.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2soefmvix.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeqriji.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsnidgo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frhajgck.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxljmyft.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2darydiom.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvtadap.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdwacmy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mipczdvl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgyqhcr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjrpmlp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfzjiht.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qckirhkm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mildggyw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifehtenj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oinmjuxk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbllbfrj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsaljvj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqncbjv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhflcfw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dghfkovd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eikmintw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyqanbn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veismcut.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zevrlhjd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzibdyw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2seeqpjjo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpiydsb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqzhsui.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2imzddwww.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpqmhml.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpqtunu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjdpkfq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyfvlyk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uiatuisy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2reurjuzh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqheega.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdghhge.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bykndquq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2illyfsfm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnjiabo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vesburer.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmvfyox.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rczojoel.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxaveoe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2myjkqoao.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgcazxz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyftyzhp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2cuthxwis.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzylnzkb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvacjub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkrajoi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugseydxb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2riabclci.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhgbezr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2uacmwfsm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvdzlcc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2isghabmn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlzgzdn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jojqxeaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkfpobn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqvfodw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxikxhe.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqnfaap.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkomavs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfwzaov.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcuewwv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iazbmbel.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyulagn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lprzblcf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhschuz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suluabte.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvtgvcp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkoupyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyadkno.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fioxzeec.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdfuqyo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmapuxyj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiyfggk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ruobblpm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmuplni.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsegmvk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgtrnol.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpzsafo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2artdlelf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvvsohc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vdegwclb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2npztiknm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttynyhax.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vckflgvd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzdynxh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2enughvbf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoedrfv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvutlzu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhwtdbc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwqhby.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhjznxr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqhrmwb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhggobj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpgjoer.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyhrxok.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugunspcq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzyrtja.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxxkzhp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcpaift.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcupwpk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2snfrkiby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzohdsx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2btkqnzdo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zafrqnrg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqmtzaj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpbkhbq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcehnyk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2btbfxykd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsslxvw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yarkcscc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hobgoypk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzhgpsv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyvxbrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhgrwyi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ogroeigi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxojhcpf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbutzbjb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjoarwb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhjoymp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxhaxwt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2stfcncuc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zczadjno.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lravzjyj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ugojnewb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcefyto.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtocbhqj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbrjplu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkawbdmy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2geoolmwm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fapljwiz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgqdewv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcbhdcp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbnulck.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgqukgv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gozyeehn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2golajwbb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxinwzz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqjfhxj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwpuaaz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2sstlzcmj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rowbbbxn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vymrpljn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvmpnih.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwctstl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glmavviq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcniwyvn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2semjjxei.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmefrwqb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gosmszkx.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2steorncx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rigjdimo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lldaupor.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tapmgsyz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oskutdfe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzgfism.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxusaeys.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwwtaag.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2emkyfqto.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiihspl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqmmszs.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2fnscwmwi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2azbqfcaq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2crmtbdom.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fusrghds.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwxglce.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmuadrf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgobpymf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2luxvtnse.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ncglepfi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2rubkymem.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shiinoja.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzqyahs.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2utoxbljb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2scdbstye.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qanlrhuq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzctrjz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmevxzef.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sxysuqct.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgfcomz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfcural.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxbooxz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rndaxllv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxsbxvh.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjochky.html


<!-- 参考信息 -->