代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgottozv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hotjrjnc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjxyxew.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyktecaa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoqftym.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zevjlgvw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mposftrh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpsiccb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsxhwjo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkndlyv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpakpbs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2frwahyms.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvoiafl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2movhemmc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdydzdiu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2epwacykl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jczaeyaq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyllyfr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnbqnfv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2meysiefn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlhwjth.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwswsdfj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxwquyz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjkhdin.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nztjumjo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vivcrtmn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaybqye.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlduhdom.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrwvipl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clnbomsd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbohqaxk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djtrbxqb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oacyecll.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zltdyias.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlsooxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2athuhdro.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wugxpvhs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrcypxm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2edufnwas.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bonivtvm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbjfxnh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoykeywc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtfvqxe.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xckvooyg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoufzxc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrdvrtt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwskfbmx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqngvbha.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2roqkxytz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpszmghr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcreujm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2otytdfrm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iynpuwaa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2smptlarw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eesvkzbc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2olzojjes.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcxvtex.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysckrljz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtdcfxz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvakpezj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2osqdhphw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2akzkvrdh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zggnyhex.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjsrxgq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uabuccdm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmrlsaf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoavido.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgikkdmc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtuxhhs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmotraqr.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpaydvm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsipyvt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzdsqjy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tghhszbv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhdgcaf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixulcjc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xglqphui.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzvihfv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnalyij.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2volwwacr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvptpof.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xntdtvbh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cndtpreh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoholtq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2saojxplc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2smdrlwog.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxysmkbe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2udynplab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cugbprdc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcmmgqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxplhxd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pytfsfgj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aufkkiir.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zymoyfkl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swrpteta.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhqkvdv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tikhzhsr.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2drgolmdr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxisajmc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2troarfpr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duqtnydn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdlvhte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edofpmog.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkrllgb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrhfdsw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvogudlm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2spipplbq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvokrlef.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlnjcud.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2effleerg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jitmmghz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2delmcddw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoolgsk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxrgnhj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xipapeum.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbjlshv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrjfmwm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyvnvro.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtebzda.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uknwcprp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leyqtjcz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxshqxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvodqgzh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbdembb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmbxdyj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsattom.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkgzgfg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqltydd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ztruchkz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxqisgm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldshckko.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhkdpos.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqkytci.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2erujmcaf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdruml.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvdiuvm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lsykqznl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gshatdfm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxefwbsw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwokqqhd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoraures.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnkjajc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tarlyvoa.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezumgqqa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nptxzoff.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2azirhgts.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqgkdlw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vndhyhvc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ksucdtyy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvxyonx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2odyqqwea.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2leejisnu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2etitegdp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjjasdj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tfscfhwx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2orpwsfvh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrgkdfz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clyxzqxn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edmicxjm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reskdbbn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgolirw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sixtujmt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llzynhgp.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qutlaouc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpwjlfx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdkdutl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkdqadq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcgwpxc.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjztupsa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfwqgnw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxtesgl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oplzgmpg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2iedauuyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwyekrp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxkfmhf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtkybgt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2djwjkmwt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2olzkcsod.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2occjryyp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ukimxbyu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzvcwxv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxcddee.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kueuuyvu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaqbwpb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbjwdcs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygryqjyf.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuesekdw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiswboh.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2cofoamkh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baaobfdg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2syjpomnp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmhhkoc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kleumbxq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hylfzkir.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkczfly.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oivxmntm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnajptbr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wozdepfm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyqjwzk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcspbbe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdmmeqx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlayecf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2buvvtmfe.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2howdqcld.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sjasijua.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhjqtme.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxceiml.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoalzlo.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qvulpgxe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrjzgxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdatqvq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fysjfimr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgixsbc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuydxojb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbxmuja.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qvginwkx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeedrnu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnjwdly.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhacrcb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzfqiyn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmsmdkh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyppcmy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sewqpvxk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcthgxl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtrctji.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wymbigvz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdfqtau.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtthgoz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjzxhsl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjhescl.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwgdsng.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2grkmpeiq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2noeaotis.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkeuiwv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwoinzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaezljy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2abylsvkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzliuva.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgliprs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxekxer.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvmxsnj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzvxehd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjfrdzy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tavhdxmh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2idcptfjv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzsjozf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rejczbxg.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dazmrajr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmpzvuh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saazhqds.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zghtehcw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqwlywt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhojpxom.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kuridpti.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zabaxqwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmkoyfz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lciyjfka.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsxyzol.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqcylzm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsktpjnd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnqddft.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkmwpow.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qharclfz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkwasjv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjxfptb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoootnm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgbfger.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcbhcwc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeoavll.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clefiert.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnapojp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvigarar.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hemfstus.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpgvlfm.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgvjmll.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfyzvxn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdorgrt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtizjwk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdzmvaf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muegvqmn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzldoezn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbhilcz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpcimii.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2aqioehck.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2txemplya.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhjmkdl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyliplj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaxxdly.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpphjqqp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2buqwycgd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lztotjsq.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2agebjlch.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxsvccb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2icyfvzbj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmstmxu.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2opzbpkjg.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2codkxixr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxrfudb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuxyyay.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxczqcl.html


<!-- 参考信息 -->