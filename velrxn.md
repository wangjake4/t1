代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtqxaofxjk.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtlucpxgtq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtygwigpgl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtdzfkvzyy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtaigrfsjn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthvamuxao.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtrxavybgn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrlnhxzfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtmgccfezg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtjzucdjjj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtliebaxlj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtjvtwkemp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gtohxxwgxx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqeulaami.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtxuueazgq.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gtcoivyvsf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtzpsckxgm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtygmvxyqr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiafqpvch.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtanalhgax.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvukxseeg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtgugpiyhn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtcpgrrzyk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtclhtkbak.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtggdpxvje.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gtvwmejeow.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbrhrzlkf.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtowzegdpg.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtgugddasc.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtvlsbyvoy.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtwdqliulk.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtlzprzzpf.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gthcqvpssf.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtjfvibdgp.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtgjczhmgt.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtfkxmqdig.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtaazorpnb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtavkfatdb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtyieyjlkc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoziqmha.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtrptfzzvd.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtbuwmbvzv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gtabsuzwhy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gtihjwqlgy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtykloxnhv.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gtysjyjynx.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqrjemzr.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtboftafxn.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtifiuntqe.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtflfbssnt.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtkuzhytas.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtedeaufir.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtkireuxwr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtaffbrwwp.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gtxoqjrtiw.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtfumwwryr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtflowouvd.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtttvavtad.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtkwsdrdrl.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtufibsnna.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtuecmkysl.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtjjjehtbr.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtbzuebgak.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gtzyyuurka.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtqdarnwez.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtotnfefns.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtthrrkgdh.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtlmdmugbi.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtjndaxxsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtlwvutnjs.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtkqyixxun.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtnvjqctkj.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtozkogsvn.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtadtajsas.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtfglgrqmp.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtkzmibrtm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtgwsrivbh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtnvmkoccn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gtaadifxxe.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtecgmzflo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtlcmiopzz.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtlzfpqjkf.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtzhmtovvg.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtluhrfcyt.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkkqcavo.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtfjfdcrps.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtewenrden.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtdbbzyenp.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtufxsmvbp.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtmbmxzvpq.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtlmbillow.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gtdtmjpqrl.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtfsmroboy.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtwvgxozei.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfxqbvgu.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtcdyplqtm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gttqftqcnd.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtackmyvem.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceslzkxv.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtmoadxjoy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtdaluusyy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gttfshgpde.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtjuuibofm.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtqsdzdqzf.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gthovztqkd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtqbjfobbe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtpttpmrur.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtprolzjdh.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gttqmghstj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtdhaixhsh.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtnbvbthdg.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtbocngwlk.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtnahayaik.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtbsiweijq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gthssxfxsf.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtvxotkmvg.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtrtotbuae.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtetcqthzq.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtpvbgzheh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtsfauzleb.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtaijyteud.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdjcaqfbw.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtftpdnfuk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtgdfcktzp.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gttrkmxwfa.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gttywjhebe.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxutcxnq.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtqivqoenx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtdwzcmzip.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtpqonzmfx.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtksftzifv.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtojmhsasa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtslltpfno.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtmrugzogs.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtbpxdcqff.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtreqabzii.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtiptcopeq.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtaxhcfpuf.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtavbeqouv.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gthohkatvs.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtijqzveaj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtmlngtjfa.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gtrgkmaxsm.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtqgvhgwmk.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtijowrqph.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtodimioud.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtxclhwnag.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrqlczra.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtcuruncyy.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gthwgqrjuy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtciwfawot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtnjlutbbm.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gtktvsgwyk.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gtfnrwbsmk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gthkgqkisb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gttwvbpcfo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtplmagbqn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtbzdacyxl.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gtccricymg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtlvvbarzi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtkpzmbysx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtznrxmvzd.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtdwdfmgco.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtgekmtjsk.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtufjhnfie.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtxsuaozoc.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtttwvdrpd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gthjffewfu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gttjbqhkej.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtnzbxaamn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtcaaijyfk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdjofjqda.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtdyjpmhna.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcoabgzwu.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtvrsvdwip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtpsolfqkh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtsaewxawa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtumwfljuc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtwkvjjlzp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtzvmgjzdz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtvjmbmasu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtubtqyrtq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtatgtmtoi.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtweodiwnf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtotetwkad.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtziezjazg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqrlahmhz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtaxzdjjyh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtjfqqwuce.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsslaszxu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtrabwtniw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtghvdwnej.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtvgoffvpz.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gtmzstprtl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtxgsefbka.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gthxdmjvon.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtnevbhexq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtamjsmqdq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtshgjsnyb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gthvpxhwef.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtbdvuvcwp.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtzgmuqgwc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtamwopmyv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtatwjxusk.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtuutroojv.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtukiczdqo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtkzwfmqek.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtttqtxyho.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtsxfgpwqt.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtvpmwmtbl.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtobapgwml.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gttvxoobbv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtqzqjywtb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjhbkaxdy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtgkewoeux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gttppbcogo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtgfswrnzd.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtkrnscqqk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtqcqdhadh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtmyybssef.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtrlmzvubs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtkloohszm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtywwsjptt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtzeylxycb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtodncgjue.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtyhkffehr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gtsnxxlysy.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gthefehcyy.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtybppzuke.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtxuzhacth.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtnifajqyi.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuikxehq.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtqnwwozrw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtmxlqfcbc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtlrmsmiao.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtwasyvnhq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gthgitcfgz.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzupetxue.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtclljdsab.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gthqweobma.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gtvjxsgucm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtdktwchhj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtjcotpjru.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtoxfdwicw.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtvjdvykja.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtfqwqkwsc.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtlrfqsfuo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtpkxnlyjo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtozahcrig.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtytovtwop.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtuuyjlynd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtomzluopd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtuyooadwb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtmxoferti.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtnxgmusmk.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gtliupitxa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhoulong.xyz/Article/details/gttklhzvhr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtrhcwnokj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtxdvpsksc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtmdcyncgs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtniuavmkj.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtvnwvkuef.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtmqbcgjzh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtdumpbkvo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtobmqzclv.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtbzysyudb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgqfaoixa.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtnhfcuxpc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtvhugxkho.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtaqqywxps.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtoddxfkxd.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwkgeywaa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtdggsxxzm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtxhssgqsl.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtwlrvhife.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtysmqxyil.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtazkxewez.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmsqjdmj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtlhcbgwil.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrbgpnet.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhecwoks.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtrqwavlqx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtfdvxwlxq.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtpxbdwgmc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtyisztkzq.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gtlqbhvzgw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtgtdeinlk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gttmvrguhq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gtyecedyrq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtgjumcora.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gthcekuxea.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gthssxnfge.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gtebfkjlra.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtfbqlcncg.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtsrafagam.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtvbgeyvom.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gthuohbocy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gteaxcvarf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtliocfjfi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtmxavnnjl.html


<!-- 参考信息 -->