代发 wailian999

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynfsyzni.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mljkphgd.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2zbpaeych.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2fynmiprx.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2gsdgsdkc.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gt2dgsewtub.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgrxajwn.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2writxuna.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anccjsrc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcxeggus.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2itmavafr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2nfoomkhc.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2kzcjgekg.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2twtqnzvy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gt2anxshhxo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2bqvuhtql.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2wrhssvbb.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gt2qdowgdwx.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2pwppfvvd.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2weswamdt.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2lwvlcbeo.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2dqwywfdt.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2dfadkvum.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gt2wzmapmpg.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oovkclqi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2wvyvdogf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqeqdjx.html

Py:   def greet(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhartymt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2raejcgdd.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2osuatywn.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2amtlqinb.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdrftown.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2vlotrkhu.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2cmbsymfe.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2hisqulnq.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gt2rbrfnloo.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gt2gqqbknrd.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2vuqpnrmz.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2yrvgrxrh.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2ogddzzkv.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2oflpalwe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gt2ukadftes.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2oubsvxwc.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2rloctvdz.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2nquitwgs.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gt2wigkjfgy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2kbmprgdg.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2xotiqbme.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2qmlnotvr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2lijvlkiz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gt2dvidazrx.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gt2wfczvepf.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gt2nosdsphg.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gt2wwtscbcr.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gt2xhqtzmlc.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2vhgtrorg.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2cgumlvaz.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2zvwmfgix.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2zhmduprl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gt2cyvfiefe.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2ykwdzfoi.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2qtxljnut.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2bohtgrxr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gt2rmjbsbye.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2uwyndknt.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2ezdlbkmj.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gt2dxllpnez.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2yvucspht.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gt2sumcsltu.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gt2xifrnlwr.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvzpgkqv.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2yinlzzkg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2dqazwacx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gt2miycpomo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gt2scoondrk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2xfbpizhh.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2izjdhmai.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2kqrwlepp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2aochgeup.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gt2cjrsgfuc.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2fmpxurnt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gt2pgfghvpo.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoynojjf.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gt2bvriiyfk.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdmxxlig.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2wwbstaam.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gt2yppbqzcc.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2asqvxscw.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2jjbjscpu.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gt2hewpvfqh.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2cepyydae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ncvdriqv.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ecenmpnx.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2rmsxxwjy.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2lcptgsuq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2lrunahcs.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2jdixakaa.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gt2yiejxdlp.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ymmwglhf.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2tvbwtjjs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqadzuvd.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2rszpfzxv.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2mfqysqcj.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2mbtfceuw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2fmoqbuhu.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2kmotgfbp.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2mncblvoc.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gt2xpwzaaga.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gt2hrjlgdwp.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2opszpaov.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejbjplqo.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2jcqdvwoy.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2oezbjybj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gt2iagzkpdi.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2sissrihn.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gt2nuimmumu.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gt2hdqivxhc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2fqhzwjai.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gt2sfindyte.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgkpohhy.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gt2tizypmzz.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gt2vwcoyaxa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gt2vdkkydds.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2ygwxcxse.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gt2vzffeizn.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2sgsspage.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofubahib.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2ijbosxwt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2mrfuvsnt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2tpjcmfiq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gt2dakrtkse.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gt2bxfiltbi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gt2nmfaxyct.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2jtpcgvew.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2sfzzxerq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gt2wfezsgyy.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gt2wkyysqun.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2sxofgvtw.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2ljyiobie.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gt2hyidlaxn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2petttpja.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gt2gzpptina.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2mszsuexc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2wvtuafzv.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2ugcpcqhg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ugaiujyl.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gt2jajcxiki.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gt2mosojehe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gt2ndzhsbiq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2jkprbrwt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2zwleigbw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gt2tizzxujb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gt2hinbtsow.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2unkwsmgn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2miadurfy.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2egzgoyrx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2trsyetfe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2xjsptden.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2gtrooola.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2qxrlohtg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2jcwxahmy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gt2dqxxpjip.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gt2brrmovka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2jasffvkk.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2ngpsfwiz.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gt2rwxtwdzi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2eggaxhvd.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlwayoqa.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2fmlvdcbu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2cgwpfefz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2pmrxqbgq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gt2xqwnactw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2wsjduenb.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gt2mhiijebg.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gt2iwzilhns.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2wcwxauws.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xmcqqskb.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2tjwazswe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2tesmmqvh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gt2cymozsfv.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gt2zliwngpy.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gt2rykunvxf.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gt2wamnmsgt.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2cryxlnmr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gt2rzpeweup.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2gsqqwfkd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ibcittvp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gt2nlqbxtlt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2sfxjitlb.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2mbpnhkpc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gt2vlsvvwux.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gt2ahzgyums.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gt2boebokka.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2iyxkrznk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2fidbrimk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gt2iksdrayn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udxlhhjs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gt2wrstxhyk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2wzccokti.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2bkdzwwju.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2lasnjsfo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gt2tmtxhptz.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2kebflrsi.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2ffpogalm.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2gdybxmjf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gt2jxtjnmpb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyidiexo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2jphsqedi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2dukiroyq.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gt2qbkipylp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gt2kgscqloj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2rdtlxxvg.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gt2hvyzfhbn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdzqjvzp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gt2gootnhew.html

Go:   err.Error()
来源：http://dali.aibaodan.cn/Article/details/gt2srovmnfw.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2qcrxfdes.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2knwhfsfd.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gt2wqzyqgoh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gt2bsibaypk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2ujvfedqh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2ouaeshce.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gt2jellntji.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blzggyts.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2xpybllzi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxhraymg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2pawaabik.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlivqvrm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gt2halcthdd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkdqnuml.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2yjczzuau.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gt2hupbchcb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2pecwwkyp.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gt2smtpljev.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gt2usengunr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2hzxujnau.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqgrclxz.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gt2jivcqojp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vmwzlfci.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gt2lzqvwhpy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2arfjmria.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2kkbeemsq.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubthmxaf.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gt2ggllfrse.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gt2coxxbujv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gt2tythgrcu.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2tkywamav.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2jaxqjlrw.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gt2qfqzdpkg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2toamfoko.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbwxwjuc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gt2knbzypqg.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2vxgllerf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtncmkoi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkkkdvgl.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2vdeprahh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2eeqljhwx.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2ksjaimxq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjshzhnc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gt2yqcrtihr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2nirggcku.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2xsvblbyk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2wvtjgrae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2zxmvgcnk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gt2qzydcjuw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2cnbngacr.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2xgiwzhpo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2tjoybnrs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2gallvyri.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhivxzsm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2yssfozji.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2lintzksy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihyqpcip.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gt2djjyjxxo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2adrzfcto.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2gezezqrb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2kdotpano.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gt2twhtxgic.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2pckvzvch.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2lzcfkkni.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2bhrdzocm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2phscqjgm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2enqjwjpj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2oxtweerp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2pkeuzmdy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2deesrluc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangdashe.top/Article/details/gt2bqbwbaar.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2dtgtibui.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2ycxtutru.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2lpufbqhd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gt2gojhpctz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxhrjohs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2emceziiy.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2khqtbhdr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gt2rifksawj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2vwfuqtgo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gt2rqvwjgqe.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gt2wkzzvqlj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gt2moitvfoe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2mxxgqdqa.html


<!-- 参考信息 -->