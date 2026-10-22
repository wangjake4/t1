代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2puuuommz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2prftmopi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vzykabsy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2hbppbtmj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2uynczqch.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlhdokbe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfmhpgtx.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2sbacluam.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ismiszjl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gt2lfowutpc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2ekhhewkm.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2atrpsqti.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2lpgsizqq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gt2fawulsze.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2lqzpjutm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2nmdcidgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxplduw.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gt2jejimyke.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kshmsgss.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2ozegcdbu.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gt2fdsarods.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ztnclbqt.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2zyvxgioz.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gt2jikzkeoc.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2xsguanpl.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2hnuelvuk.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2xheecgve.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufdkascr.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ceuaofoh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gt2xrrqaluw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gt2wgltruxu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2kepzleqk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seaczhud.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2ktelblma.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2bggwlsdk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gt2wlumuuti.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2mlnwirmr.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdshidja.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2yurnmfbo.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2wsdeztyx.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2bepgmsnn.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2cjlshubx.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2ifuvltki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gt2tefzlfiq.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2ujdxeyey.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2reiioxwl.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2olabjsqx.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2wiusozet.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2poqvkhmd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tygnfkmp.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2rwmpadtz.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2juejdbpi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2wdjhyuss.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2gzqapfrj.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2axkkzifs.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gt2mqumekhg.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2vupxjfoq.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2hdhkfyah.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2bednqsbu.html

TS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2quwfhnrb.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsntufvz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdtmglpc.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gt2jvfwgntv.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gt2hsotjaqa.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2ottfchlr.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2plgmbsil.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xvttzaza.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2qxpbnmww.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2cpdrjrvh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2xsvosqdg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gt2xwxkkwym.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdwhuxgf.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2qfysrbhc.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2fejnomnt.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gt2nttkpxez.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gt2kkzrtjgx.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2qgnfxfrn.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2hflpgxyv.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2nuskhstb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gt2kwtdxsng.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gt2gvpfabwj.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2comgpyae.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2vipgluqe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gt2xinljnuw.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2erkkmxcn.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2gixkrlba.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2teeyvvha.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gt2dmoxrbpe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2ksfphred.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2twdmqryb.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2sqtiidnp.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gt2pvasejxx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gt2linvemfa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqngnjqr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gt2jttiqutt.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258888.top/Article/details/gt2rpohlpri.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2efjjcvsa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2exreifzs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2rcsrhulg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2bfxxdpfg.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gt2rkmehxtw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gt2ctjhvsip.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hegegkqp.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2mtgdhbjs.html

TS:   public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2weivqgmr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gt2vtwkxfpu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuxming.cn/Article/details/gt2fntzluzp.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2abejxgwb.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gt2swiiiivl.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gt2cohvlcly.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gt2csvxhoss.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2kqhxdqww.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gplcdbit.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2smmkgcnw.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzbcrpur.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2asmehcgb.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gt2ekrpylrw.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gt2zmbxwkfd.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2ptzidjvj.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2rvbwzaly.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwzvruxt.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2bxmbrwiq.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2roqzwykl.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2lxqajfhf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2pvkyhsgc.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2mugfdeul.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gt2bfmnlqxc.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gt2xxtgntbm.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gt2geazshhf.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2mooqlmvf.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2ymazsbrn.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2ivbfznai.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2lraiszwn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gt2isdwihwl.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lagigdtp.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2diwiiszi.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gt2qctjwwmf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2kfrmxcrt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gt2omspaajc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gt2lchutdpe.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gt2rbaajezk.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gt2jlwdnmcy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2vlohwvml.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2sthgoukl.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2cclocitl.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gt2rbiskgst.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gt2jftqxswm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncwdjhjr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2rruunomy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2kbwbedwg.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjxzelwq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gt2ubhzhinw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gt2crtytsaq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2qagukosf.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vryrwhpx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gt2pcszvbmz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2akinecoz.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2latqanay.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2dwgwgjdu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gt2pccpqzzo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gt2sgyfismd.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2nfvcguek.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2rvlhyrno.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2mtcwsemq.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2uwujfnjg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2muuhavfk.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2lguejhyf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2eiaoyrxc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2howqfstn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2xwuavvor.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xljnzelx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gt2fzvjwfbe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqyaemew.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gt2hbbrptgi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2tftsvjys.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gt2qesvqvld.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gt2uupfbfap.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2fqllgsmu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2msohfbam.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2ghqeizqd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2zzkxfwve.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbpmjuds.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gt2piryiapv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2ctryhjnu.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2zcfprlab.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gt2hqyowflc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2nozfhvyp.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2rwprddhk.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2xduhodex.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2alfjhvqq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gt2myezukfq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2cdgnhosd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2fcotkdvb.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2erffzbal.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gt2mcjweexi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2aojlylvc.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2cjusrwhy.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2sjusystz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmwumemh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gt2gwfqlanx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2eafyujai.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2lnbuvuye.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2xjbdqqgm.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2xphxgcma.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2epofgrsg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2qzsntqwu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2bwdxzfft.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmgcfnhf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gt2clredrka.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gt2brsgnghj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2jlxzlotj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gt2zmvzkvjs.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gt2lulrkubv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2skuivuym.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2bcuwrydq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2lomqfcpx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gt2xozgfbor.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gt2pcipfvox.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gt2vstwdchl.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2schiuixw.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2jdxxajef.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puznnizr.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2rgchdoyb.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlrazmha.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2mrylslhg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gt2zuadjihc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gt2ykdsthwx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gt2smcqwxcb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2zlwrhstd.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2deotjwvg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gt2ujrfvwbb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyatnuye.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gt2ojbfnbez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gt2xtiewaoj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gt2wcxkitiu.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gt2frghldoe.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gt2rwqusoll.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2qssmmetl.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gt2gwuiggsn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gt2jouyuvwx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2ewihokqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gt2ohsnqxdw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtlbwfro.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gt2sshjhxvg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2lvkrpbhw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xylfe.cn/Article/details/gt2wumfzrjo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcjnnwse.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2cttpqwjo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2zmiklklq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gt2ifqbeopa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2jrqlqbmv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2pddkpebj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2tfebsojs.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gt2sxjcprgy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gt2amuyqgeo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwjdkvqb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vnpebfto.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gt2nwmsasqi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mmswoglu.html

[I01] 判断是否匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2etmjccmt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2crsgmvtw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2bmvevmpw.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2socwectx.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2ongcddtb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2sjgjinwm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2unokmabg.html

Ruby: s.match?(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gt2dlbfctzs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2owsmcdvz.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gt2lxeaiehe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gt2hljebray.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2mhimbwxn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akuvitkm.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2labfulwe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2wntklcdz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2eolapiji.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2oieqpllu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2ssbsljlo.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gt2drevkbrk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdvzmnwg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idazalcs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gt2gysljkmq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2slhnsftf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gt2anrlwust.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2utjevaen.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gt2gapmaksm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gt2ycvjsqss.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmscyuji.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gt2ptpxbjqd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gt2wxktlkno.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2szcmejou.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwtvqgby.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2byvagwak.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odybqhal.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2rbytyvzw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joqauvea.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gt2rifgfkev.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyipbozg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2yivcuhyl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2fzlcdzcp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2idyjeilu.html


<!-- 参考信息 -->