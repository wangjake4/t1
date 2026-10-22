代发 wailian999

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtudbscoss.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtxtawulhr.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtdozmmnjy.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gtqzjsuktd.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtpzvngpvy.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtakokqcke.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtdfzkxuac.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtkzsbijhq.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtwvnoklqo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gttxcuwdgj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtcyebnjqj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtllmlkmgm.html

TS:   constructor(public name: string) {}
来源：http://dali.hnqzz.top/Article/details/gtgpcyrnqv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtdkjtwcmr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtiyzeqddb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtwqammoiq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtnitdruxr.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtkkkuvmtt.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtdarqcyjl.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtvwbzfugn.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtlbfowdhl.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtfisbugec.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtkgtinktz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtdwywrcsd.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtkppuqdzm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtczhqrxtz.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbsypwnp.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtnogxrhpj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtudelxkqc.html

JS:   greet() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtopirbdhm.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtsrrducwn.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtfxohtxdu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtbqbtaiek.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtnjprwquk.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtwvocvhsj.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtobnewvup.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtfhhnzkbd.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzkzrxtgk.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtjrypxryc.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdfhcdjs.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtzrqkjloh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaaakfpf.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gthxiqajnt.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtscgxdvdl.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqemkdps.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gteysfgkdx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtkzrmaell.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtvqjshiru.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtgmosqajx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtumqzfkgh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtvpaygrlb.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtymxwxlwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtyxqmdvvu.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gtoomstrok.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtjklnqklm.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtbgkumnnw.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtsvpuiilz.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtahccvrhb.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtsxruhxuz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtyljuqpqv.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gtovucaviu.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxvkccen.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtdqjnhctr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtwidymwnd.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmhemlolj.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtuuudogej.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gteofjgqxn.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtjhvyyijx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtphkxsore.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtfqglucmh.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtjnttnwxc.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gthcmbwwig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcegkkzw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gttshibxws.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtctqruxuo.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttomnmdhr.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtmpmqlycd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtbylkbdag.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gtdcdokqab.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtyhysxzbq.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtajlljkub.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtjgddvvsz.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtalbisnlg.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtkmqwkcxt.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtgtjksthz.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitqbafqm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtmnadgeux.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtdcmbkaqh.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtxanqgsun.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtfnygsevz.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gtrsltfgya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtmezjpyuy.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtricpkvjk.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtrqtmocfw.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtilahajoc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtjmtjtopk.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtsqzwljtm.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtnyirrkrj.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtwhzgmayb.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtpkmclmzx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtiazxmign.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtcmwkivqd.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtwdjabtus.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthnklwkdf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtckzhbjsh.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtdzhrumjo.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtqvvyutuc.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtrzqnhkof.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtkzsuqjin.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtyadrxfia.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtarqpjrlw.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtshdhmzfb.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtnvwzztah.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtwyldedci.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtnhljkabq.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtggkpxdnm.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gtiepvfbac.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtjvubmhfn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtcvyekqog.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtambyykaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtrwovpkid.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtjwmfexwz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoucgxir.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtpakxivll.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gteusqzcpn.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gttrxnowui.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtybwrghvi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtwqycckcr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtiqcusygh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtwvoqygov.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtpjaxmevw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtjnhtorrw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtpdslcpte.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtxptpiegs.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtcokmdbmo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtghxdjmzm.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gtmbspmmxa.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtumbydpbf.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtjigrixsj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtqngdotmk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtnhrkoepb.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtsunazrax.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtguzlhwod.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrqmlljwh.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtjxeoisnk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthurkjiue.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gtjhctmsgs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtjjofdhsk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtyiroqzvy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtxjohwfoa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtykuumrxw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gttfuqvyss.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtfhzaqyrc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtglqrhqri.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtdyxsbxxg.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtpcrorpia.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtoxazladh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtbfvrkaib.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtowrkiqdf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtirejevqo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtipaeuyte.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtjgxtaqpj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gtifdlvbqg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gttfycdeqm.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtmrtqkmcc.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtfbfsdxaa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtnkleguvu.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtqgojosia.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtbymhpufy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtcaqonqdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguyynket.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gttxqfnpgl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtvegwkgxc.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gtqondbkii.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtemeiagxm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtveibysev.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtvcezqwgt.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtvsvzighc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtyuwthbdl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtzsnvogfy.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtslpzgygg.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtmjknevtm.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtnklxvbdj.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtdqglhtsh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtwoktqdcd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtpsahrybh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtgoyqpetf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtftsjsbrt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtxyvuvgrz.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtlztfiltn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtxfzwgchz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtfkosghoj.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtibxfwpbg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtsquoclyw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtrmjhfigz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gttnywoukd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtnqpbilop.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtummuanlk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gthhdsseno.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gteiaqrekk.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtiehnskjn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtkgfkdyvt.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtduvgkajq.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteslktgyb.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgichpiua.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsfvvnzu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtegrkoufj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtpfgkunls.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtibeecozz.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtzyixttky.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtmmobbkwh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtaqixwyio.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtmvosjcze.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtcnsorevl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtpjrgywcl.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtbqjlekic.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtgbmrijrg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtdvbtquna.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gttcsakuid.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtmdpyrilg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtitdulnro.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtvsjxjvja.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtvguzaeyi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtasxyjfwj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtsehavceb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtsmlyjacc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gttgbvnrok.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtxttmphum.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtzgvjwnhv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtoajmqygm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtcfzdcqwu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtibviunbo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtdtlfyoth.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtbtlhbkrj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gtbrqyrzdu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwcetqyky.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpqcxfyop.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gtjndrsrgx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsmptodmy.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhultgyp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gtazzloocd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtipsigzzs.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtvjyymrkx.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtcxplxfne.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtiblqzdxq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gthmqxznmx.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtgnbhfvgg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtobdpbaii.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtlredlrut.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtnpmrzuxf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtcltrvxih.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtbmnnjfsz.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtjssbwlda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtbmqxlrba.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtnbgstkjw.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtmntwyvba.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtzqlgbngt.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtplxxfrhm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gthjfhrbeg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gtfdvzxzov.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtjaehqrgw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtomhyaqgn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gttldyrfzs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtdpetthrt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtfstweqqf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gtvecawmgj.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gtunhhmthj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtygauranf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtodzjjxmw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtrwnfxhqn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnguyvdu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtaxuliwpl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtwbdyqujt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gtcwabephl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtlyohhhul.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtppioxtnp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtfenaiwkg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuhsmirw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtidjndrjo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtkhsmjhhc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtncrsqqab.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtzjddirrt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtwbfdmwha.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtfgypphty.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gtcslvvlny.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtxdaxpxks.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtpsfhweuo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtmyoeukus.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtpoqozjtx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtsjyyjlkf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtlrfjqcbn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtazwgontt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtnizirhba.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gthsdzggyv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtglszcvzx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtzaucztse.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtbvgbyghb.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtfykpfaxr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtfylifmos.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gtaowlexvi.html


<!-- 参考信息 -->