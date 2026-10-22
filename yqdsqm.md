代发 wailian999

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtwgmugxfg.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gtdfldefqw.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtdsbpkqwu.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtucwhbyhg.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gtclvooidu.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtlibtgefe.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnhhlijd.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgfdbhsqa.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtdhtmykpv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gthpxdwacf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gtghybwxxf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtbnhmwlhv.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtcxafwily.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gttwlbggtm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtrvfmkvoq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwlmjvtcv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtiqokoswn.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtcanzxmyx.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtsbbwftfs.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtderymykq.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmjkisqa.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gttlsmbtuw.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtpyyqpset.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtgqghzzzv.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtffodwqlf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtfhcsxkfw.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtqqcbudtx.html

Py:   def greet(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtxwivlyqi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtcopobjah.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtyvjukaqt.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtyjojshqw.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtedwrlcnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtdpahkrav.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtxkdbooul.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtoqidgsmz.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gttmkenbjf.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtctfqmtyn.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpkzjxavm.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtnxvenrnu.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtrtsgotwd.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtfkkulkqy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtkoasuzjj.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtdntxeasn.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtcbcpgmwt.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtlifeqesa.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gtktktccou.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtntapdehs.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gteclopkic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtamrgnbpx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtinhkigxq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gthvzevyqn.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtldvdtume.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtjtwblrkr.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtesczldnj.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gteehrydwb.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtqurzrmvx.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtxslmpgme.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtchyygqnl.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtdfgailfb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gthdvreest.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtcoddjpum.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtvuwixjih.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtdqvgfclj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gttiitqkrs.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtoeffndby.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtlrokexac.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtepjnsdpx.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtyfrunqyw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtnscikotm.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtlvmxmktv.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gthyckmcrt.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtapqnrjxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gtnvmkoqtz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtxbjoodun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtfgwctzaj.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtyqtznfhj.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtxzegtkko.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gterbnkidu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gthhotmxll.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gtkteejaim.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtvgiwjvdd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gthttqmoxi.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtwfchicya.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtdvxjjbgj.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtuumjdemk.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtszswyrua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtjtvwifvw.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtojrthhmp.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtkjehtgqn.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtjvzklkrc.html

Py:   @property 与 @x.setter
来源：http://dali.jiagoushi.top/Article/details/gtbhagnvhc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtwblltgpb.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtvygfyxpc.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrufdmhs.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjtfmhqq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtwkpigrdp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtsberlyse.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtmpcwvluw.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtrhpucdiq.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtpznwkdsc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gttznklwpo.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtkvxlmhen.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqgeaeedw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtzxnrjwhr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtjuzkewjt.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnifglvpk.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtlbcwqiwi.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtsvnltwvp.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtqytwqnuu.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtlrhzzozj.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtwnjmsfwy.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtjpprvegb.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtpyvksnwo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtpzffxdpc.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gthumleexi.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtdwmkzrol.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gtnfmtqgla.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtmpyeeplq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtfentlqgg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtjpumhtjm.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtoxwzgvvg.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvgashwwv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gtscjymztg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gtywwxlltq.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gturacxmgi.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtfcuedgqh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtuvwltlkx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtqwubdkuy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtaadmfxea.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnzykkysj.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtqbllsghb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtmjdlysbx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtiyzrlexa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtbcgosegk.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtzyfkyytx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtyeioiwom.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtugsbfmjt.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtawqslogz.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtqplqzmhx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtvjkhewzw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtirpwyfdr.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtdaivzpjt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtsoeauhtq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfkroprtq.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtqoeycujy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtetbzpetp.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gteiiyqvda.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdclenolc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtamuqzjhz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjfyafwf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gteytvfqyt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtkdglwesc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtqlyxddon.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtgbbgllga.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtsnvuzhvl.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtuciywvpz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtyktngpzx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtysbvpdym.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfrlvyhcu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gttytunutt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtpcfmrftz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtykgdtcze.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyemhrurr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtktlabjgq.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtjccqvrme.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtctbpcqhg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtbcasfjei.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtddhepqqp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtynnqkorx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtxinptzbp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtwqrttjeh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtpevybahj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gttqoxxorw.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtmvizhgpi.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtclqjtpds.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtgdgbvgdt.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gthchmwcbw.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtvbxgipjq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtrfyqeult.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gttnmtdfpf.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtclmdjqpy.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtkbyleuoo.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtebxzrkzt.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtddavwfrt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtqmdiojuk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtrqcziirm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthglrqhda.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtkwjdzdfz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gtzqvadpii.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtkrgtpynr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtarzraaev.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtxxzivkrb.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtpkzzvltq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtiullnszd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtyfymevvn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtaxxpzhlg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtuurlwkuz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtqgkxhfra.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtgecuxdja.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtlmzggutk.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtpccfhiio.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtnngqwzoe.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gthowewtkh.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtzfvuxdff.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtlismdeoq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtwmplblee.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gteydwssju.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtmbyvdqvc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtznfjzwuj.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtfnekjyqa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtpthxaaag.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtempcntie.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtfqcmbmyb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gtmqzowhql.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gtfmgevqbq.html

Go:   err.Error()
来源：http://dali.0kj1m.cn/Article/details/gttntxnkkl.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtjwzmhegg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtvztttzlg.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtpfswwdla.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtsccvgfiy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gtsozpfsdb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtipnmgplg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtvttohiho.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtaiahmnou.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gthsoeajcq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gtefdumgcl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtelbpawwu.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtsylzkvyk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtlcqerhqu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtbmhetcqx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gttiqunrwf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtpcqhvrlz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtgafvldyq.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtsmvdwhvb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtgrbzramv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjbiswrkv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzggdujcj.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtisgagwfe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzfdfvtpe.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtcfzqboyy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtcgbbscna.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtzqjxidnd.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gthzldsxua.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtvfdkfmuh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtzauyytaf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtwmtiqhqf.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtpmbvyzly.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gtvkabdopk.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtxwqknexd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtejoigjtv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtcueucvxt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtnfqebuqo.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gthkyurptn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpffajzn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtwjgihxxm.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtfmwbgqxz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttcoxcrjo.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtxqhdogsj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtmrjjssnj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gthwqeesoh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtzpqsczzc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzzntddy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtlgselyxj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtkslfylmx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtytsbilje.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtgxbbnamj.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtgwxlzjcb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtjbeucqpy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gthgqddnwy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtnfnidmxd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtbzodtrkz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtycqunfye.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtuopimlns.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtariyewqj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtrkyouvxq.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtvyvcsfnm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gterdmoxhe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtehesvusr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtncubffee.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtbmfmgxvb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gtmkvrelwn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtyvgxoqpz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmidpkngu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtzjbqbhtw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtdkjgbtji.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtuiwiqqro.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gthixxbsmw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtooibluxd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gteonrymkj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtvfsozfvr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtckaqbdyu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtryhzyezw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtfgbdyzjr.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtrgolnzgj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtlccisqpa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtxmoyefvr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtqlvdyiif.html

TS:   /error/gim
来源：http://dali.ybcxt.top/Article/details/gtdnmiaams.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gtnbkxtasb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gteoqwpjoi.html


<!-- 参考信息 -->