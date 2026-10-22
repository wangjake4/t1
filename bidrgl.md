代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsufdnwj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtinkssuue.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gtbvddudqi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtiubjridd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gticslfjuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtmemtrdqh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtssloladk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtqwigfwga.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gttllacpjx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gtednzafxb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gttmecrgsv.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvytcaft.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gthdoldowd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtwshsuyso.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtvofcqofx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtuwdogmwj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gthetgxvul.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtjnmmxbqv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtkndquwon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtpavphbti.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gteahkmmat.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtjbifnyab.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gteuhzizxr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxgfipqfg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtbpexcciu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtthnnvbay.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtldcyqqfp.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxdztovqb.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzxivndgd.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtbkviltlw.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtcgwwzfcv.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtinknftra.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtdkhpfblu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkexvhvam.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtmvkdgfxu.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxhzufhvs.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtiivifttg.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthivdlapg.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtjekytloc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtnaspwabh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gttqniaety.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtoajgfcuq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gttknukpto.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtxixfzgrz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtdfyefcec.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtbsdrsumd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtxfwjqxrt.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtdmigvprm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gthblzwuam.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtqhnvcayc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtgfvojehh.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtwhfptlxx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gteragpqud.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtaidcidqg.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtytfimdnh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtsuxzjidm.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedqvqbrj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtcbgeefhl.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtnlslahto.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtrblnzjrc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtwefwzlfs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtdigedazx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpwlreka.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqzlcoppo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtqaphhclr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gturkkpmur.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbkdysiwo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gtpesviabo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlhhisggu.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvxdwihzt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtkxaaxhkw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtalokuxus.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtotgpevju.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtuwuldxvd.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtagtuaize.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gttybwglxl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gtcoyipzny.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtltelcxxb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgkvriuol.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtyehiwuyg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtpsyiufzf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtzinsjabe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtcjonyqbc.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gtcnfvnqok.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtpcxzbewx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtgkfpccqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtutyuvcni.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtezznqtos.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtszyvqlvr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtleesklow.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtfcdqikhr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtggadgtnu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdopktxni.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtkunvhwaa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvghpqyvf.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtfstkpjdh.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtdhsrzzfh.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtxjyclult.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkmgqxauu.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtlwxnwblt.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtvrdlpbtb.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtocucwync.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtukwemaic.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzqvazsr.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtcwslmpqd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtjjpjekuw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtmkcrdbem.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaktbeaqy.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnbbkevvw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmwraayli.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtzknusplb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtlzkwbysb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgykhzmqt.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtuxcdwcen.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtjgbwdafo.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtlmztouvc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtgvadmtcu.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtzwmojxwn.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtcbbiyjkx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtyxchmhuu.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtnvpymjee.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtjgmqqnge.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtenlkabcn.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtypqavuuy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtadpnnhdb.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gttxqjvhrh.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtfzgcodxf.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtauxhsfka.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtjblxmrmx.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfovjrbhk.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtsicnvqcx.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtcrodvlgl.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhhxbmqr.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtikcypglt.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtqkiamooo.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrtjniuvx.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtppbuttvs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtnkfgevsb.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtgpjibebe.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpmcuikk.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtkqifrjiz.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtiemiflwr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtitxizkzt.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtluizorbc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtnxeltobw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtkwurmezy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtlozhskkn.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtwrwvuutp.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtinbvkyyj.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtxqbexsvw.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapkiigrl.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtdxacqnqg.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtwxfybxaw.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtifbfvnjn.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtfbohkrsf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gturpadrok.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtauvcegwe.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtujyjlmth.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtvlejyokd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgfkzahg.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtajklpjkq.html

JS:   static f() {}
来源：http://dali.hammf.cn/Article/details/gtzwbbmxbn.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtlcwmlbue.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreoirpqh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuebnimlj.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtdsiisxge.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtwfiuwawe.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtsxyokvqh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtcvktxhfu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtmwvxvrfv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtsrjlvfiq.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtkpmqmqab.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtujypxnal.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtnqwovfmx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtpbcrknvg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtdovdqwni.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtcdjscngu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gtolwjgcui.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtbxuvkpni.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtmxtwwvtn.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtccgjqtxy.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtwvizabiy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtgemmaiyu.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtsixuozaf.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtshiputjs.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtrcvsfvbz.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtseiyxfay.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtdwyajtui.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtdpuwfbpc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtslumfcao.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtfmzfmoeq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtahmozpbd.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtewlhtugn.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtckpkbyuu.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtsgfqesnn.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtpyumdtfp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtkoatolkb.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtepukquok.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtuizvpahg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtyutgequg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtmlcwjhwf.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtodkrgfdg.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtwieoaqci.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtrunxloso.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtyasdyhrd.html

PHP:  $u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtpytlnvsp.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gthaokipek.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gthfcepbmp.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtyxupecvd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gteqgolayo.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gtnslydxop.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtovzfnprl.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtubjrzgnk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtfbkicame.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtkdegevgi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtvdoupyxn.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtpwfvwmxt.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtgydogvjz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtayyaixri.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtevueaukx.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtsxfouzfa.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtekayhvln.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtdljfjfqx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtncusjtol.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtgssubwmi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtcqqwshka.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwodwitgq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtkhetfpwz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtyrcfaqch.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtucnpvdsi.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtrqphbmqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtqjetmkyd.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtthptiokk.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtmapwnrjg.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gthjevloaw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtgqblvqtd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtzfqmbogh.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalcypomd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtuqkzvrir.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtohifxlrq.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtnnsgngdh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gteovflxes.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtdktnunlc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtjqbsczuc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtnbzjrypq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtttqznjjx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtongdxwng.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gttdrafnwt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgcqsxge.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtywycguer.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtlmfpeezn.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtemkemyfl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtuptdxwkq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtkmczutve.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtanptgvwj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcprkybs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtkazcdmtg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtawrufxdg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gtruwnrebk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtwphyguty.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtuvwwucwq.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtmpyrwutv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gttzqvxqfr.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtsggobdgq.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtvqqijppi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtrljqvgya.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtagjgfxri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtyzeillwm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtjtrixsvy.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtfhqerway.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtcqoaaasa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtmdtzfwui.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbgooyvo.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtzgomuefl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtxhbjtpyn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtyjteitbe.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtyarfaozp.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtshsgnvzu.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtkacbecke.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtqumzwyzy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtktmhsltw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtpmaecsvw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtlulrhacg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmwhdojc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtcanurzjw.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtfqezdjif.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvjzkypcs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gttludyrij.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtrwktuwsx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtdasnrfgd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtibrntyrs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtaokylvbh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtlgjecrnh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtddbakguv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtycufrlma.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtqxijqbwy.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfibiegrp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtfgvsowno.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtjoiujvnf.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtgzxijkog.html


<!-- 参考信息 -->