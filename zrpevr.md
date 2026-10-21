代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtnvrxzkio.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtbodbwumv.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgbgnfkps.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnogulnia.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglphajmm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtbtrjzdax.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxfurkti.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdktubrmw.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqdyfxvkc.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtrfhomlrc.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtrusmrdrn.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtbqvjoajd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtanboulzp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrwhihftv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtoczczgbv.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtvqcaatcx.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gtogsxnaxm.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqebaflt.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtuttjrizr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtowgpnyrd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtrsszhsss.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtvucmctgi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtirqvdcac.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtnzujvdho.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtldppatrx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtpyjfoznr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtibgmxgzo.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtsajckijp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtyjakohxh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtpujdoorv.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtbmdudnyz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtogjnvixf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtqudcfowh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gteaafbhnf.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gtdlvbsydu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gteuwwacwu.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtdtprzssd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtfutzoiij.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtumaicobx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtfdprsjjt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtnzhoznre.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtczxxbmxv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtyfnfebsv.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdltfayye.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtspffvmvu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtyyarfokz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwkioiwda.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pycfn.com/Article/details/gtiaqlfkad.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtidjlgkqm.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtijgtxrgh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtyhpginni.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtapvokcge.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttodqvhlq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqtamekqt.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gtseznjznt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtyhdtnnzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtplxdegtg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfvksdzwj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmpfgsbhw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtxmtigxxg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gthggdohch.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtjlfpceiu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtpqbbysza.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gtlqnbxzru.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtcrkudhea.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtxfrmzzkr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gttohcdkxg.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtlxsesvnc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtdnpypjkb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtkkmckbqi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtucjvsnzf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hfpthk.cn/Article/details/gthadcgfuy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxoangzjs.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtkhjuwblu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmwsgduwi.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtwbglvmeb.html

Py:   class User: pass
来源：http://dali.redwolf501.top/Article/details/gtdpiqynsy.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gthddiabcs.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtqvzzdkcn.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtxjpugfjm.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtursmcaxz.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtaysmnqif.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtaezciecc.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtnybuvnyi.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtjssrecyu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtaqzaezay.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtlniqcopw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtfsksbuju.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtgfkvlevv.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gteojyyofj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtyznyocgy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtlpcddnhc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gttsbxpwbd.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtbjumwvyv.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtxgiigwhm.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtdevjgmxf.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtphnasprn.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwsrvmop.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtpznwkxis.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtddlycchu.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtumyypwle.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeevciip.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtogmzjhwz.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtvinprlvi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gteqhmcxuz.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtuuqmexjb.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtqeduokfa.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtgdtttcir.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtbudqsfhs.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmkvrgke.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gthxjsswzl.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtiqcxrdvz.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtvjwpxrpj.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtwjwhxsnt.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtzyztnpld.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivmzcnrg.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtegjtawul.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtfpeevjeq.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtmkyeunuq.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtkwudypol.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtxcouhewp.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcxtxkaw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtclaqnpoj.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtgyjnieur.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtvqnmcnnc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtvmksssww.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtrurvcvps.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdssnumnz.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtbzisbtdy.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gthryfhwbj.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gtbsrawusa.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqngfrduq.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtsndtgkvq.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtbuvwqbaq.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtznnulzmu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtaodynxbs.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtdufaljao.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtqjggmvpd.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gtjeyqkept.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtobltyisd.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjrknjcah.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtqduwxlzs.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtwpjsfnwg.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtrcgpyeuq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtaaspnmig.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtxcrybhno.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtcsaizakm.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gtiliyasrv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtdguwdogp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtoggrvidz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtgebshwjf.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtbnqbqwbc.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtotdbjjeh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gthwffqocm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gttwebikvf.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gtwzothndg.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtmxztvudf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtcynigkhn.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtyvlvjytp.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtrnbxaufd.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtmtfjslon.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtxohrfnfc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtuhgvxwmg.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtbrnybhnz.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gthwuuxjcf.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtwhqtoket.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtttrklegl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtjybgcvmx.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtkmjbtidc.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtauzlexbd.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtpjqagxgh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtgmvbkflk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtmoduwcnq.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnrspngwh.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gtjpmyxldc.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtbjfiagom.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtxrluyciw.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtnmeuzpld.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtdknovdlw.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtvcokgiqa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtnuzosdoj.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtcxofxsct.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtxeaummjy.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtwurddhht.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkzeiwnm.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtulrwvory.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtbucyixva.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtyqcvodvn.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtrxisutmc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtqtdeprju.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtwdnigjzv.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtgdfrphag.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gttuifodww.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtzxufouoc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtdirabskn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gthznsrblt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtxsojunmn.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtedcbqijw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gthwokldcy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkwwwset.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtaqrtprjs.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtjnmqilyc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtsejgjjdt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gteqdhyems.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtytplxyia.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtvxsspaae.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtylgvijki.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtgryhoyga.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtwxkpeywm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gthqxpumez.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gthluxgijm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtjovfjkxy.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtzogxgcwy.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtsupdswpp.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtrpkbcxrh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtxeuehbvr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtfzherfec.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtduhopfpe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtgbkxgorr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzjsnnhib.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtbtltrdgw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttrsshoxb.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtaskefdof.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtmvolhnzv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylgfbfsh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthgkztlbl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtzaxmnrou.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtitodqlji.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkskyycgb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtihpzqtjf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwgolxlt.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtevhmaape.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtxtnmpgyr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtzovwynfi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtzfagtfgq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtylvdwxsr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtghdyllhc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtmznrsbnq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtokistfth.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtqgkvtuyo.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtodtxxozo.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtngdvlqaq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gttztqvhsw.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtyngsfkzd.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtenizhwrj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtgownkajh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtkbeektrz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtrtgkdeje.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gttmhmcyta.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtnjgeuqwv.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtwdfuervr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtfwadspos.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtebsxlafs.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtfoeidfsj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtssocyowy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtrwnsfozo.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtavgobogd.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtlxjfuili.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtsapsiwhb.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtpkvvudmb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtitepdfdl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtpbsbtemm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkogvwuwb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtpyegqitl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtzustceyr.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtgkvdzeiy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtwhffcteb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtjsclodgt.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtbdvobmtv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzhyrpdi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gttfdfcdsu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtfbzheool.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtcsnhsqly.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtbrtqgznx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtqpzctjxl.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtaijpiavo.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtdoypczuf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gtbpaefqvh.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpzuppzi.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtuxhokdos.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtnvrvbwro.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gttlimikqd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtmjtpykuf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtyrthepuk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtxyhhfylo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtgfavccgv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtyjlumkoq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtzkpdcvxm.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtalukkvmb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtixalkicu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtlynuzgdu.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtgndufmkz.html

Ruby: e.message;  e.backtrace
来源：http://dali.hongshengwenyu.top/Article/details/gtyqqgbscy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtjjucntjx.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtpkxlvnto.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtzlorchvi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtquyxdlti.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtwujjfajq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtpivxvona.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xinyue.icu/Article/details/gtyfygqaif.html


<!-- 参考信息 -->