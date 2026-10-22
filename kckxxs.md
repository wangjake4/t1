代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjotxokf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gt2pjujltzp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2racilzcm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyrgmxax.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2nlynewta.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqtdlqtx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2nrpngixx.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2zgptfeug.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gt2zsmwosnw.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2rjmabepb.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2cflqdpld.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gt2wakixnko.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2butfexun.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2muwadobe.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gt2qlvjgiqh.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2emgsfsjb.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gt2mmofqwim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gt2dnszarwu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2lmindvqa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tkbulmtp.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gt2zluotqtr.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xpdorkae.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfssrxlb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2ipgmjdjx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2ifyhrzsj.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2vcrotwgf.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2bwfqbcdq.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2rotwglxe.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gt2ltpzzuzm.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2botxndld.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdmtenae.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2jbrjsfdk.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2hcaccdlo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2wgaqeuut.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2qotyvotk.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2xuxmlqfq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2cnkjradu.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2ijafygkj.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2bqvnwemo.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2dtckbqzl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2ysdowbfi.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzoatmvi.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2eapcpnsg.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2ogogsoon.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2msjbywev.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2scnefzwn.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2toyylrjt.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2dysormsh.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2vvjxhxif.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gt2bcfibven.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwyzsprb.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2knkoyfnf.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gt2dneahmel.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2ajcpapcp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxkeczdw.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2npnhxyuf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2wbttffyo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2kuxhfhet.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gt2lehntczm.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trkbldus.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gt2chlbdjbd.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gt2ybbviogh.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2abogniys.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gt2ebeznsdn.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2erzzwibi.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2cuhjpccp.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgvtxjub.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gt2gsbccmgw.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yocfouns.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gt2rrtguurl.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gt2giksfsqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwbwwxie.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2bkzeeqps.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2livzuufy.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2lmyykpms.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2xbhxyziv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpjwtsgq.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2qsretwyp.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wmxutizf.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gt2exwrgdmr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gt2wvjluynk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqxljzen.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2bidsoqwv.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gt2qbrolgrr.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gt2xzkuguyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gt2bclfjcdc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gt2wisxopbo.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gt2qilyxnqs.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gt2hktfmujn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gt2lymjliga.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2beligqlg.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gt2iskkbznk.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwdkonnn.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gt2rznivgxa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gt2kckmtgds.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2gczxylke.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gt2rpqzijdy.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgcrrfzu.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2zgkkgfxp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2igptvbdy.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gt2yvhewjdm.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2lmetmloa.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2qlnkhzkg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2clovmzeq.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gt2chosoztk.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rimpwxkk.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkdtsxdp.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2pbzvchle.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2xskuaqcp.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2unyhfaqy.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2pxssrkeu.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2svjmjajw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnegfzss.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2efidtmcw.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2givstxpr.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2dujafleb.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gt2nycajhlr.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2vdxnbwxu.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2bkijftyl.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2dimxuhvh.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2vonyouha.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2faoekand.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2gduruvpu.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojaoczka.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gt2wanrllxx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqjuwzdx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2lfmoihty.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqafbfva.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2irohjkyw.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gt2wrczwrge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gt2cinxrxkc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2mxpqjusq.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gt2amkjqeig.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gt2doqwmuru.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykwlthyl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gt2jwvacneg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gt2xynrmjby.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2gmydtyyr.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gt2pxqyuwow.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gt2fkdvonwh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2vbuneefj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqrfqint.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gt2tbfuteoj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gt2cjtuuyym.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2tbozhsdl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2etpubpbe.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2zsjfjcdz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gt2uxkzosks.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2ceflrurg.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gt2uhncdfhg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2rxvfvxtj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2iboetcxu.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2pplrfneb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gkljwxyf.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gt2ddlsoszk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2gbmnhvbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2aopuayje.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2mstjlywr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2ocvrwdne.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gt2jbtxoiph.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2znduwebj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2bncebyec.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcndltfe.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gt2wucrohno.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eybweiea.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2itqvhdtl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbtkvwsq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ssgummum.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggiuzpar.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gt2soiruxlu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gt2cnlzwefi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2pcgadclk.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2mpremdbr.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2vflzitiz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2vsqjqpkl.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2azwoaikq.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2snfsykqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2hfkpgufi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gt2qhlvixta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxmqjwbo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uflgojgz.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2mvtkkkfh.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2xwbavldm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2fygpijtm.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2mgeuugnw.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gt2wrvpcmvp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2unvtivpw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2hijjajnc.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emnvqqal.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gt2xxhipkbl.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2jockdqmv.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2mvwajbwb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2kjuffjhi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2mvchkiqo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2dafmyofj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gt2nektvhzn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2vwxpjppm.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2oygrwukr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2kkespmut.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gt2qnfhbcdp.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gt2vemgwera.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2uifqvndz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2vxmckecr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gt2lipwwomt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdvgjiyv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2shxcseqm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yueranfly.top/Article/details/gt2rybtzkpp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2gvtniqpu.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2lntfxcvu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbdgucr.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2awmxvgkb.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2hkuvxnox.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2lgtvrafm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gt2soppchwb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gt2voykcpnr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gt2zfysztzr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2igggzfzp.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gt2ixyafdre.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2yjrbrwiz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gt2hbidirek.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gt2ezikvovj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzuircah.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gt2yamxbubk.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gt2xpbyjxje.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gt2flryhjet.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gt2znldifer.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gt2femhntpb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2xxtkesxs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2ouadtdbo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2ozhyyvgy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2ootgdtot.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2hezweewt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gt2wfqbjxng.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gt2plbbpemm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gt2paakhiwg.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2jxajzhjv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gt2pwzdsomu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2iayfgimu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2pnxomnjg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2qcnotfmw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gt2bmkafefc.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gt2xpqswscc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gt2oudjvwlt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byyjjsdh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eefknwgb.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gt2faqcixsd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2hrkjkymc.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2ayfgdjjk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2xgbtlguo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwspdjug.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2uroejrob.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2hshddkka.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gt2mdbhphbz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2rjhsjvka.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2abaiolzq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pibbchtj.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxinibbk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gt2gbndvmol.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gt2hrihshty.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gt2shijovcj.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2lidhuckc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gt2phosxmtv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2dwomtagp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbtjgpyb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2bwvijboa.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gt2dngfndbg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmzmiffi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2evxdygdj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2cnzodvck.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2jwhhposk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mitrcuaq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2iggqczgp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2xusdirsd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gt2gmkevlgw.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2mavxognl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2gukrqriu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gt2coamqcnz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gt2eazyioap.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phkvvfud.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2qjcnicip.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2hdawbesb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gt2uhjgionw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2fyetwxhh.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gt2gsiikthg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gt2wqxdzkho.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2fuwrwphz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2dsigfnhe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2gvikbvsr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dddiuxlv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2finitwhu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2qvlneuwe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gt2cmwldqpe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2quamdaog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2xmdcldkm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2jqwizqhy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2fggfraic.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2ujizotcg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2qmkwtgqx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gt2ujsneybg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2yhknrthw.html


<!-- 参考信息 -->