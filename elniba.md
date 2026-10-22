代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjhpedu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pozsugup.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xejbdgxg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vypjnsec.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpswzir.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzbuxsj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrfuygn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdgdwoj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfdghum.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbybyzam.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhyytgw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgiauls.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxvjqao.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmsnqvl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lurrucev.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfaaoek.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvogzbk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lutkslwo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyievte.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2htkjdntl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2shosljdl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2glhxjjnz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fngsnyot.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tykrtleh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrxrbow.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmjxkse.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2meprdqsb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dantxgbu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfhejjw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkycpbsg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwrdgjx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyjufje.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zezmqboh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwefowkk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trvvzdvf.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jllyntsp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gowvwoio.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2linhvyji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqspokyu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lynswxis.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djwieoim.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrveotsi.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qivxoufw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaymdfjc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwuqryh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxynstx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmfwlfh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntemqixd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqtobpp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhndubx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nurjdvfp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxyhbet.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjnjdwm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkboafl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsjjjkv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdzunkj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbeejtz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdhxbcv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxscnzdv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmiriqv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkltukm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlnelaq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2evszslfq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kpztopus.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yojcpyhj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwkbxoa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjwbbdl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bogifpwe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjemlhn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ywivddsx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwentpr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2frkfeglg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gttbekfg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vppgmucc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxseona.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpwiopv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzncblyj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyaylne.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfgseef.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkiutgy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aufgteln.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsmadmy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aevhhiyk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izbtoaaj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxsqwnt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avyjjeet.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrnhmes.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zwojobet.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuwnvux.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtmeukg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qffiofyh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2otjanghs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkuzuxe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2asoxqcsz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeefjwp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtuipgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfwpjbw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xaakhsnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjonqgjk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2kxldiqbq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yazfrjro.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rouyzfid.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkewpphf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnvlglg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkkehgt.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2luigcdtm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fizuzsat.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvlkjai.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyofazg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2byafgvqd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jflwcppg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzghlzkl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icvfzgps.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfeggwb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjeqrzq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slzbqyom.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqwpcjq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jvahsbgf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kymxuato.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ignyelub.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnulkzg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkdeyma.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdtekow.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fysmjbzs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwbxwqw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhifqhb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfotvpng.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2updfstam.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iafpasqv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buiohauz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrucrht.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzxgsvj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jafxawhy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtzwdcw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcqyzvw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rshkztay.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xaledtlg.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lczfxoym.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtexzro.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiowgrb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coybvmcl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwfqwbp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlgvzbw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcgwhqh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vnothkvp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2gihzvpxq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbetezma.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnouperl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqfmwzj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszyzard.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xiihfbnc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2byqabycw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgippug.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2goaxsrnn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpksceyg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2slmgfpun.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2todvlxsf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrppdum.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wykugouf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfecqhe.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwceoay.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2leplpuky.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfrrekv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cezyuumq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrthjox.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amprmyjm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyabwzrt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dygxrrpv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wxesylef.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrfmwyn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsykxmff.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2oykgbqfc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2izajdfmg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdqzlqn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxfihuu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeuamqn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcoxvcf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utwlgoyi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcdjssz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvxzdyg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlyhjvd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2abytpryr.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnswetp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2juedooka.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zxywpipl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpbngoj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpevmsq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tafhavpj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dpklnqjy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqtqner.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmawctt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whtusnox.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubmcytu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwijkyaj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnborucl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgcbkhf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjbdliy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfsidhw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2synhdzcf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfmzods.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlimrff.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdkpzag.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvnzlif.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sypgibjj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uobkqjsn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcdhcvo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyraapb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpadysy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqihskep.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxonmfl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeoxwtc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmrtgdp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lknehxpo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxalzss.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjdtrkz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2boagkmmm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vofvyysl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyojfvw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qzttzttv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnkrouf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtawvrzt.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwtesip.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pesbksdn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2suyytlev.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gogihrtj.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtvtuaw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfrsjdb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrepoxa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zsydtcuk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2adyewxvr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtfowjz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2acjodbhy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnerpog.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhihdqou.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkrnfbe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfxbdmi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqocoydt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwrbasd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fweazqye.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mihijdfg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gzydmpix.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpymdpy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nvitgsiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uaocigsj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqqrfjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkcztja.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hszuconv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2embapfpy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iojctszp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvrnlhi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmphsuxm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwboyjjg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqopmwa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtnqsag.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjklvww.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnbdfow.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfndzto.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrablvd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaxdmio.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpgtxcf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igpesagl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjbgfag.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcdzggh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hubznyvz.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrarlos.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbrwlef.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjigvkb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzbwhdv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxxptuz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxmpwmf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nezbtvwt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcimthmv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpgcmij.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2admrlqad.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsccmvs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seumrzso.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcrolka.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oueeigvq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjbkbzn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsjflik.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2atrolxxf.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2raqludvu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytovenej.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nithobix.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkrmkjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxqvbuo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjczrrwm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhiwhwo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2yipmgaiw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdsvlsf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nklkfhky.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2agzuofow.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2vknbzgdb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgvcdff.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlsthhs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dccjupww.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2itjwshap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzztozt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooozdxpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kdguxuqi.html


<!-- 参考信息 -->