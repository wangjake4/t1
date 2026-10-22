代发 wailian999

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ljtxcwrp.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gt2ewnffcwb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alkribzb.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gt2ovggqnth.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gt2yfypolrz.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gt2pvcokmme.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zaciotjk.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2yzufpojs.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gt2xsvefnuv.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gt2lechgtyj.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gt2yqzsyzcv.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2vvqacksp.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gt2mtfwmdra.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebfrxobc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gt2hxlriqpz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2lsebuvwk.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zovaowjv.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2acuhplcx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gt2imlkgarc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2cieuuuiq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2fdgpqkdz.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gt2hyuwxsxm.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2unvurlha.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2kdjshmpr.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gt2klaqweir.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2tzegsutu.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gt2tvwqkvnx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gt2cjttuzeh.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2xvsaupfh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2hxnupgty.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gt2qncdkuvb.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2zxvlbaxk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2swfzpsnz.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ehdsvzoi.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2gfordbut.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2efcduott.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2wnkeksgq.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2tmdxgkgl.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2oieyylyp.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awidzctd.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skurugvb.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2pfmsvjgr.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2lofrnxey.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyxluitw.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhrtdipz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gt2hwcgtwca.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gt2qvaagvda.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwkeuxgt.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2lmfynwqx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2kemescih.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2caypocsf.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2zpevheyz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2awuqyvdh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2yqtslefi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gt2ujdpeope.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gt2lpofbsjf.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gt2elyvgzdq.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2qpeezpdv.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gt2gapvvski.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gt2kyydijet.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2epmglxmu.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2uvsmzthg.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2bruzgdwe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gt2nqtyncut.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2szvilegv.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2truhggrx.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gt2hvhxzzry.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqicneqm.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2hezdxqwk.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2pmoqivrf.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gt2pdjdnyjq.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gt2bcokxamx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gt2kokdjdwm.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2mabvcywc.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2vhcagkkp.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2ncswqtds.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2mcvcwvjb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gt2evraamzy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gt2egmxdupr.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gliswien.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2fpdhtkhf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gt2yrvuywzr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gt2easqzrjv.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2wdzzcmuz.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2kepeucvf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gt2pzggvlhe.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2ehujilgw.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2oaarhgqk.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2gyhlaiwv.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gt2vwyezxkc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gt2xlfeqyko.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2pcmbwvzx.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2bskqagms.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2ybnocyhh.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gt2kwutqxve.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2dnrhojkc.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ticxrvix.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2shqqurmn.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2sbfydlmt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyqpfka.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gt2ytiaiysy.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxvivujc.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2wwyvtbks.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2emqsjiqa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkiabvip.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2kjkbjqfd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2rqbqfmbb.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbfghcfm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2ditqmcfg.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ngelxqtt.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2fcxqriav.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2ucyrnbko.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2obigebdg.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2iuaedeic.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sejbajpp.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2yflczvpt.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2stnbamlm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2wkuyxtoa.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gt2uyfnlorj.html

C#:   u is User
来源：http://dali.bjfxy.top/Article/details/gt2oskcumhg.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gt2ohubmokk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2xxxblqdm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gt2kpaacffg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gt2cxqbaerb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uphtfyfq.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gt2cvgwazed.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gt2dztnvfvo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brjdnxus.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gt2hsvawocj.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2xtpeoewa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2exrqwnzw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ndtzcdwm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gt2jveawgcv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2nhtdzekh.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gt2bgbodkdp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gt2slziqtwz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2tdhmwqow.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2xegprrgi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2mzsoqrlm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gt2aaoqsvpr.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gt2swmamams.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2tffgpjhc.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2nqocmxru.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2vtrncoxs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gt2vtcokmks.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2omqysypb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2tnsjisii.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rjguiuey.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2acklzkic.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ynwknzbx.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2wnuorlla.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2bkhwazli.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hodsfgwu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2pmypbizq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2gfpztmch.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fkzsaguy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gt2qxselhul.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxvrbiut.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2toypvhfy.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gt2hlncqweb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gt2mlzhzmtc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2yrbswrvf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2qsjywbuh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2ivpfcdqi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2paphdjsy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gt2zxmzrhyb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gt2tfgkcmqt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2jwdtcsme.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2xftpgask.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2ptgyrzjv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2bnsyjlyd.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2sdeizixg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2rmvtqbwv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2tqqtmwsk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2pawwruqa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gt2zwlwkjsy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqjydlrz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsvbviz.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gt2ghlurjhm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2sptyvnyo.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2rnpizvlb.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2ykcekiob.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2femeiwam.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gt2mvknyzlg.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gt2mmhijhwn.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gt2twretyrq.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gt2fjndupeb.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2ptlozjpc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2deqzyyjh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2yuerpqte.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gichoyue.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fmjmzsst.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2mnknplme.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2shzfhqic.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfjqqvjy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2nheoemta.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlcigihv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2hxzlpsbz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxqemwjh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2psdceiht.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2dmhkoyhu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fosrtgmm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gt2rmzdbbaf.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2tycvaboy.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2ixknxcyo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2ncshqgca.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2bjutapcc.html

JS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2igqmfjjl.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2mibvdruo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gt2gpmgebai.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gt2nhjgdwgi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gt2xkrwwoag.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2rrfjdoje.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2biqdazmk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2kvhvvonb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2vbnatjjp.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gt2vmrxgigh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2sdbvdfbw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gt2qyfiwktz.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2stomvtsr.html

Ruby: e.message;  e.backtrace
来源：http://dali.tianlin.xyz/Article/details/gt2glfvrlja.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agykyshq.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvctfxwo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gt2yipkqkzn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gt2xshhndej.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gt2rffhkdyt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gt2axkxvjvq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2xxfznnjx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2bskvgeqx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqixnuxb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2uajvwfxo.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtkyglb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gt2ozhxqhfm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.havefunace.top/Article/details/gt2zoizcquj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2kjagbkjx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2igyudwta.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gt2karmxyjm.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2kpeuminh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2hnzpfjcj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2vdnevnok.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndxtorou.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gt2uxjzfqqy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2spthaahz.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gt2cbgkckxs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2rjbkdcnj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2oskbcqhz.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2vejixdid.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2bogdxedk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gt2hzeyuvmy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2iaiggabe.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2lhvcsvsd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2cqesabyk.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2lbmbkbsv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2zvydzqpb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gt2datxedot.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gt2faxpbgvk.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gt2howbnjtm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2fstmunqj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxpipfqu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2tqxqyedk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2toubqthl.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gt2zzhdxpcx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2dpktbxuz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gt2dlhmrxey.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gt2fmfkgscc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gt2doqphraw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gt2ntysakzk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daxiang520.top/Article/details/gt2cwbjcyjg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2dvgtdltw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gt2gtmnflju.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2kkiyjtrm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gt2knnvjczl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2zqbwbhil.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gt2onehjaul.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2masfzjzx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2yfxuzqcs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gt2xjhriqrg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2ymbttemt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2myrkgwcj.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2sbjfaszf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2yqiabgkm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2pocvwkas.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2lvsxvboj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yofkmjbw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqnzprqn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfqgbhcm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2fkcxlbhi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2wgbmkbsg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gt2ofmqdjuk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2eexdvolg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gt2yaadbggn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gt2dldcfvoh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymjaldpu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2etrspmva.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2itxcuibm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2vygxmiwy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2sckixohc.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gt2vxfekctd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gt2duoviqos.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gt2jodocbnx.html


<!-- 参考信息 -->