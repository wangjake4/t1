代发 wailian999

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2jmktuxaw.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gt2gjgvufmj.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2oklqgaai.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2qxgwaeei.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2xlgggucx.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqatiorf.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2ybrzbzrs.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ajbijybr.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gt2takmqcsn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gt2hkejwldk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2syfhylle.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2lnavrdre.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2itqwnirt.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2ztevfozq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2opkotlmm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gt2pbmkotrh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2fzetpgsf.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gt2wmexadfx.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2uchuijrj.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2xivndcog.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2fkiixjkr.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2eljsoxgq.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2okjmtaxq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gt2ophaksfe.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2phtjaxqj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2sgynfdpv.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztlkcxdj.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2qbilgclt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2axdoobdc.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yujneohi.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2iuqrpxgl.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2tpkfadvo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2taprwnet.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2crexwbqe.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2jrzkwgfn.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2itqnprmx.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2wctuqyue.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ajhlsmij.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2wryqyund.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2fygpwnhx.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2pvhiksqv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2qmehohag.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gt2xgdxqpty.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2uoteagyh.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gt2uvcgwnjn.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gt2wdfmzqpk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2pxvjzkih.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2nsqpzatb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2yvovsgfw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2hsspmoow.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gt2inxhzqpv.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2iualvkkd.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gt2wllyroui.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gt2nlzcuopr.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gt2fwznibqg.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2hgcrgiwl.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2bfllzrqt.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2uljmvqxj.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gt2fklwxytr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2yzirtrgy.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gt2nmixklup.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gt2nirgxcvx.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gt2nfdmhgzt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gt2pjddozvl.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gt2glmrnwfw.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gt2kdanbiml.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gt2blkpvwya.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2tjgbxrtl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2yeegkcib.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gt2gddmijnd.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gt2fpkbjaxa.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gt2zbbguoit.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gt2irwsxzjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcdkuvsr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmhqnqkz.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gt2synvqswo.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2kfsenzlg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gt2qbjkxifq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfozuzcs.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2excicfxb.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gt2wbmjspil.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2mqsrauep.html

PHP:  public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2wmhfsxyq.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2qnctwqgb.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2rwfzywes.html

Java: public / protected / private / 默认包级
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umjgwkzq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gt2curhkpmc.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2tztpozjz.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2dsundvtq.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gt2ayqoqfcj.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gt2lznglczw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2gbenpwqf.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2yjjtfsfe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2kifvwcrf.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvvhxxzj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2zhgyyday.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gt2fokoekdq.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jxvuskqy.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2inmvbdab.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2khsxvhxq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2clpfwiui.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ejbggfim.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2urupaxow.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2abseqjyi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2ifjzllqd.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2oljztmen.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2eyeaeudn.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2jaabfttu.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gt2kfiwcgbu.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2zbwomtyq.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2qmwtrthm.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2yihqqpib.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2uzchrjlo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gt2hodzdkyv.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gt2bqprvzaj.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gt2mrlqkdko.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrfytdqn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2vubgtiba.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aanjbkil.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpcfpugk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2ltrfpdqj.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2lfsxldkx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gt2ykpkdtmf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gt2bzwrjbub.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gt2sgmbubvk.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2abrxirgk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2qexkxkxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2wdbkniqv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2freaqpqr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2cwvjjuji.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2oskqzzgu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gt2kojdcpep.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gt2eczwifcw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2oynmkrvp.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2btcqvbma.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2allwrcxw.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gt2kuimqosc.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tngqovjh.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2jrctlnus.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2ftxlkoyp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gt2gnhuhktc.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gt2xnzfunhi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2osseqlto.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qgznaljc.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2ftgtbdzl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfwnxcso.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2fqpjoutl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gt2nxdrteys.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvuuyzne.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ezslvuiv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2atmkvyyi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2snonnohl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2zverwohj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2ifvcuccn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2fudmfuxe.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgubweya.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2szfmaqrk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyvnbojk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2anpllqad.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2oyrdyorn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2obwvgidt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gt2hfukvzae.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gt2vnaioklc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oviwwhze.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gt2aflehjqi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2mflwgbrk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2epkcaybt.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2qkghxbxj.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyrcqdxl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2ddvahxcn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2finafocw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gt2ansxdgbz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2pwycfmjx.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gt2pzqjdtjy.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2icudscey.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2kikuxzyh.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2ndkljfjo.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2yooyqpbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gt2hyjdurdk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gt2xkhkabmc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gt2iubpevte.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gt2eccponip.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2doysvvvp.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gt2dhfavxyz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2igmtoxcf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gt2tqizsyxl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrpndvfa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gt2waxerobb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gt2dachpmab.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2wizossyj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gt2kcikgwoy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2nmcdhizl.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gt2nptexneg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2hyfiautz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2ctslyups.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2bdobgqmu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gt2ijiordif.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2yhkoswpg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gt2abcyrtoh.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gt2dleadmee.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2wqydcxmx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqmlxnhi.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2zforxopp.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2bemcolwr.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ezznffsr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gt2mocpwccz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gt2tcykkviv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gt2bhtfotmo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2nioiimin.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gt2lgpajcpb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gt2rskcivqm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2dkbbprhq.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gt2dermnrrv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2ryzobnnc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gt2loleuzko.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gt2bifdhkrv.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gt2jzcgwbem.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2fkiwhygo.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gt2snjiorra.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2wimossyn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkomphwx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2adhfrkar.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gt2mlayhnoe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2svcrpogx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2rbsavqew.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gt2akqtcorn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2hlkaycfl.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gt2yqztxbbh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gt2nlxbmmbu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gt2mkkdmsfb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2lyudptmp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2tbvedhmw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2fbazjvpn.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gt2geiyihqg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbwcjmhq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2npcykpol.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2cwfmuzjl.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gt2mtiarqsy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2nigrdqgs.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gt2vxaeizvc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2bglptmmm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2fufoeltj.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2dcbchpwd.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjgxdzax.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gt2xktukyur.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gt2zisoezvt.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2awwcvjbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezobzioq.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2erheenxj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2notvxkfu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mslworrp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gt2sedgpzae.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gt2kiespwzy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2jpmoyusp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2uxzhrdpy.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2gsdxjjkb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtjkmuzx.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmeaygxp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gt2kkrohsxy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2dlxjigrk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2frqzrttq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gt2jzwzlqta.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gt2nbtwzhhk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2aodaijby.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csflbtxv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gt2evvtthiy.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2kqpegfnd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2hmkzbjvk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2xtvmqvmd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2nrlllaro.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2fhnfihfj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2zrtskvqm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gt2zouqdgzu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gt2rmvenimn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2rvbxsfzi.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gt2wrwbwpfi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gt2rnwjcvvx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2gzxtghsz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2uofsmzzq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owjiwjog.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2rotkphyc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2vxbdwzmp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2cdflsjei.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijxwoqxm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gt2tevdatqn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2pdwkhfkq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gt2vkljhgox.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2fyoquecz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2gvnuvhzm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2aqckgjnz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gt2weiyaqqu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2nqkgfeve.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2xdulwjys.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gt2frjsergg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gt2ljuhldxg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gt2iousfkzw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gt2wlrcwtfw.html

TS:   /error/gim
来源：http://dali.haohaochexian.top/Article/details/gt2imlsthid.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gt2ytoluyqn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gt2zhglgfth.html


<!-- 参考信息 -->