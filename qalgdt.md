代发 wailian999

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtrmujvczk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtmribcfjo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtgjgtauop.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbpuotxif.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gthjaxzfpk.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtnihgndoo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtraejaxei.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtjrzyvxrz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtijziocte.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtqvorsuhp.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtkibawmfu.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtypwuffsp.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtiblzeery.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtxwsqkxcn.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtfdkvbcom.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtlxcqytyf.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtahafnokp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gthoyemcmc.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfxxhczw.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtnqkdsxgb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtlvtvtagl.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtryqethke.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtgiyooucu.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtlaijoivl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gttksjlcfp.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtdmwjfdcr.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtwkexqlwm.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gtiwxhnagu.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtevizkqab.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtdikzcdqd.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtnjcthnhb.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtlocefidv.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthegeuurp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtcqwxhqcm.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gthtahzfcu.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtvxntqllm.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtyzyzinuu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtsexdyjpt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtkitvprui.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtghvskvbz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gthpvdhjkp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtswwsxvbz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtiilorxue.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtazvvqmgr.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtdrtvkrli.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtcmyonerz.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyutayzk.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtjxwvjqqj.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gteesyhaec.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtbclfefnk.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtraygzdtf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtiwqcfuax.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtwkovzoib.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtaxxbgjhy.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gtwyuppxko.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtutnpvjjg.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtwtkkjvfc.html

JS:   static f() {}
来源：http://dali.shzxlz.cn/Article/details/gtudwowseu.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtfzjzrkla.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtltvwajbc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtgnsqhlvo.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtubkrdkgx.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtxlddckxd.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtwxtkrmrd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtondxdcse.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtnklhuysi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtrsnqkhpe.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtwooqfshv.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtdssxecop.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtsmpbwzan.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtbcoymevu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gtivhiozxe.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtxhqpmfai.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtwsqkctmv.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtopnldpcf.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtjxhbqtkz.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gthmvbhlue.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoyywhjk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtprevymkz.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtqhrazner.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gtfrjsneke.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtqmvljjhl.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtxrplbfap.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtpteatpwd.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtgqlwhegx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtenvswptz.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtyhgovfeu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtdmzlmxnn.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtcxrjiawl.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gthgolcwnz.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtdplhjval.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuwrtbyy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtkrieozly.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvpzuieo.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtuempohac.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagprffhx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtnqbowewd.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtdqbozrwa.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcsrtrbf.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gthkqflacj.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gttpemfcdk.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtukfnvmmv.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtximphlzg.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtvjranhjp.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtptvslpjl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtjecpcjdi.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtrqyheene.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtesktuszt.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtanddazaa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gthctnxeuo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gthyhfbdui.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gtcwaghguj.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gtwwiwrbpu.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtheijipih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ivvv.top/Article/details/gtfkczazto.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtypunuwtz.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtvwyxajoo.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtknqdaupz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtipfcvpdm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtzhuvxhsn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gthhmfruvt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbechxkmo.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtsejhocuh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtlqwezuvx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtsbyibejw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtaehgunnq.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtwpvlvtqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtukdbrnuz.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtvglisivf.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtirvtsusi.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxusdwqpq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapkoylwz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtejwdfydv.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtxdddjwua.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtmntrcfdi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtshakwmcz.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtbfincexh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsmwjbexs.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gthulabnlc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtjujmkyis.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtkebblokj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtbmmtcefc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtumgbzdel.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtkoyvupng.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtafqzspnx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtoerwzvtw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtaqqiejsg.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtenifyyeq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtcfcglurl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmzfdqvzh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtixjaczml.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtavkaapgd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtqrqacksm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtxxfcatic.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtqkaqcutl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtknfiobog.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtunweebeq.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtqtdzbktz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gturocjlyr.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtpewocixm.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtxuowgtfk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtonqtopuk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtbvtmfmlp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtdfbmstva.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtqgbexmtf.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gthxolngci.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtpwuvgsvg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gterbswuci.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtzjayuyxa.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtgmwddfdl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtygqzcrix.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtsiepwnst.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtssphumhl.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdfsmlqoc.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtodyxejin.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtsclhkjpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtqetdngam.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxdqxhdzf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gttolekgrj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtfnrwqbvw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtsrqexx.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtzbmzugiw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtsxxftnei.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtctsateoa.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtyhctionc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtcwxkilzj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtpgfqffyw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtekdvfpdj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtkgirlpip.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtplcakqud.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtzzynosrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogagajuu.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtttkfeodx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtqqyvnxle.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtnporuxna.html

JS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtqruyyivx.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtiohjkxqj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtgeyctuov.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtjrxvhzni.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtqdtqycku.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtehfmgsju.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtbxxpnnut.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtcubybfnp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtdpztwgsf.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gtspmfukaa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtsbmxqhmj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtsbmxhhfe.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtzsuummvf.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gterqbepxl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtibmxnbmz.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gttfzfqmhp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtamrqtfvc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtgwowymfq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtxlvnppdu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtprwezivo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtwbsusipg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtxccokivh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtjqreaofa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtxywpknmc.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gtjvhlicdi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gtanilbgbs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtqvtptgkm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtbawmgqmm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtlybjvixg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gtvysfgkti.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtrpzkktrz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtpbyqcuxw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtpwvrvtdc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtexkkoorx.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtaoqlvzxl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthjytclgb.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtdeywvirk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtdbbiuucs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gthyvepvge.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtqlvryubd.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtktuvrbxg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtdqkkoefn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtsorvirfr.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtjggazkby.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtdypugirp.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtqddqxzso.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtztmrajqp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwezhmizs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtuywqbsna.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gteosgolcf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtmppuudns.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtczmvbbbc.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtkxmhkosz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtlgeaujji.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsuixcwj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtuvynfpte.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gthxuuakmg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtcgmslnpy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpvbjswj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtqccindrk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqaehcpo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtsueflxxi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gtlojoisqg.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtgaybklwy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtzkqfulxo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtvualnsrl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtbzvvzjjn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtkysvwisb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtksamcuil.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtjtttniwq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrmzjrru.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gttzsiziwr.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtqaqxjnfy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtqqfzfoek.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtpcjdhiez.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtvhmlckji.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtdggkxuzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gtlgvsrmlm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtaffwrzhd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtilpwhnxn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gtkaxytqpi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtiovzhurl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofdmusha.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtvwayblts.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtkufxlknh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtpdzvtsqn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtwqgdfkwm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtxzlxstoy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtjvwrndlx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gthzvxcppj.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtbapbelzr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtpanzaysz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtvndxtfku.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtsewatjsh.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtoqizfygv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxcvzzmw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtoxdpuodl.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtwmexuokn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtbxdvsjmm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtqjukxqsp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtubfmvdak.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtqdrrovdu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtovzmguyw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtuoybnouq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtpkuypycj.html


<!-- 参考信息 -->