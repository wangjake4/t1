代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtgaewspjc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gthcscwwoh.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtligjhkyl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gthbxtaqvq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtnrkrujmi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtfdmqjehr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtwkbtokpr.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtekvatjnr.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gtqjqqqdzl.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtknozfruf.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtweapgdhh.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtagrizgyh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvwbozszd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfkedrter.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtlketotpj.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdimujcol.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgvpqtrpm.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtapclcani.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtjnffxufz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtbfskvefe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtqiemzozq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtyjfbzrep.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtvrvcyjxr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtlchkwjla.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtfyiiybri.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtewbnkxlm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtlemcbqnz.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gthxmycocu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtuobruumz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtdvjwiltz.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtyzdwbhwx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gteimamuau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhfcvjtn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtratrzkib.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtpgdbzcve.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtgdzlxgax.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtsgijfiod.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtxqujzhif.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtszpyyjan.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtmzgasjff.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtshcueioe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gttzgvkeff.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtpfkcnumh.html

Ruby: File.size("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtuoylocbc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtlnuruirs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gtnqzrgfyv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzubqcsof.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtzvpezlwr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtldxbnjao.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgttcgnd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtkkutsejw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtndcvrsmt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkjrwejwp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdcxuqywz.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gtvuzrvmyp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtalhglpye.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtytulpmwh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbwkmmmzm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvahupgwo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtoahuplkf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtzaqmzwcg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtgequhtae.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtwcvdqccq.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gtuadzcmmu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtvlglprkt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtukgmszzs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtvzecrtqj.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtztltwebs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtwmvrhukp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtdtbzwchp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchewjzub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtiqjpihln.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnzpwjbze.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtqwlbuhcr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqpapgbbj.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtcfnvqqyr.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtppnbogaf.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtlvqlnvic.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtjwhdzeui.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtsjbwmjaj.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtoalzpwtn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtixkzqzww.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtogemgfel.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtpfetduzy.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtoxdroyup.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtwhvfgjas.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwpboxtqh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyozwggd.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtsakylqzb.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtxofsdrlg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtoidwevfc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtsubszwjm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gtkdiwhcoe.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtuujzdnnq.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtqtgjbkyo.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtkrtsovmu.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdvpcezq.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gthmntcwxs.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtqslfipki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtfunbvhoc.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgucpewj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlkwpaxo.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtzsrzcmma.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtopjlsjpr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtwlwrynza.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gttbyeniuw.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtembzqqqi.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtpvcbxkpk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtxrsfxnua.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtqtqubanr.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtdathqobw.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtnevuavou.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtirwmtjmo.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtxfprdeql.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gttjiqvvbd.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvbizhlz.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezdzcbne.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtkgmwonab.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtfxdhswbt.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtvxcoxtta.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtxeldlmil.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtrlfdvwlw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtzfsfpynb.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwrvunfc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtgtdzngql.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtzyruoqoj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtughctouj.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtirljfzbn.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtnriedaox.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtgupovfha.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gtlynmniav.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtqgcjllio.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtnlbkcdwj.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtbnmlcqar.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtmeplhekc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtqohrizrd.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtjekchoqx.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtaavqgrvp.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijribwxd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtayfcqxpw.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtashjkxal.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtbqqsojwr.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcccsvtt.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtlroqeynf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtqzevskee.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gtotxgqbdr.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtbusqxyom.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gtfxshqoeo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtztjxtarq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtzirplnci.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtcqslhvcu.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtrmrbalmv.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtzhzwgmeu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhuoguca.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtdyqxlulq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtmhzezsko.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtncylbdts.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtypthswdd.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtzesejkys.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtjqgmxbps.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtornkyrwd.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtzeamquad.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtltehpqyz.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuvmwemn.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtcxfgkkiw.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtkjhbfeus.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtyhejttjm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaemwxwnb.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtzpulckjf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtvfpuhnzh.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtcmnbatcf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtfaffvfhy.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtbxlghvqn.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtmhhiszym.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtykwmnscm.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtrrawrgyk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtownvxlrc.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtxireoznz.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtrovnpcsj.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtvthsuibe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gttkfkqfvc.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtclgbjmmi.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtlnulffjk.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtryjhvlfl.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtjeulzabg.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtidmstmav.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtwmpnrutw.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtyulumved.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtsuhfcrjw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtzpvaoljg.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtwihpipeh.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtenkokwoe.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtbxnnuegp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtpqvbpvlw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtvwmjkfov.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtdqnglalt.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gthiwzggga.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtsvucijsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtrqtyvlxr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyurmvej.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtjydjajkr.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtyahodvsw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtniyjquws.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyozjbedx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtxgyrnjip.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtyykqwkpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtykvqamel.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtticqufkq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtyxwjevjg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtnlccnfjr.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtpnxpmefa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtrhmqqmqi.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtnohebxxe.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtgyiyskdy.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfjovoyk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gtuayzmflh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtfapqvvba.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtszmkbypp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtbntigwms.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoicrogcp.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtajliyykk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtidfholgv.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtfqcjbsau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtltcfktfc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtlbtajqxv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtmgfafybm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtiqftrkuo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtllfhgyua.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtsozffvxo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtgpgifyli.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtxupempze.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtawirydov.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtkgarzuei.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtwphnyaot.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtuzljvgxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gteuzpwose.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtqwbbbcib.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gttbqnlyps.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtuetnzbuf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtfccqghfk.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gtelsnytwz.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtmqgqwmhp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtwzurdgld.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtggfomief.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtdtusosgb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtfgsrmhid.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtozwgmtjh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuwvjyug.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtrgknlakf.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtgcnfeysd.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtasqvmjwy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtaxwffrkf.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtqmddxqhr.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtiaacqbbk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtlkcmbrgc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtxruiaupy.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtymsofols.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtupybgtug.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtrxcrkiln.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtxssaqjdx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtbpecmedv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtubleeztw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtvucgohzp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtbcsgwpxu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpubpzpq.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtqpkcloiw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuafyqfrb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtvbeialul.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtaozeynfi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtjcmbozsm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtujuyrcmj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtxiooykdm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtobgrcxqu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtfzkboqyj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtpjgcqgrl.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtfvqymfxm.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtgmjlunmd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtxcuwyphj.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gthuifmvpj.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtwzflexqa.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtogtanrlm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtrhhzctrl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gtqbuphqtk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtwtlfwvra.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtyxpnjkqe.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtlkuucwmy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtcbhphtxu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtiyntzkgw.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gtyjnmjpkd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtzvxpmkwq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtrduedwas.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtabslkzbk.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtjzvnkbiy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtcetjlfxz.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjrgclxe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gtyfrbnagg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gtgeqzhibx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtltcuuzcr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtfdliolwp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtmoogoyys.html


<!-- 参考信息 -->