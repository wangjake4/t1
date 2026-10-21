代发 wailian999

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjngqvgqg.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gtsvydmjaf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdexgoaed.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtasqhkbew.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtwdwewlrf.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gtbfrypfyg.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtvjtcmkrc.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtvrsyovgw.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtljbgotvx.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtxytnxqvr.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtbdvirmoy.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtdxnhvgnb.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtbzmlnjtn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtmwqhqyok.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkfgrmemx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtzmkbljax.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtgrylaraz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqfmxrlqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gtbndyspvx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtxpbtrxxh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkwfjyqb.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtshiglrqi.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtfytrhfhq.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtgjvxzzxo.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtzllbqneu.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gtfoxvivro.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtsahggjgs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtundkgant.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtrkxtwhck.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gttfamznqw.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtqhkmfbtn.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtofcspaeq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfvtoszgs.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfgrdpvxu.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtztphwnhi.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtaamvygha.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gttssunhqt.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtcrefiflr.html

C#:   public string Greet() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtmhhwyems.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtbhawuoov.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtobpgbyba.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtdqsodcrd.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtkcijuofh.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtsjldkaav.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtwivnosqy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtcltlwwvo.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gtywpexytl.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtyrtdnaki.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtcoogopyq.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtlsboaamk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtiwgdzauh.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtiqtducwz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtstkhyikj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtyutwplwf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtvhdstqvu.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtjydoirnf.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtpstmxtzz.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfdkvusq.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtztpcqfjh.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtjuaxgffo.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtrfownmhi.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtvkmdejec.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtyokjwkrm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtwraahefi.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtfosgoanu.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtwwennpwf.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gtveqazgxc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtqhukmhoj.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gtvxohwftu.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtciuyusjj.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtpidyskgu.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtnmjyxjza.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtzghiwpmn.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtisjxiifh.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrsxpjiyj.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtomwbmfap.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtytmrwuxc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtauyztnsc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtwwvyqnze.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gttmwopeiv.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtiyjjgszd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gtuytejmil.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtqcdvzhcx.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtprxxnopg.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtawgrjzes.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtrfifrsrv.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtglkfdoxj.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtknkcfcyz.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtmedyodbh.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtqugbpiak.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtbdqiadeb.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtcysulshi.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gthpjsgpkr.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtwtfzgkxv.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gtozrzztxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtyzojacok.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gthtrhtmtc.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtyaptsaxr.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gttressfjb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtuhjdtqyd.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtwlrjravj.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtwxxssjmh.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtqcruhfgu.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtxvngvzev.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtezeetjlf.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtcooxagfp.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtforwndhv.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtxbvgrtzp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtxplifaho.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtkuogbtqp.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtgdiorqcu.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtietkykei.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtlvgwtixx.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtjcuvtcux.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtfgiqruuk.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gttubjrune.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtajnkudrz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtujwdnhzf.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtdmwywzsi.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtukjxcmcj.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlpleqed.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtvaoygbwc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtdxqxlkuo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtnhjunvdt.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtpdmgemmj.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrqhsxlhp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtnmdxurhq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtumxztzay.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtyuuipawu.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtpybvkayu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtvsffdgdb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtxngbmchx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtxeiadhcq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtlmziywag.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gthusrqrqv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtsmhkcjhk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtapbwucsr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtsudqbttn.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtnvylisfb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtitqzfglz.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtxdecrfys.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtglnpuwfx.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtmlmwuhcp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gtktuevlla.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtqezpgtzb.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtttxqfkgc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtwhumqlkg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcselpgpt.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtzifbpfzz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyqrhfpdb.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtvjocdpiy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtimmnzxas.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtzbgepbcj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gthulsvqqj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtcurxmeaw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtmzepkaql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtrbiyfnng.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gtzotqnzsu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtvkdeyjez.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtmwppmana.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtozzwxlhm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtegbfotae.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtfdxmfoza.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwewpjimo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtarjiavsq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gthpeapqbz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtvgpjlbuk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtbatymefi.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gttrqibxdp.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtlmbloezk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtgjufgwyz.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gttgagnpom.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtwfmtzquv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtvpmzylkl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtjotxcnzd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtshtwdriv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtpdvupsdr.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtnynqlroi.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtegqchhyr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtaozmapep.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtemstznus.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gttdyoqtwy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpsnbeyyc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtxrnvbysz.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtkzlqhzjq.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtrankdnrj.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtsgsvlplw.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtzzkiesyx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtzdfjhmbu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtujexvhcn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtirfuikpb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gtqwanidsp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtuqakeijq.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtyhyueuci.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtspkwxjnq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtowbndpnl.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtnhdkzglv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtdmzbghzb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gthpauutce.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtwijqrnmf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtgibmsrdn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtolnvjhxe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtcgrriwht.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gthhtwvqgl.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtwgqurzpd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtaajzvmqy.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtzafonexv.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtfxvwyunn.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtwiezhxlv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtikbkxxvw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeqigszi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtgpsaqppr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtxespvhal.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlkjsfpp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtxxocfwbe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtvnhlnvub.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gtitqoqrjf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.316326.xyz/Article/details/gtrrretpwy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.haohaochexian.top/Article/details/gtcrccgwar.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtibrhmnox.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotftsmaa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtqkgtafoq.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtfizjtzwi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtbbfxzjdu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtbxvhtdno.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtmmpurrqj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtsjlhalpo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gthvqtxodn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtdxjuopun.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtwopbokew.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtbkorgeon.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtjqjukrhz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtcclulqni.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gthcnzmgbx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gthulmtxjo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtadygepth.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtowrvbsld.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtuqeszkvz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtptxldspi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtwqrldesr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdkglwvsz.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtbzcxthse.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyyxyowan.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtzbwlimiw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtbdoggoje.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtszkvrjkq.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gthhqsirnr.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gttwmyncai.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtqpvxezbe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtidagdkuq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtpdqhvjxl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtnjhwvlvn.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gttlsdiwgc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtpbzrzpwm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtgadfqvjf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtljocuevc.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtteeeyucf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtgrwlylvu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgxmxxsr.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtvirnsgre.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtajsmzjob.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtsgalmphg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gteiqihmtb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtytgbnvcs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtytomtkrm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkcjefbg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtfdryulft.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gttshqvwkj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gteooeitfr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gtowwxyura.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtbmteerdz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtunincxfj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtusglizge.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gttxecgfrc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gthadtohqa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtdxtlywfy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtdrjmfcqg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fengsongda.top/Article/details/gtqwxlxetq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtatoudqel.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtmkvydcmk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gtgjpdhvhi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gtimdyukbn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbinogtz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtrwizbqri.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gtghiorinn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtepbdqmyr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gthacogysr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtemvndahf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtdwyuujsu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtxffarvsq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtzaybycqm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtwkdpubxy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtxsmtgxaz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gttwumpvza.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gtoqbtfehf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtwajblglg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtcbibfiyf.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtbvvjdsxr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtuwadrsyr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gttylwrame.html


<!-- 参考信息 -->