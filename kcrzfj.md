代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyygxvnb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkwwmjh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgaqynx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvtmofw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvgbccc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rasuuaqq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2saadeerk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqecolf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkzvrqr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2oauqrfsd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlzhcct.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iouawigf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zszplmit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwufysrt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaeslcj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqxhghn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iifdoxyk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaykjrp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uejesetl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtuczsb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wasvatcm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjqukcn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2puyhahrf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jikvsopy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaugkziy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzkiejs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzvjtvf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnkiveu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qraioxsv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2msymnwif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2sxguklyq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmheghtt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2usoqzfyf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmpijye.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmphkqh.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hnozhhud.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehretq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyshkwk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yokahcgk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqxjokh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlilsstz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqlleao.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ughoojfn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2upbxabjh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gvselgmo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbynbkz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkgxkku.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cahatvsr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhxgmir.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkybknza.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjfbdxl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkbsqdw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkucjhw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzchplt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsefztr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxcvpsq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsozliu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brvdoncl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2akstfbdb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obudnthh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szocmzdi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plebaxdl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxomtxcs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsdbyzw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2srvugwuv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpkyuqy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avjjnnyu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sywlshjf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tftpttjv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2syososoo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdxuqbx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yhofroxz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmgbugy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvgaeep.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gmijtxti.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eaibeyhy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrgfyab.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjdgkrx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyhamsd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxaujpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnhdnho.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2esfiszgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alztlevr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjexhpl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnfvnsk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glskfhkz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqgfqnu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkpbjjg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fktoykav.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfdgtjm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wczgnunk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtinmkuz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqalzhuh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwswsoa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tukggdct.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smydhtps.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaukxdx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eopmxlfw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2swgogifz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbzvagy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxfobtd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pavgnnks.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2egrqjwsh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkazpdaj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjlrwzd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsugpuz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpzktfa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuljqoh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoabjldw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bieujcqj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfhgswj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpfqbva.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjkjlld.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzkzltn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tctoygdl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphaxpvn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubliwmpr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrqzwwh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmykgoca.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzkmpad.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqifsbc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uktccsoi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjfpcqr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgcrzbl.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oitngspu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhxqktw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxmpskx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlouutji.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jpneiywp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyljsfru.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kseptefo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidhhukr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roetorcm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjkgqqv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jczpxazt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqciughw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2szokrwyg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tognwthw.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2piodaomz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zevzzgkn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlyliee.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvshqov.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gajkvfdx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqxnwhl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zptlpyhm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cygjkzox.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfvnljv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxdzdpn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zultvpss.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opbzjuil.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgkkqgk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsysowtm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxyxyue.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsbinul.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzhlhpw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zokaaxzd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ndafyinu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdioofg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bsytmcte.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqofvjpa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2voeohwmd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uphbeisn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwgvgti.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epgrcrec.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tbprtbnz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzgwuym.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnqadlj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2izmnnreo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fmehzvzb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nmroxqrw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pwupsfun.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfktjuv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mccrprck.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hphicgan.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzkcbbl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxnleur.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bacymcql.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihogmgad.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obuyrswu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2shvatpal.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwxebtx.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omdtzfja.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmwzmaq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cwodxczq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siqqmbbr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhljvbq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knldppvq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjtmvpm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2avqpqiss.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jykbeahl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwdrliz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izkjqoys.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwltmwsl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwzssvw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2efnkumbt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2anoasfwr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rddlcuxc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2opdskmol.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeclxhx.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fuilqspm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mlenjhws.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwnmekv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxxvoxc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2grriqzvq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhmdhlb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irxlgryf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbwsiax.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2unqdlpdk.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqwwupp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhxxmmc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2guhthiqw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnqwzxx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjzxmhr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qinfznxb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2txtzjptj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsykuevi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjypoim.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbtmoiw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjolkva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lxexldrg.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzxdoyu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhfvcvr.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsdysdu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygizgjiz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmiaibo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dudfazwp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2csquglbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvusnmb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2upumfpit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyzplwu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgnlcqy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qplfnzud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqkcdux.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbleophd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgsbvjf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efnjgtfq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uksnooaa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgqviub.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wskkmqlm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2admkwuui.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2vozbqyzd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khiwtebs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhdpigc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2erlxjutw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrbyglj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxfwoya.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2facqcmpy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfrxacr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsrmbtb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyaakqn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iumzttct.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyujlxhg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2reilqzix.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nezsrjio.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2avunwqsm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuyptru.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wewtcoeq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvheqapg.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lihvrkgv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vigyzzwj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aisdjvoz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmvkxqq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qotqhtkg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2uptuxspv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slmqxskl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbluvqp.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiavgeb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2cloofmxv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwieohp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgukhvgb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tggtfqns.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdkbtot.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kojhrppl.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2obyilpat.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hppvjwpw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tktxuqza.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2txvcdtul.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwptgjr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2yapkfxsu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2preeimir.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2dutqpvjt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtefuwqu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfifbtl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqhdncl.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aitcxxcv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2vphbiulf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjysiihx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjssybkx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfpaiqj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2juuxonpb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yctjsyop.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtdmux.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwcgnlx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzdkkry.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjzdgzl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbcmtuo.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuumaib.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbphstnv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyghzbb.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoqtvyj.html


<!-- 参考信息 -->