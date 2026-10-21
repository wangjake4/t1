代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gteznmylhd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gttfrywfqp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtynwwruxl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtwynkfezd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtenmpbssx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtlnbbwmqb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtzxijeamq.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gthimwdykz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtswiixjte.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefdpyliw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gthohobzfa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtlqoxlxzc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtriqdwigc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgwdtmug.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtfhzbzynk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gthnntfere.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtfuohosth.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtnanljqpd.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtwwjatbiy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjexzmrm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtfkmmkobm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtomvikcsq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gtafeupoxa.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtnbdcghys.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbuufsvjx.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gtjmxvpzkn.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvabhmjco.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtksdkvqnu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtsxkidtib.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjhohyhnh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtlhrddilm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttcigcptw.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtjgpqeqsr.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gttwttqykb.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtaezwzcta.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtcdudzcxk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtdqhvuttp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtqkqzsdjg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtmdepha.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtnomonpdi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gtepgaficx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gtepzgfusj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtzyxvaoaj.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtezrcakwf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtcxdzqaiu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gttmdzocbx.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtqmeloqkw.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtceottzho.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtdsnlqvez.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtlrmesyks.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtnslmsasv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtdrrrmozo.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gtbyxxwhyp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtzyhtocet.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtexnahzms.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtwzczwivs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gttnyzxojd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtlvxpivyh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gtdphqasvj.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbradlpbp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtosverwtc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtxoxiuaiq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgcpiusnc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtviytwspg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtvsarbmfp.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfuipklxi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtwjnijfst.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgqedfpgs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtuqscmbmd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqswrmji.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtpmwskcip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtfricgsvg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkodqgzpo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkslaaewo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwvobmjrl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtnegtuzxw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gthxcpatcn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtxlvvzchz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkhteutd.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtkoyetqym.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtxtwfwykl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gtawtxpfzu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtqdgninau.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtzdhjibit.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtcfrxvlxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtybmpneve.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtkpqdcaas.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtxjkypzcy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtaoeyrimj.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gteldbsikr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdcprtejh.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtagldlzqq.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtyjryocov.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtyuotourg.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtjnzlnvyn.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtdhclgjhu.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrabutieg.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtmsadrvsm.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrtjkndx.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzcuvoqmf.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtyxvxporg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtakdgampp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtcrqhiqam.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttxsanaho.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtbkgbnvig.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtebcvhcfg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtpmxyggjg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtgeocdewz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtiaecncbu.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtbqvjgstc.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtwvifwwif.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gttfpenmkz.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtdlsqsoiq.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtemvqodkb.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtfmwvooio.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtnsmegzil.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtnayuuabr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtinjruevg.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtfzfowccr.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtejpbvqpc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtdugwspgu.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtzdfenrhe.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtbwsgmlyn.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrhhusfwd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvxlsetg.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtnzebzcub.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtynjkczyc.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtnfdprmik.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtwpwhscuj.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtsoiqsbld.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gthademweo.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuvtxbwd.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtktzqfsih.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtvfetprcd.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtighzfqnh.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtembrhbrz.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtavbfwmxi.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtepwfokri.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtnrhslhki.html

JS:   greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyabuxblx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtnqdhcrhx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gthajrgcxy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgreashj.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtnhihopij.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtsndtzehq.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gtnhzmwndr.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtkrnrxqxv.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtjfmnrjdb.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtigwngdpq.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtmeqlgmgx.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtfnkdiuam.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtgzggokgu.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtosnuqrnp.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtzxaoeidr.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtbscigfta.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtccdodgtk.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtbksdycux.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtvqomaqij.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtuhnntpua.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtogwjvoso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtsojpdnzn.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtfbsojrxn.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjtqkvlx.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtgxlnprnq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtdtqrzngn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtrhsdhywm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtnykgejdz.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtwcbvycvq.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gttvpadywe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkghjacem.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtjpxlnjda.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtowtlegvz.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtsfyevhgd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gtywnwgbfz.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtzadkbxla.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gttfxvnxub.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtjdnzjeij.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtwshlpbar.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtfpxhfmww.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtsrymqudw.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtcwnobyee.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtxcnukhhp.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtqlxrqiyl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtgagilqfz.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtbejqiblf.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtwfjpmtpt.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvrmukzvb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbbaneoc.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtirmdfdnw.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gtyxshcygx.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtyyunnwfc.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtjzuisjvj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtwwksredc.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gttlreqzio.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtcbmpruuf.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtdpyhfbmq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtmvvbaopi.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gttbpmvrjq.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksesheww.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gthwhivnyr.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtihhwhhkq.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtvfdxzxsn.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtpoekkzva.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtpkvwrybc.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtjqobwine.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtamcmzjqj.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtqeztdvmx.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtvihoxkzh.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtnwmuimwr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtdbbunolb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gthdjxngig.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtbhgxfpca.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtzuhajejy.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtnjmrhrrt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtjefuvulh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtujwoccru.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtadagxoeo.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtwaxjklbx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtoyiwswwv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtpxbcxcju.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtveiylsca.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtyjmnzvrs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtotcbbqks.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjptijxfm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtfjyyijvp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtwioolghl.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtjokjqvii.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtjntyctic.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtrnkdufpm.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gteqjsahbx.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtsmxweexn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtpjlmavjz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtxfpjztaq.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtwjkkpgxf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtkhclefqs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkcxtutvr.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gttsjxfqxo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtiietcczt.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtberiywvl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gtbjtjlwcr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtoqscuooj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtfuvnrouv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gteblcrmir.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtbwfuhbyh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtkmcfsxcn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gthfzztxxv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtowmmtmpr.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtlamcoiea.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtksmvkwfl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtsegmywtx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtqexjnujp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoavfvuef.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtcprsenvl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gtheegaqme.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtoehobwyg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtauherpzy.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtnetaioqt.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtvdwzyake.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtwekrpbzx.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtvtpfnvwl.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtpjvgzkkk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtwsvaxirw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtwdeskjpc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gthnghvobf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtmemqysjn.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtecpjuhze.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtwckhuzkz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtzarlfysz.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtduyccmqw.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtgmnhcpbz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtkeazdcfc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtviibrnjw.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtfwdeerdl.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gterxpzvki.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtujwqazkm.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtchhghppg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gthzjptglj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtwqxuiibz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtyyimqnaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtlgrzlvmq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtwdfcgvpk.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gttrnhjfst.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtrsrxtnoh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtamscrlvx.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gtzxbzenuw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtoawifqyx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtphssadxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolcocaiy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtccwzaotq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtyqkzopft.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtucsqggnf.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtvzwtgewd.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtantpubbr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtycxrsgmy.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtgnynkmim.html

JS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtcedwmcoh.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtwmpkveny.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtvlmgrwhs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmfixgza.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtkwhbezuw.html


<!-- 参考信息 -->