代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dumtwyyw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2segxexbl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cogwuydn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2txodrbdk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvknfer.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvoagro.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcapzokq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkweoie.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nruheihg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxkyrxt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2crrctban.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhihjnv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqaclyz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmcbrkm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2paigrkrl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsqjofv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fokqiqmy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2murgthcj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2owkkssfu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfldjpmr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kurhbkto.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xugemsuv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lybsqdxj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrajgimj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irzplaoq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnewust.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdjpqzi.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwrgutm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evztpkxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxhjbjc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmamwlx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhbrrqp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfdopaj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnavfnd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfeqwod.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzvejew.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2suunifiq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfanbnf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2stqgzzeq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2icsuedfp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiinpcyw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjitxlp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2htctjumj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkfysjf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugvdgwn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqtzhfq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2brztvudu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlvcogy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcngipo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eatmkkxb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubogzawp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzljhaif.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qivcwwhn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwysjdvy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2asrrbdvb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2okjhxmmh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2njwzyrxy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfbsbnc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tktcpvfn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbokubmh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhidjvt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uedtwmwi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfrkezu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2onvmcsus.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvvwxdw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmwnxpg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkynerv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbzibcn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrxdkbc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaajxxu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szknqhpe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfigsbpo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ermoxrxi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kajcyair.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sygqrwhy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hagkivaq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmzasdb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnojdjr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zahcghzl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyqupkm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqeoozo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jffnlbce.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpsytrs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpijbis.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxynkxg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvbkrzc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2itofbevd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrzzlwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbxtkfg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2skkxdfku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxukzfp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ougfmzpo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2phaxywle.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpifnbf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usermdub.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiszwlt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osisturi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdqydgk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqxkbrg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtduvkj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pepgzbpy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2auhbsyyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qffqkuzt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvziylgk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sruxbvxe.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyhvjae.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wghbcptj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emwlzwrs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdewywb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmejfsc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvhhvmr.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zakmiqvo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfuoqoe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiiebmz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnxghec.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqmpypm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqleegz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2apwmiwdk.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2utxkvosr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fdikrdgy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwjocbr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljlcres.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqessnk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vppdvtbt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cioetcpr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aesjmynw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yarywmty.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbjqhhl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2shikitwg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdwrrel.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnccmzw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeymqrsm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhpzzsc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgnwwhn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxcjmxq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkoqstm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sfohzrau.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2aooxyeoe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcghdbrr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axdqfeqb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtuqloe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzrmfvf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjrlbht.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bynintda.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqmchpo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxsypfw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwqjhrr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2blsspiek.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeqavuh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ficmyrbo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2njbaonqw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqorege.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2gelvtgyt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwubtvm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2phgmcufj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybebyx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbeqeka.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nokgffjb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epewbzmv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhjhjoo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtblwnh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuigfyc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vojazjjt.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbcdspi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iopkqgao.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqozcvr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvehlge.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcbcgqe.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2puioidpc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmffwqvc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pigulvml.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amrxskir.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rskiyujh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvthfwv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdbarui.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2boaiauip.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cblyvqqc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ilucgogs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iyodfrdf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkousob.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yekkawsm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fehdbkvy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmnqeuq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttldcmvi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzoxbfn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieemaykk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zesruofx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvljonih.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2blnjyscb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmlgnee.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mitwmmhs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2omotuwts.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeipify.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbprmds.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidpiaud.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaaxqkh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfcicxk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzileon.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvnmgef.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfblxgwl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaobstp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrxgijn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkglnre.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhneaya.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2scfshown.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzxipww.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyewfabe.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2limkupww.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jmotqako.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpqbikw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxntalg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtauamk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2odzdrjdf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzjxqfb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrjntsi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgrulbk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2iotdqsjp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2albrylmx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hocumtbc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkdjeed.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgmswdr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvfknjn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2tehcpyrk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfrmsyx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2deauvzby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaqevoh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqhgztv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiqztzr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2surdftkh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsfnack.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eosforus.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuczjbdw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjsqztc.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtjihqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzkfcfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odjqvnwc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlbmqwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qffsfjkl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ullldqae.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyyshyl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrorlksj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xogwdkyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tplswiqo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2geomcklq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiurkli.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2isfoepqu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmwokea.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2euguoliy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpgbtbt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2robucxey.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkupylqq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyspfitj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgkcolj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ehitqomj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsnekmq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzulftx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmzqpdn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2byauywkm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtkxnrt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uagbhqsd.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tatmqhyp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2upnynqsj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsymwjlz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fapunbfu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmeecoq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2usbhdhgz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwgfnea.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmplyeq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csffvlrp.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpgubmt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgjrhot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyttxtp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uddcktee.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjpanqz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsacftx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2hujuflpx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzknlcuf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scticmbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2engoxiyo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frmdgrzs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnauhrg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfzhfij.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyyntax.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeaculo.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2nescekna.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxqkegv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmbuuwp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsqpmsz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2djlbragd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2inywlyce.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pybortzw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsngaig.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkfvqqq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlaewsg.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2etoqmjsb.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzxfuzo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxupthxb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcsiuwx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqklute.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iasihrwy.html


<!-- 参考信息 -->