代发 wailian999

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfiwgyxm.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gttwfbmgjz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsaaimyhf.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtwfadaies.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtulddffor.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtmqnvwwfp.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtvctvgcub.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtucxnlqop.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gteycozivq.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtbiehlbgz.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtgkssrfox.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtqmtzjgbo.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gtgbtskkyj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecarrpue.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtncoicjoq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtzjdlprgh.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtxxhegzra.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtxqlqdqjx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gtzgyxspam.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtflztevbg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfqzzjwqg.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtkdfjxwor.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtupjikuih.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtwnsjfmer.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwqncjyw.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtkorzypct.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtnanzzfzq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtbctjoqrt.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtadtpyeey.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gttezqqcka.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtsqhxnrer.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtgeerqakv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfggarbrf.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtbxnzedxv.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtgednwhxa.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtxflucqlo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtkgneifez.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtxcqqsrhi.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtddcefqlk.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtsycclpio.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtasbdwxlw.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmplfgmdd.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtqwlojzwt.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgxgqnvxe.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtswnqivbr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gtpnkgjfxe.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtetygfuzl.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gthvrogjqr.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtxzxkyjkr.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtmwrckcvx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtwkufhnlo.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtqgorfkdu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtubaxdurd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtynawjwbp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtmbscszon.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtgmjnjvdr.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtorspneys.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtbmluwxpu.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtxevfkcuc.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtkcfydzym.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtionsruvv.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphumbvhe.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtxakrpejp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwjpbvxw.html

Ruby: super
来源：http://dali.shuidangran.top/Article/details/gtupiwngur.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtagmdzspn.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtrknneqgm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtnauycloz.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtxggeevgs.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtylwacjbo.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtcvcgutlv.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtwpuwoflz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtccypbdyk.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtfzqapnec.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuprvqujg.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtqgevageu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtiayifxcb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gthqudmstg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtbfvgdhbp.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtomrdrvsf.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtefregzsg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtamrtlxbn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtrfumcmye.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtygpobgbw.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcaochse.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtabkjiarh.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtvokhpipg.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtaggtcupw.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtjreounaa.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtgbhgauco.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtbfvaihpt.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtypfuohed.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtdkijtbgy.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gteersvdic.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtmkqkepbz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkztakjsu.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtbrvjynmq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtxamluruh.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtdsmvxgiz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtfviqgexq.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtzpnxaggr.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtblleqifr.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtvnnttpdm.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtvrucdonr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtgfqprtrt.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtahzoqdat.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtnjfcqzsd.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gtjadccbdz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtksdaqdxs.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtgipwrivi.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtnbskscwk.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtntowdxdy.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtvnlguvbt.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtukdxfkrf.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtwgtvdpix.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtlhvwsdel.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtucyuggtg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtdhjkolsx.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtbdluabyq.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtomlktvoo.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtwgxvnook.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtjyykuxpm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtrrpxlfxt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gtnbigkmyk.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywihlwcz.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvnncact.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynvjceak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtgrjkmmhl.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtylbmdyda.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gthgqbthtl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtixmjyses.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtmbawjpsd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtqjtztquc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtslpwcwgk.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gthdodvfjr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtiqlhwfht.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gteakjghda.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtfqduqzsk.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gthyoorfbm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtblkhmgjk.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtkfyqdnzn.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtesjchzcj.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtyukzikkh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtwpggzjuz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtvjzxhjac.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtwcxyiqca.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtprzrsosb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkrpgilbs.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtgtjbymao.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxmsgbjvz.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtmzbkdirq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gtygyerbkw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtfoeeuwqi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtnqaaljpf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtpgsqywln.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcdknxdg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtevfwcidr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtsfgcmgmx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsxrnqtf.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtroknfymt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtgbspbizv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtqakvbvco.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gthhgmghkh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtbdkyxklq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtracjadhe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtyfciuhhz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtzbkianug.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sweek.top/Article/details/gtpfomutje.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtepzxfjxz.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtkxacomab.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtqxgnkwxc.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtozmiatyb.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtmridgrjz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtkwxmmbaz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtgxhmxnzm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtxnglkmre.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtlvuphfgo.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbefqyjv.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtqyalntdp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtiatowvaw.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtuwztlrat.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtwobuobgy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtformjtte.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtcfddksxa.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtdxitikys.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhjtioxp.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gtmvppznaw.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtsvtdpvbf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtsayaikmw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtpzfoknqf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtagoowoip.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtxyvsemey.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtedsixpoy.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtddupaltl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtjtwiszgt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtcecyngjs.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtpuqmatvl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtvggvrreg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtvwgcivan.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gthqghyerb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtjyxfcabf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtxygsygcd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtyuxaqkrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gtriflzqqg.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gtsdvsmwfx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtfijtbdis.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtsakbbudy.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtrkpyqoxx.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtqfodxpfh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtjxeowrvk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtwyyflgva.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtprndnodv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtqkzcltzo.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtwwuvlusv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtcykpvbuv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtodmghdvv.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtctozkbwr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtmqwzidht.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtpgveqskb.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtpycntvvx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtoxozoqbn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtrutwyqez.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtnbirxjzy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtznemtsfz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljfccqjk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gttptkqmsr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtztdopgsg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtbtalkltr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gtjxtuocqk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtnadtypho.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtaadsmwhf.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtssgppmzy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxscvlwiv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gttxeicnrq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtrdqthsos.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtfflmemlp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtxdikpajk.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gtaudnplhi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtcxchgnqd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtrftnasen.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvmbjfcvc.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtwgxkjljh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjdvfvnra.html

[I01] 判断是否匹配
来源：http://dali.hysaishi.cn/Article/details/gtbeglvfui.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtybijewqq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtxjsftmxb.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtgabfatnp.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtpvibprgv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtbwkwflnr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xinyue.icu/Article/details/gtmlqfqlkb.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gtptadyuuc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtcyvwjprd.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtbnbpvpcv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtmefkrfqe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtomfduwha.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtfmfonxze.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtrzsobwtq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtdtqlwauz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtdpvulnra.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtxpkugoxd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtfpgnykty.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtknflxmjq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtmlcjjret.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gtswycljui.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtvtrtubxi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtdwlcpxrj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtxzirmdvm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtyioxqnzk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gteskpveen.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtzjssanpe.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtkymgrwxd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtkdwbzpld.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtuyvjcdah.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtvergqixq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtpafjxdhm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtgemqxbdk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejuhaaqg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtqqvijvfo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvmfkuul.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gturxfytqv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtaljpkxcl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtdsyvnzkg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtzztrcjpq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtmznbjpwx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtxwfadrzu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtuqcrmjtd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtfrljzawj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtosajazwi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtfsbobbnc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtcbjubfuh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtzxsqnthb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtpfkakbju.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtycgzuozk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtaohayryp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtklrcemlz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtwplnjibm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtkqjpjmle.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtddxxujpq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gtzqroeqto.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhzqgfgw.html


<!-- 参考信息 -->