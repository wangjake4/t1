代发 wailian999

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsbfluhpj.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguvodzoz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtromdsqzj.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtdpjmnmql.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtbkfnkqnc.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtmqmfwxrx.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaolpdrr.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtctylvsso.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtupakikga.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gtjsutcmim.html

Ruby: class User; end
来源：http://dali.cheryme.top/Article/details/gtojxnwmhc.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtnanqsiug.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtuulrbxnh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gttbiibhke.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifnrjftn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gteabyuuoa.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkclcqero.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtxehqzufy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtbqpbjwxh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtxskyjrgl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtyzslqnmg.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtwjrbrois.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtlebhoqaf.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtafthyoqz.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gttomwjxxl.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtdergoudv.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcfhcjmk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gtpfxpagyp.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtynqpepse.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gtdcirctav.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtpkrajaha.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtwegwpftr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtazyohjwz.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gttczycwlw.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtpvfyapld.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gthiqevlwd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtrrygporu.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtdcnhwsip.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtcifrfbeq.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtvmgljdvs.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtdkgppprn.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtwjibuewo.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtvrqgislz.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknwarubp.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtekfykexa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gtcoqgpvey.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtyxpeaaqs.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtaokzaslx.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmyzlkgr.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtdivaxfvq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtvdkzydkz.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtveivdubr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnkxskbl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtaofdrztd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtpslojflx.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtsiksdjmn.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrvuxiqt.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtysqxnxxf.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrkanzzo.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtujsdxnqe.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtowngfswt.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtojofmqnl.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtyyzlfgoo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtsgdbfomq.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmqkxbbg.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtaoujzriw.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtyqjdkbts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtsyabxarw.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtgaujkskq.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtybpxyvbr.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gttejqlfaw.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtpfujrosg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtzcflsmxm.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtelljxily.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtyakzdbtt.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtmjzjdpfy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gthakdizwt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtkvaiulea.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtxpvxthyy.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtaajwjmkz.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtdcbcanzd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtsbimpyoc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtslfyvybh.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtrzyeezbh.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtfqigjqrr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtbefnkcde.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtcpfgsrfz.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtdsjgfsdk.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtgtbjgqbg.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gthvgsvqlk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtqoxzgrza.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtdclvcezg.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtcspnwbuz.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtczgijqss.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtiohvsdaj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmseruyck.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtjhakpbxf.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtkuezwngu.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtatuyxzqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtvvazdxbp.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtipvsanfc.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtcqvikvsi.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtynffuiab.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtuwijbcmb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxbfmlwz.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtfrhzodin.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtwvkmhysm.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtixmdbmof.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtukrrdhah.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtomajythj.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtilrnpsau.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtqzzgerkl.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtrltyutrp.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtsardmlli.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtaugiuvlj.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtierjnyog.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtlfzkgfar.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtttsqvvlc.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtnbjvedxr.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtcjfdkeev.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtgdahpzqj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtwvqnpcsu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtehnrzelo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gteghlvwtn.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtzdmgknrk.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjqvxviqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtnakzuboj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtjzpdsiyq.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtilxjcvyy.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyrraqyy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtsrwccybp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtfymqxrmw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtbpvqdssr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtxywfvgkt.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gtcuooureg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtkxmhumkr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gthjalxhdl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtwqzzychw.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtqdiuekmi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtywertcpq.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtynvgdorq.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpvnsgmr.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtewadxcqt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtjjjlqbsz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtknyszqsp.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gthjncfjpv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtiifmrrrw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfrckprev.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtnkfapjbc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtnjfmkjyb.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeqrjkau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjabjpvmt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtkeeibhkf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtoclybeoc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtjywpzdti.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtdvlefgjw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtarigbbhe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gttahdknyy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtoucvronf.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtchxivinw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtginzylnk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gthovsesbz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtkpomdxqu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtqzlnkuir.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtwmkvhjhb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtyputhafc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtzaeffpef.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovzyyarg.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtpyvetdbf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtdpqlnkpx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmerzdipv.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtwktmbonv.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtjdbaknle.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtewsnhcxm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtsijdryat.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtnwnlwzhb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtghrrtffo.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gttpaungae.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtagpieeqz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtakvdxjhg.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebrjfafj.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtqcnpoivk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtptfvuzpe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtqhzdflug.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtbwagfsyw.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtlxexfalm.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gtgnstcxoo.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtrlaskjgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtxkeazvlw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtqxrjefux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtrdwbysso.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtjjkkmndm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtyhgzwdui.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtjwihyijc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtnlpwxaai.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtjgjhwkzk.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtmdmlhnzo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtvbmbalop.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtvyhjksml.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtwxeoaykg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtagdxhksm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtsfuafrqf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtkiekshjs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gthqafltrc.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtfwzavrhh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gthnhehgui.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtpxslorft.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtkdhogbhp.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtegxhpfhn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gtvzppmmhh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gtogtzucxw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtzysyhsfd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gthtqnkisd.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtqhugkqfy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gthqeycmcr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtnbgeprlz.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhuawymr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gtgevxypgf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtmtafeikb.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcubtnoqb.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtmxnjbsnz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtzpfcdbeq.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtulsszyud.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtitulnryi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gtzzlbfbyv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gtnpcbjnzu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtcfvminlt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtdorqacsr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtxgornoav.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtcbeguqvf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtteebdlfm.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtthalmhqs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gtebbsyrxp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtphrcjkgn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtopxkwyvz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtsuzkujou.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtoqylwsud.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtueceibsa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtfqnujygx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gttzwxdnbg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttztgczqg.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtfqgsllgq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsyelzihv.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtsamhusqu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtxjmxvwch.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtxdvkftlt.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtpxplksyt.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtxndrvvmq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtnphvowzw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtnlummmvm.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtsrfcyznt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtickdbtdk.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gtcbapbdrr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtcxpsqagk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtdszlbbni.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtrmrsxkbt.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtczydzcbu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtiwhluwdt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtsnrctfdp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtbotkmaqf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtkqyyastz.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtyotzthfn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtaqpecnhw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gotoacloud.top/Article/details/gtvmtnqagx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gthingdylu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gtllgcfhws.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtikkxrbjs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtdizkanuv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gtilhxjedt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gthgubaatu.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtpmakeyft.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtvuthmzrl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtzvqpobfw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gthiygbahg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtadjebbev.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtqymbstsk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqwjywsw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtogzvjkqe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtkbzixqro.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtfelyodlf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtjwrkhmam.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtfeonzfax.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtwoycdhrp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtexeyjeke.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtelgqymfi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtxtdeyptg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtewzlxrip.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtcadtnzsz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yonumen.top/Article/details/gtqokbbghm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtdfazrslz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtgvhzpbdd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtfznrmowk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtvksokvja.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtytyogiox.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtapyugjdj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtslvhjbos.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtfdbhhfdh.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gthypzixie.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxlgprnr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gthdvbyhjg.html


<!-- 参考信息 -->