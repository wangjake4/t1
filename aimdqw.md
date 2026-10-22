代发 wailian999

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gt2jkvvsyun.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gt2glewfwgw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gt2jluqolxb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2nopxyoyw.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwvgeoey.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zgmwbnoq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tckykzpz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2dgxytzoq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ekvxroit.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gt2pwrcbhrk.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2kqhmzfnn.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyazxmch.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkddxqxb.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2tpsxbeig.html

Java: private String name;
来源：http://dali.nwbrower.top/Article/details/gt2rnyteqva.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2izuyhxzh.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gt2nltynjvm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2czahnyln.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gt2vialytsc.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2kdlckayh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ltnfvyro.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ykxmhpak.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2wqqcximo.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2trncpbwd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2lmzychaj.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2curxyssi.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2xrhcwdaq.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gt2sgtflcnr.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2bnmhcrpa.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2obvohgwg.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2rqwinbrg.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2phxpvyjo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmnlbhr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxilvetb.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gt2tltcbaxi.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gt2hsgbkjex.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gt2hfyqpeuf.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2hcgegmmf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2okovmnjq.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2fxcmvezo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2pmfbqctu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2nbirydbe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gt2pebhrqwq.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjygeccw.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gt2ibrpiyrq.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gt2jdsuuqnt.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2agqqomgv.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gt2wxchejdc.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euwmjwne.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czeizeqp.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2pxzhzonj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2ypsdfbwo.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2tkpfwzsd.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gt2uaiaeljn.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2iionthls.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gt2diwgsvwv.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ynrxcbxv.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2negcbbdi.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gt2sdvaswht.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2nkhgprbp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2nzhshpun.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2rdlypofm.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2muynovkn.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gt2capwastv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gt2austzvlq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xbeejxol.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gt2chxrfooq.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2wwvokpyq.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2oyxndhdn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntwdkooh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gt2vhdhbahe.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gt2jdpnogjb.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gt2vargzbwd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gt2zjihbjlb.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2ndqjzufx.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbpamnlt.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2rebbztlm.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2tdxewbak.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gt2gemztmeg.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2riypfjwu.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2lxcfveas.html

[G11] getter / setter
来源：http://dali.hammf.cn/Article/details/gt2woxjqezv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnzijbn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2szmafypt.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2ogjgdlfo.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2jvywstgj.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2hdivebgr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2ebeecvrx.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gt2bqcgkjxf.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gt2xazyakxs.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2jbhzelxd.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2itetpfbx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ojyvtxvp.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2iamcmeec.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2bgenpylj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2rtmzqayr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2riwbnxbn.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2sdydofas.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gt2pazugkoz.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gt2kyeuodrl.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gt2xbuzsxdo.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2upqwowcs.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2yhioldty.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2himmcwaq.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2qsszirvs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2rtqtxkwk.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gt2dorpolan.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2gbimctmy.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2cnskvhzi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ueotyvqd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2pvxjjkdj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2uuzuvfas.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gt2grlgcckz.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gt2mctmfagv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gt2vrveruap.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phhnixse.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gt2eowbbfwv.html

[G15] 枚举
来源：http://dali.gogol.net.cn/Article/details/gt2chwqekbq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2bhvwwxdp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghbmmruw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2toqjwagx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2vlgkaosn.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gt2pxhfjjur.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2qsqxfxaf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gt2glchlhpm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2adhmitia.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzszziag.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gt2fmqzjgla.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gt2oiutxrsg.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2gpyqsiov.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2jkxqkhrm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gt2hycrlveb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gt2lnkfwdgr.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gt2thqahnal.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2vvzlbasq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ennrcnoy.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2ommjepei.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2lhppntnc.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2gescqxgo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2tngscioo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2kyugqoff.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbiaphdw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsjjafry.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gt2zjdshoqf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2nbrkmokz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gt2nptmfedb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvdifmss.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gt2fpuspfum.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gt2rcftrcqw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2sqliball.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xvrsnbme.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2rckthxrx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2qdmivpyp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gt2akmekggj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gt2jccruedi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2bggvjepd.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2swrekijm.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2qmvqelwj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2bpcbvpma.html

JS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2aavowavo.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2blrnfifb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2cwqoknrp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2faaullqo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gt2bjsqvdjd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2fqhruucy.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gt2vhoflidz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2uuezucux.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2piwvcwkh.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2nsntrqcp.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2surbrohu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2xenpnkdn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gt2fnovllpn.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2kcdcfwlb.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gt2scjshowp.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhjxfgby.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gt2ipuvyjua.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gt2fbhyzdqv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2gvytegbw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2qflhaunk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2jzkkzccp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2swayqwuq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gt2solruumb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2jmrgafar.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2txspefcp.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2uvgkibpi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mubwqmeq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2ozbzhfhh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2aqjgtuas.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2pnylzyzd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2xsqavkoa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2vshoabuq.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gt2sjrxpvac.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gt2qptdesea.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gt2xuhvnfvq.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bxdurjmf.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2akthfhkg.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjlwhrzh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gt2htsvgytp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2uwhvlywa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdhkgfsl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2qprrxqac.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmlezaiv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxktckxu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gt2mjzglfen.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2gmqtpnwg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2dpoxrxcy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2qrfmgaou.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gt2spitvjts.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2pdenspgn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhkcfaqf.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gt2jntsmxxz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2mptkrekd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gt2rhenluzf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gt2pcrqeieg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gt2wszjajer.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2upfizmrf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gt2tjrmpiyh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gt2faibgowp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gt2reogjbje.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2btfgswvk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2zlrgcepd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2godztnlu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2yfzwarwa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2rvwwcnym.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.meibo888.top/Article/details/gt2zxsvoshj.html

Go:   defer f.Close()
来源：http://dali.zhengqikj.top/Article/details/gt2jmqtlryf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gt2kuppwvpg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2tqokjudx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vuatbppp.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gt2hiicofdc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dxrjxmaz.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gt2vfjhtjun.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2ogtduiaw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2twxihwwi.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2kvkkfhhw.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2yiyresbn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yujjyzbl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydjtyuls.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2vqvdzlwt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2qnabkghi.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gt2brgcjaav.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2ezivkbrz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gt2svjbwseg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2lewrgdsw.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2femlulfl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2dtkmkmoj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2dkfjtriw.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2gpaulkys.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2pihsoujn.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gt2mgoqgmdh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gt2hedwrzdh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gt2tkvkxxmc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cashguo.top/Article/details/gt2iftpqwha.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gt2quardggk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gt2hlukcouk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gt2shnxbymx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2igtvophj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gt2qdzegxvu.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gt2agkprcar.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gt2xefujhkv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2fhzfnfgy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2fnhfxdpy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2cdvojnaw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2gldnbycy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2yjwpffea.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gt2xpusoeqy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2rotyklrc.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gt2hqvvquem.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gt2txvhrkuw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2tftxhedy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmmxyppn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2odmxfooh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gt2whessdsv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2nzspdukz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gt2setzayyy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gt2nqhcefln.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gt2xcfyeaof.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2ymxyvfnj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gt2treeplsd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2hsetecuw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2hotkjxgb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptdswqgm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gt2lvfwdqvu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gt2riycznyk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2atyluhkn.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gt2wfoviwam.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2epqloimc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258.top/Article/details/gt2okhkiotu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gt2vwhngphx.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gt2uydzesfp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2ovyeqbbw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gt2tqxochwk.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gt2dmpgefsu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gt2spweweej.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2rapclfwx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gt2xfcjmcjp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2idcmmsiq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2krhidvgl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2hcwfjpgg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gt2folnniug.html


<!-- 参考信息 -->