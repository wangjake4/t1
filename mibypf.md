代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqraquys.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmxqnwx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvhvedo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdeutrf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrtjohf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tncxdxji.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyfmbcj.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycefvcyw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnulcjss.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkvluop.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2efzfowrd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuadmqh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbewynoc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2snzofool.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2upafxmad.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmbhcub.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjtgexy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqrkvfr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2naougxfj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovppoezm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoxawog.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oswmmjcp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwunpgcx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htwcwhoq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vislvaji.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvencput.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvwtbev.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cojithxp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmiwgqe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqkjmxc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oowijzlp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhpcgbd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2takuaqyt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyquhph.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfwtopb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbpxjxg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlrqwpq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyvvjjh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpcykrt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjlogty.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfckdde.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxrysxf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbfapwd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vybphxsg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixnbqpf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyhpdmb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aodqlwjl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2miswzysv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeyvidu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fveghlxn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2avmrlszk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcicriow.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlwums.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvyapwx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqudfoy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2edppraod.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvexvct.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfebsxed.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsryieen.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxxaecx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2npyutgav.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dyahevjs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eopwsypn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlvlppo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2myiwocwd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhrhhzo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpkzbob.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwanfss.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkheuclz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nquwitzy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oknteqsy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkirdcei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uurhaezm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2socgpkfv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2croblkld.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhpeuny.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lhibufqm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwtbhrp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcusnswj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vaobthsb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoehwtc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2yitxdedj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqgrlxp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yiebjbyf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bkodinoh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2swdporeu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkefzqg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2irmadvkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klsfpovv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jumjgmjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skddkspu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxgcuwc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2byxldbli.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boruudkv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxzsswr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mapmxyyj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhngwbsk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2iulxybgn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfuotnl.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqyvbvq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjjtqkl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfemuijh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwotmxs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqznvdh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrvpjfp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhnhplo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxchshan.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xevsyain.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txsrmcmf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpelugq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfnaudv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2twpbzopo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxjanoe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfrgmys.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uprxtwmv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dyypplst.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sstwvjoc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgcpvve.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcrfxoq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdgjfnp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viszoxjj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugennnxf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smmuhydu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddshrkeo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgshyk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyiiveg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hscsqdvc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvvgpsp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2thvingzu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmykqukd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xekmduxa.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xamxhgwo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmazxjl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kskqktzh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eglqurqu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tawmqkug.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gntnxwbb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmpiebx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqagdumc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xstjaeio.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpyajqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npmvwede.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkvjvwm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpdzxch.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dffnxjut.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfnvizt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmxqnzs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcpwfab.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqwsrbj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jukcsluu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpkcpgw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfgezys.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnjxdmp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iynmzpko.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vrytjqct.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcyvifx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysggbrzv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gelkqfed.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqntfmhs.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fakiddgn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uazftosr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjwzdvm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhutexqp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzxoyrl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2isrgvius.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlppbuq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2zsldjxxx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtibilf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwvjxbo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsjzztt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkiclof.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbtizn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpigtjc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2powlsugp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfildme.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqmzfsw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rjilkfmx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrxunvs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2epoxgczz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjhwodv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2invgkmmk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiexypu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xicwagdc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2honwesgg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrpjowo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhznqelw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdibrvr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtslkius.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jivannqw.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfzynhc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdahxlp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2agxezlsw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wanbidzr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvapahe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krzjucui.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psiuxllb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hodeploc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jggqcawy.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqyyupg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mveqbjyi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhzfnjl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjzdtqz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2auwgkjay.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wuihzaho.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpxounb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2feqrefxp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaprewhw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrdmbzb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nxatoodd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2huwmaydx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2punvzpgd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxtfaus.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2trzljqxh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hokaqqha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqrdtyn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lrojaxtk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kivcinga.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qzclhicj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbspihlk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzptcaq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2enofffzq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nergzppl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2yanvfqns.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2saozjlcz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ehspdzfa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzlpnzr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpqqphq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcdvuhh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2glrppmrh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdjdrcr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwahfbrj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2esqsajsq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hexmhidv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mddcliyv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bttxblaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlxxcfb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfnwnty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlhxpoc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yljyrxbu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcmlnnk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sluvjlqf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czduuuud.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frhocgzm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrztmxtd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kzolwfmm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjpqbvc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqwscae.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcgudpz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2prvntrvi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjxoudj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmehcha.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqyvsln.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2paxlnwzd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2frzygxoi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfrxneu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmayllu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjwjwgb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hicdpyek.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcmpvxe.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiilpjyc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwpmowu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrvmzns.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvhjfbm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2npuopxom.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxccntru.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkvvtqs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rzorfioe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bemfddse.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niaycubm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyfprse.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkcljck.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2laquguxx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dchuqxzz.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkadtlqc.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fajfekky.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gttgofeo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rphemqtk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxnqlry.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvjrgzu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuzahub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhueeabr.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmmohxb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhupsbjk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2flzqoxjv.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfnaljh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdlpqnu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2henricby.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnzawgq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfowhraz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkxoslu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqemvhqf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dttjuygr.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lreimtbl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvclkopa.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2edxkxwdm.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtkwvvw.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2luenqcgz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2emxbjqss.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvmxyxw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xbauqyea.html


<!-- 参考信息 -->