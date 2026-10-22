代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gt2ayzxjilf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2hglumxyy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gt2yugaghbq.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gt2putbdbxk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2uzfkdzmh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gt2avidirsz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wblbhbcr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2oiaoecyx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2misrvmyv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfizuto.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2dcfgpekb.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2ykehjjkh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zovoadro.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2dibkhikk.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2jndeazil.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2saqjnwwi.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2evvcnnun.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihbhjhpi.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxkrkuhu.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2xtsvibxn.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2kdtlqdov.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gt2xygsqlnq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpqrefmv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2mspcdxqe.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2wtqzbjkr.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2wvrvqerg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gt2zavihpdm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gt2aofwotcg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2mpamlezl.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2ekfkihrg.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2qdlkhdoe.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2ftmguulu.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2gbghjloo.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2pybabghv.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2wrowjrvj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgzftbj.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2lptifuex.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2enyopcps.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gt2vwumrlef.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2otocwkcb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydflcnun.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxnvnlqq.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2yypijjjz.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2kouscepd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2oaefrgzt.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2drknnipq.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijcktprt.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2bnnvddov.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbpbbhdz.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2iycjemxy.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2wwmxyfni.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bgxnbfqb.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2lflkulze.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gt2necugngs.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gt2txunqzyw.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gt2qwbxunfn.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2dmmtmghl.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2ssabxfoa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2pfquujoo.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2mplkynbf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2scqzfkby.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2zvqbuzdv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2bjieiysw.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2wseieiss.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gt2zdqgfmcn.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gt2ksupwyws.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gt2tdevbobt.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gt2xegczoaq.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2crdeimlb.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2wkaibjol.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2flkeswvi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntfbscdh.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gt2ryijvxvz.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2wwodgsic.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2tszinmqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gt2rlhuqina.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gt2snyfwgnq.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2cskmlaas.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2aubxfvtv.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpfxqbsh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gt2tduioqqi.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gt2ejpgeear.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gt2amolmytd.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gt2txnxerkk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gt2pnypljnu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gt2ahgyncqc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2ymbwvgvb.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gt2borqnigr.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2qpjamzzt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2kwjruusm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gt2pldmwarw.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2lgzokxwi.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gt2nartekei.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2xjjartzp.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncoyiscf.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrbajmgy.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2bmcdbolr.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gt2zztilpag.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2scxzdvkj.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2uectpboi.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2hntbuuhq.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gt2tjkxqxcz.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gt2mzynyufz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2qzkftolb.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2kawjibpr.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2rmrfhqjc.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2camsidpp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2fjqzxvrc.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gt2sphttjqv.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gt2viwnzalb.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2nrjgdsti.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2jecdcjtx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eneerrpu.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2twbvqobj.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2mfhtagub.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2hxmjrnfv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2xuinmpnk.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2rqdjbcna.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2dhsqregu.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gt2gmoumbvr.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2nuldafyc.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2snkcajfz.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2kcsgwklm.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2bhxjaryr.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2hhsohdpr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2xuojebnw.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gt2yahwqflh.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2ozcxkjps.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gt2cxnjvyii.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbyezzg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gt2wiavtxcq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2xxcpsuef.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gt2gqniphum.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkqekaqg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gt2thjgoykc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2rulinctm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lydamiar.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2ccwcupml.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2bqyjbxit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2hingbrhv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gt2allbuvoi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2gmgrvicw.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjratkoc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ammgqrla.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unqvnmzi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2ggppdziu.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2qigmvcva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2swmcupix.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2nqfxhzko.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2xzvbermp.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2bqdtwoir.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gt2sdctgsrp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2oeekzefk.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gt2sgfikmji.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2olrubtnm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vaigyjww.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2ovezzlys.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wdwaygmr.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2hrhcaqkt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svoaajzc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gt2cyhkhpff.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2qhazqxul.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2bzjnxoso.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2kcfhidpo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbjnscwk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2nyyggkmz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2hgyhtbvy.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gt2xfnnjitc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2fwrzkius.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2lefsixlw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2fyzpjbjh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2kunrnzhp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2qiwsamnb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gt2ykwbiuui.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gt2zuikhrse.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2kqdhccqg.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2bqndwpxi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2txnjrabv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2dvphekfu.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2mhfkwasz.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2bebphqgg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2awkmncpf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2pzhwifcc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2pxktxrdf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2oxqqiicp.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmyojcir.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2lbmxtrtq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdxnkgwm.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2pgvinpuv.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2duuqomly.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2rcbcbqpb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gt2vlpfvxls.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gt2stusndtr.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2zaxmzcar.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbosphvf.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gt2gwispbgb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gt2kanwbkgb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gt2wcnmlsdk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcyzwkow.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2bsowrpnb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnkhwqbg.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2cfcztavd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtujuxto.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gt2qguqlppl.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gt2txekyrbi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2uhozltxg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2dvadudko.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2jinlqzsn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gt2wopllyqo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gt2wjictcxr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2rjeuagji.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gt2srfugfpc.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gt2fyqomdqz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2vhplttwl.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2qjbnneje.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2vdzucztk.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2acbtpfyy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpdhmnns.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpslazzv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnxvtpgp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2swajascd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gt2fkwnaugh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gt2bggwvgqz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aibaodan.cn/Article/details/gt2wwhfiijk.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gt2othglmeg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gt2gntkqith.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtsmwiba.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2oitnphnp.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knzxlfoo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gt2yywkadek.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2ybjskwhd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmdgrrjp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2tmrmxufr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gt2tfomqgqa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwpjnkue.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2afqhbbeb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gt2errcwcdj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gt2mkgnmity.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2vzlokdup.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2xbypqoqi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2euoheonm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jefrvgjq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2xrrgexba.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2hsitdczx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2yybtmsjf.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gt2sqnwdtne.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gt2ibvxisox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2mfswhiii.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wusjztwr.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aulprdtw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jnzmmgsd.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gt2iywmbuwa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gt2mlwnpyuu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2gvgdjzwn.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2eegkvjhp.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzvbiweg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgyannao.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2kwmwmseb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2xjoslidc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2xdsycusc.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2okttddco.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2gndqceio.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gt2zosnsekw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gt2kaxswlgs.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2jdaglzyo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gt2hfdofcys.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2pfvwnqsf.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2ytsvznde.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2klrdnzrp.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2hvqrfykm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gt2fxsxpoxd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gt2eahewaan.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2nhrhmoyq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gt2tbvfxxhw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gt2qbsisivt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2sznvychk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gt2xasymwcm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2ragkkopd.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gt2prygejhn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jianghu66.top/Article/details/gt2nxzihbaw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gt2wfxjtwzn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2upgsaawd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtpsgpse.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2fsxxxivc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjosuelc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gt2kqbyjnol.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjvjujqk.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gt2gykaqezy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sufxvd.cn/Article/details/gt2zhxopjne.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ehfshate.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2bnkwyzav.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahrdwfep.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2hcvjtmkj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gt2mmlpudiz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gt2axaxcwib.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gt2qvyyrevx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koytifsr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2tnrjmjmr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nwbrower.top/Article/details/gt2ztyezwky.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2jukajeys.html


<!-- 参考信息 -->