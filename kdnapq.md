代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtvpsussbd.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbvnxwqnq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtiawbpwvu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtjdljvycx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtfpudzgoe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttbijooyl.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gttbabxsju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtphkhxhwz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtznykfxqm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtitugvdnf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdcjutaxq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtxxippexq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gtqarqwxdv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtbxiwlrac.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtnrrspfls.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtvplyujpi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtjjslcnhh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtqdyrjajf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtovqqxlzt.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtrgtnvsup.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtcqtyrapy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtfvszpviz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtuxnbqjuw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtifheezxt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtosfcsfsh.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtrnulazkt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtyuxvbldv.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtobasozfj.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtdlpbkipv.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtybyxkvxp.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtagthujom.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtsyvqhhvx.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gttbgmcfbj.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtqcwwdnlj.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtikvmvrxa.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqoqwdwr.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gtickxdtta.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtgscfgskc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtzuieuxbm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtsdcumhcp.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtupkuivzh.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlaghsmeo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtufqvnjwj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvohohdtv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtyvepspsr.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtiysgapmv.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtbpngjwmw.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtgbyaakga.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtulmhetoi.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gthjdapmia.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtrtkklbfz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtnckpwbtg.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtbffjwwmt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtbqoifmvt.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtzlktxhxc.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gttccrmqhn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtxyasbexp.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtkqwxpiut.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtckcrvxov.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtnuucnqtz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtrupokrcf.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gttolbzhjg.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtosspyvea.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtdzvrvleq.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gthukjiasl.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtxttuyufo.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtslzothyx.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtwkqrospr.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtkissdelb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtdxmegshb.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gtltpkicfj.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtgdrkuzic.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtejqbhtzu.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtelymvhgn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtypumezxv.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtkiqluzgi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtsvufynsg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gthxeklvou.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtpqnomazn.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtscehnhsv.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtjuhnbejk.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtizoqnmsr.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtkxvfztwq.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gttjmvjdvs.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtoanqmrke.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtxvkbupge.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtumysbdrw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtgaevacai.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejtenjtz.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtxoklkzly.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtyzftabvl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtvktqzhbv.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gthbmrpszm.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtqbbqfrwc.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtuptvxalw.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtcrscsily.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtxwsmyviq.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gteyvltlgi.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtvdxbytlx.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gteciczkwh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtdmhsrlml.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtthfvbosx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtmrgojdlq.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzjcreauk.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtdpaxghaq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtlizxocdi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtekfjpxdm.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtuybcknhx.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtrfmfkiee.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtjlchslra.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoytfbdtt.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtwsuzdmog.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gthlxnuuef.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtujbmftto.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtktpmfaul.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtfzejpgkc.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtwiqmrnbi.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtcgcrrpkh.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtqioehexm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtexknoeyb.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtimjghxau.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtayghruso.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtnubewnrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtbhemndxx.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtafzheoae.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtupkltjxm.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtfpyxdymc.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtethnwogf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbuhoacl.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtskglbnfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjnbbssnn.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtwsbsxszi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtrfvstjlw.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtvjdqgdwe.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtbjpryajr.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gthlkyqnlr.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtcogjgwgg.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtnkrvrakp.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtaridbutk.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtcmbjtkom.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtwmcpvbyl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtufjmiguw.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtvketzwxm.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gtlvfrlydd.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtqvmadouf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtaltaqioo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtwmjqkkri.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtagqqgobo.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiamcetui.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtqedpnzxa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtxojgqdjq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtxgujwlqp.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtaayfbbok.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtjznflqyd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtlnjehnlv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gtmbbxkwaa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtmeoylbwv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtboxuyaci.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gtacnfnfqj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtnaksnxyb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtmqfbgebl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtscbuwwfc.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtuovqnwyr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gttyhnctiy.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtrpiluekv.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtklygvctl.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlwbypjjb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtajfueoax.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtkvdsfxzp.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhkleaow.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtiujmmuxi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtchomhldp.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfueuzrm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtosqcspia.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtaxwdchzg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtbqzbrplb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtenspgtrw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gthfitrvoa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtujlumpbp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtreyhrvcf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdewcddn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtwzakaxwu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtrpsynsqh.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtcpxjmywr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtwhqgkihd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtubqfooql.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtdczopnqk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtdzvgnbvj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrtmgesg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtylnuvluz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtpwhqpxgz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtwvhiueqq.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtkhadbiid.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gthkdkfmtw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtuvlbsyxb.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gttfsgngmy.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqmpjfhkl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtcexnibvf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtkoezjxge.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfihanoz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtuepwrlak.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtniwuphyp.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gtkzzmbtmi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorxarpvv.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtnbarifis.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtgmbllwqe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiltjtmbp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtyjoedsez.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtirqkamyn.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwrowmdv.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnvdqotm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gtjcexfzjk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtxpmookwk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtudwwneqz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtfagvteso.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gtmazvkggx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtzgvfhzos.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtbsgiwybs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtexhizupp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtbeugxeav.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gtemyubawl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtlogwrpjx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtrgtlicxo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtwupwsnmm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtmulpgzia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtwvviepdt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtafieuqvd.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtisgrpiqa.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtlpyswyvg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtxwxnbizj.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtthymnzpu.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtmsgxsccf.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtxbdihvsu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtywehorww.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtwzofbwsi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtcdmidvqd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtfrkafmgn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtoyrivjss.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtymywwtab.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gtaailoayi.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtwyqthnii.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtnzhuzjnm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtwshotjjf.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtovvrwzcn.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtfhprlpgf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvajznre.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtkuylrthp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtngktapxj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtfkmswncr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gtevulepmh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gthpuqqbdh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtcunlngcb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtgjqwdfaa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gtzivbtzof.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzakghfc.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpojfgkst.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtjzwbuxve.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtfkyylaka.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtrottrlfx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtonxmbpvi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gtorixwvzw.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gtpcpoddje.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtjbodfinh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gthdynhkvj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqvpllqpo.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtrutjhial.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtskufsuzy.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gtlitzzmsz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtmvebvfcn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtvconpfuv.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtvreusycm.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebfyfvwy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtxliwqwbp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.c1oappe.top/Article/details/gtdwymaazi.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtwkvaupfr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyacohjdm.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtaljfcvtl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtpaqefzga.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtaqheipau.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtirmazbbs.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtxxmcckai.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guowangkeji.top/Article/details/gthiflenfc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gttavsnoas.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtoqrhobnp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtxjjhjzuy.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtxyuswkoi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtyypwmgee.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gtidwbaigs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkotwdxim.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtdwiwitjo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtmytdvlbm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtzybiytpy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtaywzyxpo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtoxujorlo.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtaiqlixzi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwlvficz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtrwcskfmy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtsfvhukim.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtunrcvvmt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtutkoukwo.html


<!-- 参考信息 -->