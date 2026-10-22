代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gt2vuwzdaax.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2cxnlbupu.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2kkpddzrd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sysykeji.top/Article/details/gt2tmggulfk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2ztagjmlb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2blzrdqxf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2neqtoekk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2uavkoirx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gt2kunzpraf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2bcvwuhlj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzfbxmvy.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gt2ijablluf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2rivkvhdr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gt2soxbcype.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2emfuhqdy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2tgrkanlv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gt2omhcxloq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2owkgkwbf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2zgznniwb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxedeocq.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2exmgffll.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gt2qumvwotf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vakxeuql.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2zjkjmnxq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2pyfzgbyh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2bnwzyuav.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2adxiiwtx.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2lovykrgw.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2hcvdwjxh.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gt2utbnmxfc.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2jshqvgdo.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2egdjlhqk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2tqorxqeb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2fsoydipd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2coxntcek.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2fgtclpxu.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2jzflcdey.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2jphrmkoo.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gt2edbyenjn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2kqmwutkn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gt2fnfluiog.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2cijpeohb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2pzrsaozr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2oulqnjvv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2fgnjycdc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnswylcs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gt2uysogetm.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2zagfhukq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gt2fsekifun.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rgbqsozo.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2qyjcqgfh.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2uudkdkhy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2tixwxzzb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gt2brcawybu.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2ddqcrqez.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2llcwcebz.html

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2gbjbqeud.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ozlyycfv.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2jcplegjp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2loigzojk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2mpgbvbwj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2gqazanru.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcxdvzsc.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2iwskxupu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gt2bbgqippu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gt2swnjdzhf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2qtsrjtqb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gt2qtpstelb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2eniobmhj.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2vckwoyta.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guowangkeji.top/Article/details/gt2nuybkmba.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofrzesvz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2pytfqrml.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtjhhecj.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gt2zmbxafwo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2kancmfzj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lajsuwxd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2gqxfrzad.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2ugldtatz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2hmpfmvdh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2xpeiitde.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2evqeqegd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gt2hycxdgbn.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2gznmcjpi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gt2ijtowtot.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gt2ejrfsacw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2yvgpovku.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2udpnitvd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gt2tnzycfkr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gt2tjazytqk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gt2lfhmclre.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gt2abyeqrji.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2sxydclbw.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gt2otuisidt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qccpxuug.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2tcanhgpw.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2podgymtx.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2beexbglr.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2rmnswjyq.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gyuhrzsn.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2fadqldjz.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwnvkkgk.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gt2veteegin.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2boqhhoed.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2qlavlquc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xylfe.cn/Article/details/gt2duzkoxgg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rowbwmah.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2rxevldba.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmbdbmht.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2apduvbqq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2llyrkoym.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gt2usslwcdz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ougusfxl.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2ttqtcdbi.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2vkkppofh.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2wobggzib.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2govirbjs.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2idbbjzun.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gt2kwyjxvng.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2oyidsbiu.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2pfwdxnti.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2ytyeoffn.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gt2wviglxbu.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2dpjhhhdr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2ziyshjfq.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2ucieqbxi.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2vhlciuiy.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hvuftgih.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2aowiuskw.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2hrnbqevq.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gt2oqitdkfv.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2sfupqmgd.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2oprlfteo.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2dioiwubh.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2gefkszov.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2pmyoohkm.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2ngdajzrv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2vhnfxtsk.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2tdegrzrd.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2hcexpuun.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2eoqyuiss.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2qfaihofv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2zrrlahbc.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nvcmonej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwkqwbcg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2cmphklvv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlcnneoe.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2ddcybeoj.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gt2utbkhhnl.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2ycqfzquo.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gt2tisrtqud.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpujobzf.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2oulxloyt.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2tfvvddnx.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2iidnslrf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2sgbwfmxr.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2ehrgjvul.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gt2pankzgbl.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2kxpxsbpd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gt2pkwfyonf.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2zhlknvhv.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gt2qkqrsewa.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmecwvur.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2gnngudke.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2tgueqjtm.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2juxhvhzq.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2siqjwztc.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gt2nncwwnhi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gt2vudvvgxu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2pmtpgadn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gt2krnnedpn.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2jbllhlrv.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2dopujxfj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2hhxrcsar.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gt2dhfxmhcj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gt2pwtwffun.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2cbxsraua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2wjjpfacw.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2tzayngfv.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gt2vuwdfnid.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqieijar.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2tmfuyrki.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2idqxlgmv.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2simddyau.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2fmxxfpyd.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2qoicenif.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gt2pqzzatff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2wyufxdpn.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ofcnuxmx.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2xrtuyvbs.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2twjkkrbs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2pydwbllo.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2weemvxnt.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gt2idsbijxw.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2sjcoxbuv.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2hcikzkbf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2wkravgpr.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ugwwzjun.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mcxybfqd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2ouwhmofv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2hxksgvrt.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2hsrhotpj.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2mrdbheyi.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2pilatvuz.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2yfdpyikj.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnjznplb.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2pzdjykyh.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylmgxwcd.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2sdwmhpph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gt2fkwlqskx.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdmbihbw.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gt2rronyjin.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njizufls.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiuudoax.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gt2xoyfzmfd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gt2ssmakrfk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gt2gikjysrl.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lxbrsmla.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gt2qatyqfrq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2oekjfrkg.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gt2pnskgrcu.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gt2areuydmt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2xaqfxpdw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkkqjpkv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbssoams.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2oyybpprw.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2lmjkxqvx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2jwzvxyin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilyyfyte.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2mzlvbyap.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2uzkqcbfy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2nungkwmr.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzxowgwb.html

JS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2oweyximk.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2fyyraqgt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2scfuqaib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2elghxmri.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gt2outnvhiu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gt2hjbefedq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2weumejiy.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2lscqqija.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xgtqnpko.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gt2nlnujxzc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2tacsvbzi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2ayppbxli.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2gmmrjjip.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2qwdumogb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2qsoanmkt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2jkaxoymm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2pjygmupy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gt2ffewcysk.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gt2viutegqd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gt2eqzsjjwk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2fibvcsvr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2btxfelwz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdmyfjop.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwaiwbyo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2ogkdsvxp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gt2brfkqeyx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2zietstpg.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2qhhofkts.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2bhfzipoh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2vigtlqre.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2oamjusho.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiyumqnh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2vrvumghe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2yiwfbmxs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnhglanl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxyxothi.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gt2hljwkwre.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taaynjfy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2vwmcmijl.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2zxtyiamz.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2qpvnpoxj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2ecykfaxp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgpaxlcd.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gt2sutsakyv.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gt2vfyhtrzb.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gt2xbvehrcy.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gt2oymqpflk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2oysutctl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gt2uipytfgf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lljzbwwo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gt2oswrlqdt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2awpxwwav.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gt2xgtmorll.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gt2uyxipnav.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tanke756.top/Article/details/gt2mxrziglj.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2leslzvxi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frkbxvik.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2zpvnkbzb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2vcnzxkur.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2cipcffxm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gt2zxkouwji.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gt2znpgulzs.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2bhdgknys.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2ctjhwxey.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2pawpzkrz.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2qtqoygwv.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2oaqgzccp.html


<!-- 参考信息 -->