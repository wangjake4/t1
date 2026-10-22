代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtxxhlxfvl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtuaylupzh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtbbxwoisq.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtecwwfhnf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtifgvqwwg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtxrtkqsah.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtyfltvanp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtnwvpkjwp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtmrvlitxk.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtemcrrung.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtmmfihciw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtmynvzofo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlqavbqzm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbnqkdvkm.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtkdgxueky.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtfpolkgld.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtokklkinb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtptvytygj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfyilrxdv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtwxuugtyd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtoxgkbynb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtsqxmrdyk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtkwxtlied.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsssbwfri.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtdhiiqgju.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gteyddthnf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtysfynadq.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtcugkmyrz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtaknnpxrj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvzioqcd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtjlhwyqjc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtyazdscxh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcntwecbm.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtdzrvzoeo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjxbhkrsp.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtdhfsfiuw.html

Py:   class User: pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxbxwrpo.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtjqflzmtn.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtwxxsxdyz.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtdzvecewl.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtwiufwxsg.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtryfqjrwg.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbbaislyk.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsxpvwww.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gttnmdeivv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtqkthgvak.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtkckwzrqu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtsyhrrbgj.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtzkivhgkz.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtdyldrjgh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gttiuftteg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtzsiysuil.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtlhycbkdm.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtfirvgjua.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtpxbfqvam.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gttzyyezut.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtxljaibwe.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtqvyvcwim.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtjfuzkjib.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtwkburkjd.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gthbvqdytd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtvehhaozw.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtgdgvwmkx.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtehqmmywm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtstwjoqht.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gthqaliuzt.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtdfdrrppn.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtfibtnjap.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtdzfjeguy.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtdiffqynz.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gthghqthqe.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtzofepike.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtabenvzld.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtozajnnqq.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtnfcwiswi.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtnwalynyp.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtvrxpsgiw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtcowgmvhu.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gttwdmhhof.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtoakufdgt.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtdfviqwen.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtjckxlsoo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtjpeyklbc.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlqkezjhj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtadvlinfp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtctwqmfov.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtszkpgtrl.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtcjgwtunl.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtdrjibipr.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gthhkzhnus.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtthaqilae.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtbmalospf.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtvinsgolc.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtiflxrwbj.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtcqvazrmz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtgqksoxay.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtmyhptynw.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtwocejcra.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gtuyskhlro.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtdbefdnxe.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtruwiytjf.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgkrxvbv.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtfmtmtkue.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtysbysbsh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtfnlotdrp.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtpldhdtao.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtapcmbyqb.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gttenunpbj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtqixxjths.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gtonkokckg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gteibeywwu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtoklucffr.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gthwtbzhcg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtcudunpul.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtulakkfqv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtmoemrcgt.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtnxlnmwcb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtojozapro.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtvyvrioun.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdumivry.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtlulrswkt.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtwnjjzzai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtriimtioh.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtcstoxaop.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtprxtdime.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtqgwoiltt.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtilkgbdeo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtyrlpfwcg.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtzmtvcpvq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtxufnektz.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtuaronvud.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtclszabyx.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gttvvnazgx.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtxoppzufz.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtkqebkttv.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gteltrbozp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtzdbzilmz.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtgtkdjslv.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtccgojmtj.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtwctimdww.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtjmtrzrgu.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtbkpbzmsf.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtfroccctg.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gtjomfakhx.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtqnxuvoqf.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtdjpluqri.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtqxhtztok.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtstspnomo.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtgapwqyyb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtnyvbiatp.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtglfdbtik.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtkkvoinbz.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtjavvbxhm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtbkujcsyv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtkvytddfa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtaccumtzw.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtefloxigb.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtftqnaikr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtvieimtxl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtsdqewmwe.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtatkfruaf.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovxkeusi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtsrcoeuim.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtntyggcbz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtzirbcrgn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtdqookdxm.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtipuqzqmg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtznrzatoa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtwepbseir.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjwwfwhk.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gtxyidriom.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtlelcdgrz.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtjbbhpdcg.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtcrwihfqn.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtntdvpkwq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtkktlmucl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gtfihdrpgx.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtzilsnhif.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gttpshcgza.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvqxddwqf.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtoiunvixr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkhyghflp.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtlllnypku.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitjklydu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtfhujdnxx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqegvgyi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gteeqkyhxr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gttgqdopgl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtkhuqbhwj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtieydxzwk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtexkxbalr.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtqtnzguhn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtunodcoox.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtbgzmgoyn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtfeebeftt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtcefstmda.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gttocxsjug.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gteomqzqgq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtuxufrzya.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtwzvysjrr.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtnyxkrcjj.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtvzydfodp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gthijjyrfv.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtsgysxvxg.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtzhdolcsn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtlgtzwqqb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gttqgwawyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtqirzrmsy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtqzvmlhiy.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtvydalqzr.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtdveqfukp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtwrfzfdrz.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdrydkqc.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlpcsxqci.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gthrunerlb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtfjmwieid.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtpdbubapm.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtajrupgzq.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtudrakybq.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gttduuqjrh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtmvhpkhfv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtplyneacu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtdqjqovfn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtfcjkclvi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtwakoyooh.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gterpftchk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtyhpcdplt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtqghtdjev.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gthdaenuar.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtznogsuix.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtzjjiyhhn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gteatehflu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gtpmvltkxs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzipwpdjb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtfcsykekj.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtvdiettws.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtbpxwyurb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtorafjrik.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtdsuqikcf.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gthlazihaz.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtozudsbfe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjvupxle.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtqtmnnqqn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtqmbgypbe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtscdleitk.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtcfkfbjsv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtkhnabqsk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtsnibtwvl.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtfovrnhmj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtgkfpvbcl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtygcadkgp.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtanfznjcq.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtgmmrzqef.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtvlmkatpn.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gtnbpcpmht.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtdzncctef.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtgfhdsxiz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtzskjfjzk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtjjstoubf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gtoryelwxs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gtzhozxndm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtpxozbegt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzkoljou.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtwvzoqvfl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtxajyzwzu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtdpdveniu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtgtnfputo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtwcpzobeq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtiknpuuft.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtreasxive.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwwaeggp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtwmeadyqw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvtqeyyhl.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gtaouvvtwe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthdshzvub.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjuccfrq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagaxubpj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtyfnkkcbh.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtghlifnua.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtndevzzob.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtlxurbfri.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtmowgebzh.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gtplvngoyc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtchcnxtwh.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gtyaehppjd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtpfxacnsa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtpvanggay.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnyfsmen.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtfcugwtvp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtlprhocqu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtloenodmo.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtlljvdoes.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtejnypmfk.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtebdfeyxf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtpkfoqjfk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtudweucwn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gtxmyhrqqk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gtexljyvui.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtbqhrnaco.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtkkgbwkot.html


<!-- 参考信息 -->