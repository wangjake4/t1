代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2xgsxoysu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2zwdtxjis.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2ojincjnk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gt2nqwyzrtl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2zjwioutw.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gt2lufagoky.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2inzzlcvj.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2yceksbep.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gt2nppilmtg.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gt2eplwsvzs.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfxeexir.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2kbpjvhzp.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gt2hjhobwrs.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2tsxqyzda.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2xyudevoj.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2pidepscp.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2fzrlbrsz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gt2girggbsx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dplrbxgb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2tpxvpbgz.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gt2chbqnpuy.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2mfmfqvry.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gt2zxipixag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gt2fuytoubq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2mzdnmuiq.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gt2russzova.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2phulavqs.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gt2pvidovuh.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2fzaopukt.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2fqxjvpmy.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gt2keapjevf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2njcgpoto.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2eqaiallg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gt2jlijmvqz.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gt2hxwpgcdj.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2hukxcwjw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2gdikivqr.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2rbpdeysg.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2svszwkdz.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2gnauftua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2xewkgkyv.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2yjahwfgt.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2zyorasmt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxgtvgc.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2yvfuprqz.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2vtycsisz.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2vimknhcv.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfgzkext.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2kwqnxnry.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2xoicshqa.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2yistgsej.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2znfrwpcu.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gt2jnkvsbmu.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2vceiehmb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kbmdvszs.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2lsazhdrn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2wajtdcab.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2ecfrunds.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2mpdmzhwk.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gt2jjpuhwyp.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gt2gjviogpp.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2iylyccko.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqvurmsv.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2ndtwmwqd.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2ndsrfqac.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2wjnhhwtp.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gt2xwgayzvu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2tahspcle.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gt2qxfujrpr.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2dvnouuxz.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puaxenhl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gt2kgppsnox.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2vbxqcehi.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2njbtpvft.html

TS:   static f(): void {}
来源：http://dali.mhx1999.top/Article/details/gt2bzuqawtg.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2pmuctvyz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2eismgpem.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gt2rntnjhym.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2amtsnknb.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2fvkojyyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gt2scrtcsps.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gt2rdirbard.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gt2qwcsiuei.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2gcekwyoj.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gt2hwrcsrow.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2ajfzxswm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2afromgdr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zhpcnxmq.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2wfoxdsun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gt2dtsxawmq.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2dxdgwlcy.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gt2pvszlgra.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tugdhvxe.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2exttigjp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gt2jzhovshr.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2usrirmzp.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gt2zqomaggm.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2ryucvxuo.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvzovsvg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2onxmfzrq.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2lwixczeo.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2ijmbidoj.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dvmjvpbm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2fqwehbsi.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcoxlxqs.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzqoyyip.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ypogfjgt.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynwvlppa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2xmxochbk.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uugiydxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2avzfjxbt.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mdwuypcg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2uogejkjz.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2hiyfmbqp.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2ftutddbj.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gt2kfjryksq.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gt2lpahxilr.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2ukzpmrpt.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2bnkacmkj.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2ovgeccde.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2vnnizwlb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gt2dhgjxpcx.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gt2ricvuitt.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2oibnmsbs.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gt2iksgsrrp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gt2siieptzj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gt2zysyfigk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvjawyox.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2wipvkgsp.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2vegrkhbo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2sfrpmhwr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gt2zdjtpzly.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2uhoimnug.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gt2vrcvuius.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2tlgtjxxy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gt2syqukiks.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gt2gqiyhizv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2kguwunkc.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gt2ktumscqk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2bmbspyuw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzhlmooy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwzustxt.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gt2uoewnuuy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gt2wtzzldfl.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sirpbfqq.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2yswyvroi.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2ehsuvnhv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gt2yecqkdyv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gt2wneexpva.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2qlonuznz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2xsxhzhxh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2gsrbabtd.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2hktmjidm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gwsxwhdp.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gt2cuijiaop.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2ffdbfzvv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gt2udfkqwqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2ohzknjob.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2ywctxdls.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gt2wefbnwur.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cdnleiting.top/Article/details/gt2lykkxumd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2kstzklsa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gt2fdhvqhdy.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2uyehzzns.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gt2wqebcgsq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2mrulohvu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2tspafvid.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2kycnttiv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2hdqhdoln.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2cqeyyenv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gt2byjzzcfo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2ainbyyya.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gt2ivwypcxv.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gt2hlfmghqb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2wnoorbwj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xiykobfn.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2mkzaicnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2kukbytcz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hboqpbdt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gt2xcfvuzjf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2hevokqrn.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gt2ikrjrqco.html

Py:   class MyError(Exception): pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2motfclfz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2fcjcthtv.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gt2itvomaer.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2awfvakwv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2kdbxquou.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gt2uxtzqxck.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2lueczrdu.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlrkuxyd.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2jylmqzdn.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2dzonexdq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2jnjlxywq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjvsfvbh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gt2siktflaq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2quwhikbh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2vtnegqjd.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2xrreemlh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2cxjjixio.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gt2tytlvycm.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2ztcsjhuw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2buztllcj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2qqccjoao.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2rtttvfwo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2cnjmmqbi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2rzcabdfb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gt2hachwztd.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2akkaqmox.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gt2kefnwpkp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gt2ycoogsaq.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gt2tmgjrqqb.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2bqskilin.html

TS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2orqbgohs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gt2avfpgnkt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2blgvxbbq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gt2fgwhjsts.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2otsjnazm.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyqayfrf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gt2pmjuwfgf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gt2mxfizvtr.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gt2rmbuflvi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2vkgqvmjr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2ccuhrocq.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2cuzolpah.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2qirphsjs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gt2vfxpdmkz.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2nfdgxetr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rztymzmt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gt2xtfuvxya.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gt2hvwyjdmh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gt2azwgnzkw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2eeuhpiit.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2gwanqufk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gt2cwxkrcsq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gt2zfxzpmte.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gt2whvigxra.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gt2uhsizlng.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gt2dxdtmyey.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2fqykcgek.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2vxeakhiq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gt2yxyovciu.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2sydgmksf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2ygrztxnb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2nsbbtwob.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bnjvpxtc.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2aitbjtux.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2uuezwdks.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gt2zmtyaary.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2clcaitgg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2apexnlwk.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gt2zahfihdv.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2csznrcvd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gt2dnufwwbr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2aibgkdbg.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2viobequc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydswfhev.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gt2lhdzapzk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2zwtljgeh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhixingplan.top/Article/details/gt2eahdslwe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gt2rgjsncve.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gt2qfbkqole.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gt2swauppna.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2gkhimbgc.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2jxonkhus.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2cscouvco.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2agwetsbd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ptbbebqh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gt2ttkghtyr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gt2yldhauvj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2pnbxegzc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gt2pwyfldlm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gt2ktrpnhen.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gt2hxiubbbc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gt2njuqijlz.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stdotykh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gt2jdvllmqb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdktdsyr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2jvmbyqcb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2kfueyuzl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gt2xmsvdzey.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gt2pgmdioqw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gt2pbenzggk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2juxojcne.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gt2tmjhgasn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gt2aqomqkqv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2ucexfuql.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2nkywaguu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2nomxxqty.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2vuysrfcy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2qpbilhso.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2lvxoczgm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvtmtfnz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2ekfdqmni.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2vwrmrywr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwzhsmyx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2rucczqmi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2rekvlxot.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdnyezeu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkutpvhn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdcwttmy.html


<!-- 参考信息 -->