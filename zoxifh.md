代发 wailian999

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgadxbuxy.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtanngmhum.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttunbdgqr.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtiibfynas.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtccueoudf.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtlagxlxls.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtqqblodne.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtsidzpipo.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtizimeiap.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtythkvrpu.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gthanzqeal.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtcipehixd.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtgwfjalbz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtedtfphgr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gtkmsmmnep.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtlaiudzkh.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtabzleqry.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtxgqemvyl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtyvrlovjj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtbxwrfpek.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtulsgtbrj.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtxbrtvnmi.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtjnitfezw.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtrsidgqga.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtsmievxgm.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtzcftfywv.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtiwiywvyo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtepnpwhbx.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtusckdysy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtvyjsjqzb.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtsjepokrs.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtqfvirtgs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtxuucvetq.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtwegcbosu.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtuyiigjod.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtazwgfanh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtswobufwc.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gttwdtfgsv.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtzyelnetl.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtnmdeouse.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtgwnddtsd.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtmxgjdjcj.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtgmxcthqd.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgktdqxn.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtvojkfkzu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtkycljpev.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtmxwopkzh.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtpkfoapkn.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtzxpdjgpn.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gttlxwhndr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtaltyblyr.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtwitgcdwh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtplqzpxjp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtqlzrtpqv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtegzpodxs.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gtywotaivb.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtxbnpvcyz.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtvewnpjrv.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtwvsoinay.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtjrqzenvf.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtupohqgru.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtyktndmdx.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtmffuvuyd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gturcnpwqo.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacfwpbng.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgaalvbf.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtklthoajj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtzycwnnop.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtcrjlbgqq.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtgceybxow.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtkkxkkxgt.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtaquqduks.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtjbyidddi.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtbeqilykk.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtfofjnvzp.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtnoemsbll.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtdoyjuaeg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtwwrocpaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gtjvkthlne.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtxslnotid.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqgkyijul.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtmmfehdgk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtkdagwjua.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfntupxfe.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtedgsrroj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gtajyjrvgn.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtrlapayzl.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtbweocgng.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtvyvsdimy.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtfnsoqazx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtktfmhxpc.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtxmglxsdr.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtybmvkbga.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtsahxuvtk.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtugpcksig.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmfhqmhkz.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtygbvfela.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gthacvuupz.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxrzijwrc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtcnmhwqxs.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtvvcobsvw.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gtqnmlffwo.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gttyhrjzbe.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtoiqxzobx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtkgricxfg.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrjoeytd.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtlntkutvi.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtwexlsije.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtipsqpfrh.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gttgaolwlf.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gthjiswjts.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtnqjutckz.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtmzqykser.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtpdviimoe.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtnbuwmzyx.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtlnipmtme.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtftydvkoz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gtfwkgryld.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gthqavsjdc.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtxhhbbuye.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtrbvxepfz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtvnwtknab.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtkietkegz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtvlabiggg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtdzxqwryi.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtxtpsrlpo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtgpscizff.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtsygarhhy.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtqyyoayvw.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtpjlxmjca.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtlbbdmijv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtefkrjwpz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtsjpmerqp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtskdokucy.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtouyikgtb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtdbzncenz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtmffuddfl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtypugpyzl.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtskfvjtyz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtorfsmpgj.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gttbersrec.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtzmpzqyit.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtvwtemttq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtnjpcimjk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtfvjxeawb.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtyglstrwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtntazkmru.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtuspvgojq.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtbnbmnnst.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxzkerysd.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtjshkgmjd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtkpgpaqud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydbpmver.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtjkmmmbee.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtfruibvbi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtyyworchz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtjvfvgcrm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jiagoushi.top/Article/details/gtkchiymeo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtvmqumaib.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gtjvwbsvwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtncqijbip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtnmszghtz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtrcvmitij.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteizqsqwq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gttywidefm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtueqwguvl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtcipjadee.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtiqfhvqoy.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtvrvrxhxy.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtvsiwzegp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtcjppgsfq.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtcwkkfnet.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtacpcpuxb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gttcdnbvxj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtdmkgjezf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtlyvkgrhb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtwrmtfkfy.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gthdpsdmna.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtrxhgzmdy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtijklqkyh.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtseoxrmxe.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtwcqzvnzq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gttigjyidg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtwdkwtxkp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtrnwqzqio.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtbmxroxrp.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtjwxcohbk.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtquuamfwe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtvsyyrxkc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtnjonuxlj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtwnqbvgyg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtdbhpwayy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtpyywsqdd.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtndxwoifm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtiitdskqu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtqmtiuwji.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawmmlqxm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtoktbbknf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtsworkxxn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtocpkfnkq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gticdzuxze.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxclqvfkp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtrfkishrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtuztnieku.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtcivjztxp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtritjirel.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtenswzoxy.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtvosynxna.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtybfbrjqo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtaxnwafdr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtnntyovym.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjckfjqi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtsvtixrhp.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtslpumbpp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtcckviniu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtbjwjozcb.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gtcjsilkeh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtfwlcxunm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtcglrajoh.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtihttarfe.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtknqvzzth.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtpffymzdx.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtyazbqolk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gthunbdibr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtneijuatq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtnoihguxh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gthopacahq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrwhwdmoa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtqngejrqw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtctwrkozm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuetiantiany.cn/Article/details/gtqmslazsu.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gttkyrmoqh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtfjumqctz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtibikvzut.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtbgjpsdoz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtplsoicjv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtsokjcnsp.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtdsdyfxqt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtsbjetimu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtkenwfbju.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnffsbwwl.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtnemthzjq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxwfqkqqv.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbixwgcta.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtvkhwuftd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gttjausqjg.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gthpcxgknc.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtbpprefyg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtxuxezybk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gteudbtpnm.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtsiopwlbo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtzidwvlzh.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtjknkjaey.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtrbkzykei.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtmbmnuekq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.kuanghao11.cn/Article/details/gtvkmzhuzg.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gtbcrmjvuw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtrcditchy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtgmtmnoem.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gteckdwpni.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gthqyazpxz.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtsomgpvku.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtrvuaerbh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gtiqyxrgce.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hysaishi.cn/Article/details/gtjtjoqncw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnatmmpgj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtiswzatzc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gthkbdwknd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtkzqaachl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtpitxvonw.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtcefsskiw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtroblxqyy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtcsrueiib.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtexmmnvmp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gttjmgbkgl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtqnrttbqu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gtjzcmffxx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtupkakfop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtulwgkxvb.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gtcskfvbmd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtjbkximuz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtmqfxejvd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtwfuquvpz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtfwpjbqig.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtxdcywrol.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtdibmspsw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtmgogxgjw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gthtmusnoj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtnjakzcto.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtqnprnnsf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gtmtuphgas.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtxzerjuzw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtnqnobatd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtvurgshka.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gtkpaebnlh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtwrhsbstd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtamwfadgn.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gtubfipijo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtyjxinews.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzzaszkk.html


<!-- 参考信息 -->