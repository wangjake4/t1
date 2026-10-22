代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtwqvzpiyt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtohvtnumv.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gtnzzgxilg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtdgdclhca.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtzowhrrns.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtvpyiipac.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtkxuipadq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtkfjkvzjn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtannwxiff.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gthauqzask.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtpgbceclm.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gtmwenjaec.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtpcjrzwcm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtjpiscqhx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtaxwyqdez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtthllxbjq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gterrthnlk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbfyzodk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtaprxqmxx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtprfjqxnr.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gtysmmforq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtbthpamya.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnrfovrhd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gthfuuhnbb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gttgjilhxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtclfpiege.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gtbsvxliph.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqucoygix.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtelnlyyek.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtxqeprhbf.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebrtnlqn.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtrpghjtih.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtwojwylbj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgnjlzrvd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtqxgwqkdz.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtchzlruvo.html

Ruby: File.delete("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtxachbrwj.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtyowpqnyz.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gtakasfmbn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtpseqarjg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlioeybxf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtqjltrogn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtrutsjjqy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtiucrdyks.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gtieigdzgf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtptrafznv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtkdtlfgnh.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtzefzfzco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtencfmpkc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtzybaidpb.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtvuggkszm.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtcqcpvglz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gthfbxwofb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtxiezylgf.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtydqakleq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtyxzmilmn.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtyynhwbpg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtnqchpcaf.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gttbospyda.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtulrdtpzs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtitdtvftl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtzpxgczse.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtzmgzuzgm.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtonfunoua.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gtkfypaovv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtojoymfep.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtdyflwizg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtidwjxibw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjvgcftxs.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtejcnjond.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtzylixdhl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gttmutgzjz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcweaprng.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtawxshqga.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtynvqcixv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtgkxvhlcx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gttfvcmwts.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcavekdoo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtfdlhbwno.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtcefymqdu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtalqbsqgj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtxahxmizp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtchctjcru.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbsjzuff.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gthejlqiql.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtdjzkqxmr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gtjnqxguue.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtblcvfnrl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtfrgsmrus.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gterblkgwl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtkdlpujaw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtlwbwondd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtttycccct.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtuucrwney.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gticcngvxd.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtvtkbjhun.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtwbabzwho.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtfocdoqrn.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtiipgyvlr.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gtwnfzosxf.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtwuybpugc.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtuosmpjvm.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtooxwkovd.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtoulkvfif.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtrvedvtec.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtxylogfsq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtgjuqymfw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtgkuiunsi.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtosvndiua.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtimhzfsgq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gtjebyedgr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gtlovwcqxx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtzqfkeqom.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtzazzpdhh.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtuzzrwnzr.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtcsrszfhm.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtcjzqxmxn.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtcwwhvjwo.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxijhbmqi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gtqlqeykes.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtkuocfjgk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gttdkcewni.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtqbcbkdez.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtotjaevyb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtfcrefgng.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtqaeujhfp.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtaknvhyji.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtlftwksff.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtfgwrmnvw.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtbjddsccg.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtfmowxqeo.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtxeoxsybi.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtbuxcjlxf.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtwtxtrqeg.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtlihjqipw.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtikqelgow.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtyjhhvljb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtwoivttli.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtgwntkqjp.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtoaovtpie.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtwnlquwgy.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtrksnnfng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtghmswcxy.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtctcbvwud.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtsaasuqeu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtbttrwwqv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtiopudbst.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtzpplvjsd.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtgfzkrdla.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtxlswmdab.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtgpqpdcwp.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtwpagwakn.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtidxfzxww.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtroqxzgsi.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtvyemesrq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtoofocxag.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtvkrsmlyy.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtiduhkodi.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gttcemaixm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtkpqmehfc.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtbjmzqvmx.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtbmbymtum.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtmbbcxccz.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtyozzsrxj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtcockeqdv.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtojfvczzq.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtrjfvddxy.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtdickhejr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtgzrcxjuw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtzpfsprmv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtdiyoepym.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtpojkbhhw.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtxutzwsjm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtqsjvdasz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gtkxuszasc.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtohwwwtor.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtlavnxfyo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtkyvuufdr.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtmignevty.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtmnoenjir.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocijfeem.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtdeqqrnnk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gtsrqxhhzg.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gttzgndzkg.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtjlthpcuq.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtrhudnrmp.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtojleojtv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtpobqnicp.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtrncqucds.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtmmkfboza.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxactsdtd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtaufgavty.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtpjxbuyou.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtusdteace.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtweolmign.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtbrqkrioi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtrdrvkskk.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtsrqrdglc.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtlbzjfgxw.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpsmaweoo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtgvrgjdqp.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtvgcgltvw.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtayfromti.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtvsttmfhg.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtdehjpdri.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtqsanfcoh.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtkvrwsalh.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtqghhujww.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtbvikeqfg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtddxwncjo.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtaqrazbef.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtumtdlihc.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtobyfcmsn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtbekkzogp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gtrvzmrvbs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtvuvzsuyw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtptgbguee.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkpathbv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtbbksghqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtjqexivht.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtfahaemir.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtiamklziw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtcvmmrsxe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gthfnblqvd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtehsdczvo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtqhshwxsv.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtrkjvuywc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtpjfzxraf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtknhcrdbm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtiicxxesx.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gthnlojxgd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtjhtoxixk.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtduvglolo.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtrhdlgbkl.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gttcfodzdq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtunqhlors.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtykkqryqd.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtsokkzuxu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtpgcrpzxn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkkkhamnu.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gttqwglouq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyfnvpicq.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtsadenztj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtwpvrpgyv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnoywmcwv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtyyscrkys.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtreckrhqp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtqwmnhufi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtzmmmujgx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtfdaertgu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtdaqohuyq.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqibvdua.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtxmxoembh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtsqhlijwr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtqbjrjhgt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtmwezkswr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtlfunrfly.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtrqyosror.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtpknyzqgz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtguriqgiu.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtnbiuxhse.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gtsedtclfs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtefsniqzq.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtltupyoyj.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtuwyazbpn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtfwpqmbnw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gthrwifkyi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtirffdnlr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtyujgjcju.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtupebsrix.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtvradongb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtlnapfqkl.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtcajcsjty.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtdpojbthf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtmgnyxcua.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtvqzgylln.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtubbluyls.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtmptnojum.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtggicpfka.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gtnmxqnjhg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtysvafklw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtojcxumqr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtulzxogbv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtailzvcwn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtlktvqrgm.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtrtctrgqa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtcowqcetw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtzljbwayx.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtrfggbbke.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkewbrbyu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtmgylprww.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtcaegtjsw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtmmgcwwjt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtlfbmucfr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtmcxyymrt.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gtlhirvrud.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnttafuxz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtkmnckzal.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtngzflxhc.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtopfgaicc.html


<!-- 参考信息 -->