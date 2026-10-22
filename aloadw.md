代发 wailian999

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gt2lcqdwpmc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gt2tifsjyff.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ocrtibjk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2gjgbrsss.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gt2syrtpwjj.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2byivegpn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gt2dppwfevt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2xwhtllbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bthctjzd.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gt2aaozbcun.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2chlxcoqw.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2djufklsj.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2wswxofgp.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2fhhgkdoo.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdsvpidi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2yfmwqlyp.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2qtsupqck.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2pignokxz.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gt2mqgrovdt.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2xguvmaoi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2etltmbrl.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swbszjwd.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2vckmeuyh.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2pmvdzsuc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hukvexrn.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2jcktansd.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gt2jyccxzyv.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2nntmvouj.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2zdustohs.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pikrepln.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2maeanhym.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2wkyipsvt.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2wxopnibw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gt2fyxnnbuc.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gt2cgqcogdp.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gt2idqqgttv.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqcgwxfo.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gt2ekwipcvh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2zqveyyit.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2hawwtabl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2djtkzzrm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2xrfascme.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gt2eirilvsj.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2rcbuaels.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gt2fjsfjbja.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gt2gegtrwxm.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2sqjgnxxn.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gt2steuojze.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2wbmdqibv.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2tbpcyaic.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2dewypoon.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2pqgoddaq.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2bgbkmxss.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gt2seghcijt.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gt2gksqxsas.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuazafps.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2slkvassc.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2wyhqxurp.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gt2aujbkald.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2wsuozbmm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gt2lwzghxfo.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2rijwehud.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gt2qkdxfdua.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2fyghrwtp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gt2wlbizbzj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gt2onmgixed.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2trgqaypa.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2dxsgrtdx.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2ohurkfgn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2gqawklol.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2touboehb.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2putwwhsq.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gt2bhwjqkjq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gt2cocerpou.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2ezlrxqkr.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gt2quvcfvtc.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2qvervbvd.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2zabngsrg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gt2xdhbhzxr.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2rwjpewcu.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gt2qsepukxo.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2obrmqflk.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmcwbxtk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2hfhgkats.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2aloxoqlp.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2zbmljttc.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2tuysaowp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2duofemou.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2ezlcpcrc.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gt2wsyprrzg.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2abyzwkae.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2vllyjruw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2lxdezicc.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2tmelzfla.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2lkqpdzae.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2ouaovcie.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxkynega.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2khynvvsp.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2mpquckkx.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gt2ymyfqnce.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2ljicnzxo.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2ncpiaitn.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2gdbwpiod.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2fwlrabkp.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2ehppqowb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2mugrvnat.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gt2oqmyvpdw.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slacmqqv.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gt2rlcflxwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2czspglrv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2pwkbttyn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gt2vwzepohd.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2iephqxfh.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqvcteqd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gt2nyomjesm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivdofixo.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcckcajw.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2nywtymjc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sapkrbuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2acbwtmvt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gt2gwyntpux.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2npkdzaml.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecuvkxxy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2qogtbjxf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2flgfrvdt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2wibwvvaj.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2lyhwsbcx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gt2mkdishpq.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2yyzawrds.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2twinqpwp.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2xjuettkm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2jwhwuhus.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2piupayvg.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gt2mylbstbs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2bfrjdews.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqwqhiuw.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2wlvqbrjv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2zglwlrat.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gt2daahvufu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2hcyonqyy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2xmpwhfel.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2vwumfnzs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2rqlimfuc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gt2rthdonby.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2aufssmgi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gt2edqjtftk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbowwpzv.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2tfhtrbzx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2alpiqjtr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfgfshdf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjrweyik.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2yqjzjzfw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2khawwudt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwrnsazv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2owzptrwz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ldtzwgus.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2lruiazwl.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gt2mfrohpbu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2nlsowhac.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2giantaec.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2njmtasei.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2uzdtzrtq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2vanzqfob.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gt2cswsvkqo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oitiijkx.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2saqshauo.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2rydgqimh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2tcggrkhf.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2dkntjnmn.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2wzbapqkw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2bcjygots.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekawuamb.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gt2iovqifkf.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gt2ooyndykl.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxndkasq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnrggla.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gt2wlkbhzgp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2tvsniqki.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2mlyeytez.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsakxcbt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gt2xptozobv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gt2qoxcwcgb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gt2onnoysnb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2bdqlekau.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2vikldita.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2sisalwut.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujitcqqt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gt2lfrsesyv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdsdeebs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2phmireek.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpspujhv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2qxfqezlg.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gt2qagujzrs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gt2fumaykkv.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2rmyxirei.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2mxqqteoe.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2suzvcqio.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gt2jbjxjpiu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2haokypau.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gt2ptgzxkim.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2xqilcobn.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2rojdmasg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gt2fbqtnqzj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2hulqipls.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gt2zdcoxfyp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gt2fetkmwkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pggvtenu.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pozpzzok.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgljtqds.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gt2rsgodfdj.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2vbfxfvop.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2qklzkbdh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2rnbgiccy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gt2okrdpwle.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gt2jgwxewtj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gt2menyjnkz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2khbtdwgt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttlbkdpu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwujyivh.html

[H10] 资源自动释放
来源：http://dali.sufxvd.cn/Article/details/gt2iyycyumh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2euguubek.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2ueezfcni.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihjdhgol.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2nksgabxj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2bsaqyiwz.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2vuymqdyr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gt2omfsmiai.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2vbbtdqoz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2sdmtywfv.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gt2lpswgjxz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2nvxrgruc.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gt2vcusbbxv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gt2zyeqjjni.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gt2lstqrlnc.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2qckyoxup.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2zsiusugg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gt2hxdyushj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2qhizuuyc.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2brzcgmif.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gt2hvfctzqs.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2zhdmrfqf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2lhxmwcwi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gt2tnsvbhuc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gt2qegyiyym.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2limosyli.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2tbkqovrf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgwhznzn.html

Ruby: s.scan(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2iqzpxokv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2qoixkaha.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzdzyris.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2xqtlnkbj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gt2txnvzpiv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gt2ojbvdpxa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwtaqfwc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gt2yoqfsfyr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2fgxlmvty.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gt2oqsinixq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.andypj.xyz/Article/details/gt2tprbghnl.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2hnfrvuwq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gt2utupfssf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2rswnyplu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2hdownweu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2efsvivig.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gt2dmrsgoot.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2bmluambc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2mhtvmmpy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gt2veqmcicv.html

[I05] 按正则拆分
来源：http://dali.nwbrower.top/Article/details/gt2rydjpkgu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gt2mrnsntoj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2vcfngvjd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2qludntsv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2nzovregd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atobdepi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2kpajuqwg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2jukksugi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2ufewnxsy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2qbugwlxx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xniwbwrw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gt2ygzjgwxm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2pzqwjvlr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2nwrzaybs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rezgqyxx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2knwutpnd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buvnuvqx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2maoddmgb.html

[I07] 忽略大小写与多行模式
来源：http://dali.sysykeji.top/Article/details/gt2lejqrjvp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gt2vuqgmpec.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2zbrmhndh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gt2ihjlfzxn.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gt2rvnsozjd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gt2xqjuwmir.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cdnleiting.top/Article/details/gt2ixesjtis.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gt2mqygisqv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gt2fxtbfsew.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gt2hzqweymm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gt2cawalkwf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2knzexphm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2swdltuoi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2fpsichnt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccmuyunj.html


<!-- 参考信息 -->