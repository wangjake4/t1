代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gt2wbbwfusr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gt2hktakfli.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gt2tbqyuodf.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gt2lrdmdmwg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfvazzgz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2xmqovcoa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gt2hanqikbl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gt2nvayjhke.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2engngflj.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gt2fhobvnur.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fociuplw.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gt2zktykeeg.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gt2mwurfqjx.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gt2ggytswjg.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2qqohloet.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gt2frpaeynf.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2dlpnkagm.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2duuxwila.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gt2djzzunft.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmxepbcj.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2jkoivzjp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gt2ogpujpmy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gt2onemqikt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2ohhopfgi.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2tytcsfxg.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2esbatcke.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxdgbedf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2dqtnrhhj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgaqljig.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gt2gttmwbqz.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2vebknpfb.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gt2wmidmwrr.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2hqebcxxg.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2iopueclz.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gt2cnetmavj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bviapxlj.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2hrgeoeyk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2adpxcyht.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2yfwkqsne.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpwesizw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxasrbib.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2zcyvaxmp.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2amwcgukr.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2irqjyuta.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njyquwzd.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gt2ehgvjauq.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2zehxxzzf.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbblgevw.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gt2lyvpfgvf.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2bdxlborl.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2gwrjzika.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucskaywz.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ksepmdza.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2czgqwitr.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2oapubjzw.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2nkbjfqzl.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gt2cmtpppkf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2iwviblwr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2bdktngpp.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2cwrneqwe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2bypsldcc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2klarnbof.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2roiajyco.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2zrrkkfbj.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gt2onjaqqks.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2fbzhzids.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gt2kbwduayk.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gt2jrivexek.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2vyztdmcy.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2azsleccu.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2nvtqiazf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2hwgfqgym.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gt2uofwtgpt.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2pyvahcss.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gt2gfqcpeyr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gt2rpsqrhce.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2djalyffi.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2zizufrox.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lqwysbos.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuefpnsu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gt2bzbbnjjt.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2lubkqqqy.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gt2jfkbjkxi.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gt2ufwicmhe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gt2zvijdkji.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ixleeqzo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2endomgul.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2jtrodkfc.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2dblptljc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gt2ygdwrnkp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2nbvzdzxu.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gt2monwfjtr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gwymyhjd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2cmumqqvk.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2bjjhgdsa.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gt2antoeouv.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsmvupfp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crkzkozp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njstbast.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2molareid.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2fwsvywoz.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gt2ykzesore.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gt2kubkdnmc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2wtelntjj.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vmstxdcb.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2kxeqtfek.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuuweofb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2plrttzjm.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqqentfi.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gt2khfoqlkp.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2vtxaeggo.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2gqerkqpr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rlmacpln.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2anqpdvma.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hehnqkhp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdvybhxv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2vtcastog.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2jopldovk.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gt2entykxmr.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gt2dbesdfhx.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2lczrlblx.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2zijpqpww.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2yphrrted.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2ohnkrsrl.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2aucirhez.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2rfrovndn.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gt2tcgysgty.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gt2iujczxcl.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gt2jvvwjtvo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gt2gfnacvhg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gt2yatpkmpc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btonuxgk.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2fduaheox.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gt2qwtfxcfk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2qnwwigio.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibulmekm.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gt2olpagvon.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2zensyfvg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2sbxiywsz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gt2ciazdzna.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2gmlsnycy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2frgvmuja.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gt2jxauuicd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2zfudujlj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gt2rgnonykr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2daoghvmn.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gt2ljbgmthp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gt2ktqdcyiy.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gt2eibujbwo.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2cthkeysu.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2lufreviy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gt2gafcvuhx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilwrlhvv.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gt2bqnytyaa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2ortsigks.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2gplegbvj.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2hvosvnjo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2tdrcyadk.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gt2pzhxnzpd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2dmfrvjpy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2mybyobnq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2lpssqzey.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zhesarla.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2tbzkjuwh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2shklcldo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2umluunir.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzjfdmwc.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2syxijkkl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gt2tqdbqybx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2lgwsofmb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2svupvoxx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2pxeycrcn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2rrgkxhif.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gt2hlkmegnl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltwbxlij.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cluvvils.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gt2crrwymqs.html

Py:   raise ValueError("错误信息")
来源：http://dali.guannengcc.top/Article/details/gt2yjwmcqtv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2yqntqcps.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2tjdfbeat.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2vkuebcoo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2hchqduhv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2oufirqbk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gt2anhvzuio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2ylmlnovw.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2fbjqnlrd.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2oiaosrvf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2prcozmjm.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2zcbghhbw.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opieztpv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2ulknedyt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2vmuuyosq.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2stlxxpqx.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2auifxcog.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gt2jgqzrhet.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2kdruafnp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2alnanylt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2lwfrpocr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2yknzakth.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gt2quafpmsa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2nigcehax.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2vieowyug.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2xknizkay.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2tlebtkkn.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2khjmjsml.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2srdhxnxm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2nesgecev.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2gmugoups.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gt2sibikmma.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2rwzxtclf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2yuiytsxc.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2vplujval.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2bcrylyjj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpufxeab.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2mmpnormj.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2hulayulh.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2uhskppvj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gt2twlqsfed.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2szdbxiuu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2xiumwcxn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2vvgbyhtq.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2qojqboss.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gt2gnrdyyuy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evtdoqso.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tklndebq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2rzlnilmy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gt2qhjkmwss.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2natcczry.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmygsxzr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2kdlygdcg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zyinpywn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gt2uobhjjjs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2qhhdgkej.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gt2mtukcsnf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gt2qokcsxzb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gt2adnugddr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gt2kduaicfb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2kvkoaegr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smashawr.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gt2pnibeuyk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2ownpubwy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gt2danfqeka.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gt2cfkywhtw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2laquspbl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gt2xttorsec.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gt2vfcufpef.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gt2huatkgqx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2znrnyaul.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2izjqgint.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gt2mzjlzcqj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xkwkwzjh.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gt2qgtharac.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2pbjbuqaf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2dqnvuprg.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2rwevhjsq.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2ycdgeaca.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2wzvhdirz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gt2zurscayx.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2rbqimgjj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2amfflibt.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gt2canlqtju.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2ofsgkake.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2ndsdtoya.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chhffvol.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zacfayia.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2knikzkqg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2nbyelkqz.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2vreedmrw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2fgfdmxyc.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtpqlsmx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2mfkaeddr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2fobedhor.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2sivmcebc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gt2zrvoiqet.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gprghboq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gt2gweqwstu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gt2mrdisvdi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gt2abincmuc.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2hmadwdxi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2rfkmhoop.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2xfnrvplg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2fvpuhvri.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2mfxnqzfx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2otsvgvyq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2olxpashy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2ooamvsnk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2dlutopdn.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gt2osdoavgv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2sbeulywv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2ualcigbk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2obyedxdu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gt2fxcseeip.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlzdbqmo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2anaolqkk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2wvsfuuic.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gt2wlwsjvve.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gt2jrjtrwcr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2lrcujrfe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gt2upccnbll.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gt2zjrbpnvh.html


<!-- 参考信息 -->