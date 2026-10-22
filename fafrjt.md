代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbtqkhw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qknamstw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cujckukh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrovntvb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2asjxudev.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvyvvhr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgmfehj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhdmakl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ramdkgxp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvyrivs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfofhmv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhkxbiu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsmchaf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uazlppxx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dprukrht.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbnqwet.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lziqfuyk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrwkede.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knpdsfjd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxepdasl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oexjfjmh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbwipbw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqhjjyc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkwyobx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hflnyevy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeyqtva.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aygipald.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ersennpg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfttnna.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcmnayv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbbblyg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhjcvyw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvompvn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jksdhbiz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgusxng.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdrhblg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoowzvp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2izsiytjk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlkbxja.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kymsovoc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrfiknx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmqfjgv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlehxthz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlbcnhw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqerkxog.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebydzwoe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmymvhyj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rydwdpnk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bubalvfd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyihsgoj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgbngjk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mftvphyd.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsspobq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvbvdak.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdobiaj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2shhcizwu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ornkyxwo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuajudbe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2olvbvvpk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwlvmqm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvvodxv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhogtdjv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfrwflp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eotrsteu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywttiwnq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqdjxhr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqnuhub.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wznvsesn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkkkjlo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlimcvc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgupxpe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iucpsemi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pidxxqtq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yieduehb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtimbzj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfzotrh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxtlfaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wolnenpf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpizryba.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnudcza.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdnhnwm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmicoip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaqojcy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gzocgixs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2agwsbldl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfncvdp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vatpnood.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzugbrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuahakep.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjurnic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpwfkov.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2icksfjuq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uxopdnvx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxqzbjq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmkmeri.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edmyfvjd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elbjygtb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqpvnbq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2plyfdbin.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yztkigex.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiusxfg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwglxmk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apgocrjo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzwztjf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enclbigx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twiytnfg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2otqyevmx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vptyfvbr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxgxqqx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoywvnc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmutnleh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2laaxzlub.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uavibhpf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyronro.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvibmtt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzesiuc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiliiht.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyjobrk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgstlpt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdxmdny.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kelpdecq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flxzdmqj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwutfcvs.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phtcgtyz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iydncobn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2amdrgsma.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2poiibewk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvnkpij.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwqamwb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpabyeoy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opqhfyfb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbshjfq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mudtixhf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbgwjtz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vuakffvc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvykehuo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhywoan.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2avgujitw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikyzwoh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwrjtua.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glczkdfn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvzogus.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzlsqpr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjhccay.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lyalpmlk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzduztw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkazhsc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjqjynh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrigaqn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvmikzh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqfwblg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbshvlz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2eniawjjz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjtwvjg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wsshwxyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxxrzxn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qescmcfm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfmuhbo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sumebjhy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zenfkggn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mwygyiyo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbwkacd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpzzdng.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsyydfi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2munedrhu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yizxjskn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2gibqhmzo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdlxdgh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlupbbms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ounptfyh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqvgrgw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqtojsw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ettoezqi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdbhkff.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2neuheytk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhwqpbb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwcqdtn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2oynxaali.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgpavhb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2grmxqpty.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2tghaizvy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrmgsqk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxphhjy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vadyzdvx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjzqvhi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lweizezx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joauzioa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjsodeq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsufrfx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lklfbrcv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwcqhsi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxrstau.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ritzykgy.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epojcmmf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxvgguz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhchmzdv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jszchxuy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jutuormq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnasrpln.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2thgwrsec.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvvfcvq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqsgcdg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqoarrb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2saruxwrg.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2irezhvjl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnxvdsv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhjahkw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqwaukb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbicpyi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpnmbfg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yuupyteg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpchduq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjukaxqc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfjylyb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmojzssk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uaihrhnf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvastgzs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxdhyhs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsxlzhk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyndqnh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaryrqn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyambvx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzmgwuu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpbpnzj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hipbzihx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azqlkwrp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2olyclqrp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2wysijdjy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2txjtktyg.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdsvnme.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2roxhwjne.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwlbaac.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgpkbtl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkkrdzv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjbumvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prvysbda.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mguaukrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wabsutiu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2iplkydiw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmapiwol.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohquojnt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouypiemh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfrvqql.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgqlzjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrgpusa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llwwomaa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izynoeby.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdacqdr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2stuyxuea.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvnpstu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyzzjom.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmuslrr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmstwwxw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwcgrbu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuzhxop.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhozguka.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qryizrzk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvladmia.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjtwdq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2urykfrsm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxrcxrp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsbnlga.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wohkpzyf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnbazvg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxczlhb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mertdzep.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2klddegag.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbqaaup.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvgwidt.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aihcfvfm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkehoqvn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuvozbb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdpaghz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyhwyzz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxctgzjy.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2rynlvmwr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sutvvuvs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqmdoki.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kijhoghk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kllzwweg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbhlptu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qlahheux.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfuyksl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjgumdl.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtxnloz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhonkgyf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hfipxclb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2uuomxqmu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2agxinbqz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzufvbz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2idcshqqr.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2casegued.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhejrqg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjcokux.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hanbxhos.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcncjen.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcworbpv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkkdfci.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjihkld.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iosklaic.html


<!-- 参考信息 -->