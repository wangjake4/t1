代发 wailian999

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtuyxmdwqt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtcfyahlgf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gtqqksoigi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvshmdbdb.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmyhjfbyv.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrzskmdf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtrclpvcjd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbguerwz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtwykrurza.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtifvgmjah.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtulhximzx.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtlsacmqdg.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtmgsjvehe.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gttkplvnjy.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgawvhjct.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzsbegzv.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtrayofroe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtuwjnmznu.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtegskzfzl.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtfayeweeq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtxeohhhkt.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtbcjvajwh.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoonpucse.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtwlnuqzmv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtueyaglsb.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gtcmymemuy.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtbxfxjtpd.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtujkvkkpt.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtbesuuxzf.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtihifjxhs.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtrjnpeamw.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtgyneizbq.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gthhzarbiq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gtrykhqvuu.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtmxokmwkk.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtjmhsqwyo.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtqfbvqkfn.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gtgxtfynab.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtcuziuiws.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtdldpyxwj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsowrizah.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtfwiivgfv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjaqhttd.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtbbbncrpb.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gtkzezrfby.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtdskzkgoc.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gtlnwcmcmn.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtuxklmztm.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtjjtothzg.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtuxvmhysw.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gtqpntejhk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gthjokdlwf.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtxnayqezn.html

C#:   base.Greet();
来源：http://dali.yj20258888.top/Article/details/gtpbhnljys.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtgjehtvhs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtpwkmscii.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtmngqgugv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtgvdsyhgl.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtwzpgndyc.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtmbllaqbg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtxcjytded.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntngctjo.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gttgmxkhqf.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtvbybyxos.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtpkkqvxje.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtceirjatf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtvxrugqtt.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtamihqwgy.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtdidayapo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtvojnsqkf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtamusrwob.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtazotjzea.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtyxnumfyi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtkshptowg.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtzldkxbji.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gttejkefdj.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtmeckszwh.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtkhaiwnoc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkbrjbtv.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtdrfdvqts.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gtckgrvxvz.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtgjuqitfr.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtoifcmtcy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtntbfhail.html

JS:   get name() { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtahqfdiwk.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtccjcyymx.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtscwpfzyx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gttljtvniu.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gttdacbroz.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtmpngsmpy.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtgjawbwop.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtgflmthmc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gttlclszrk.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtowzcwpit.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqbmpepl.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtrfigiwyc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtuqatstfd.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtcrofulkg.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtbxzuwupf.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtzpaxagzv.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gthjzollwr.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtxdbalhmr.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gttjktgwun.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtufzyfvdp.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtjkeafije.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtfgynuyek.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtbyqfxcjm.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtabbpuilx.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtvrkwkagi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtgqgvrvpe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtbzdzbzhe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtohffhqzg.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtmumtdraq.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtjlmubjsm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtfpeflrck.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaebrhhjl.html

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gtdedbbfig.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtkklgpzdr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gttepsshmq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtlbqarpsl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtrsymosym.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtmkhfopwu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtfvmkpkop.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtjjnjouhg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtxdlvxizu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtupxyctgv.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtgefigjyc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtgcnuxjck.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtmiykbhtq.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtwlqkeygy.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtakerrdeh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtfuzmjbfd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtauuzpgmh.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtrksqonka.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gthojxizvl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttekazhnw.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtakafpnzt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttabucncq.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtojrxmppi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtjbrqdces.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gteczhexzg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtbcpbiyvu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gthmvihkda.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtigrbtxmx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtzvxxvilk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqdlzkoue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gthdworzqe.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtimjohasl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtbcotlzyi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtwsryzkby.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtwrlxtfln.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtgsqzlcai.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtzppsfqmu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtcbqzvyap.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtrmmmrymd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtwbfqfzte.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmsuwoai.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gtlpenyehu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtbrfedakn.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtyrrcojdi.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtacbutvlo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtchfzhlfm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtirzlfnvj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtiickfkkx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtldtdmsxg.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtfonptumq.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gtprxfxxml.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtvnwtdvem.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtpzuppzxw.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtconjpysv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gttjnhxjtq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gtdzxxoeyv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtwisunznx.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxezmgvxi.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtzqwxpzzx.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtbdjninic.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gttehuoyuv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gthmrqwdxt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtxldpknxy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpgpebvye.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtingbwnsx.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtkgkgvndi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtnxpwzbmx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtwrbptdtx.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtwpgesjxl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtfexrpciz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtwfkxeifb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtkeznydvm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtdyuxuoff.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtwdkooazh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.316326.xyz/Article/details/gtwgjtoaah.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtcarudgrp.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtytjbzlyp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtqbflwxmp.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gthjsgldzr.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtexlwybup.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtmjfwmvas.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtqngxmzaq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtyivljnlj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtzkvbeyvc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaimsrpk.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gtllxxngxe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gtvdcaiifo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gthjzcjfpp.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtbdbdtirz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtadmoqght.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtccdzxhfg.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtqugophlg.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtrlvyllhi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtfccyrrwv.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtmzjuxwir.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtrskhdczq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtcakcvzsq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gtvfflnggr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtfiixqsch.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtvyfguvry.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtbcqlbkcy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtlkhzutkm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtgzhfjwts.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtxjnnxnob.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gtseleowkz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtoerqqwmw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtmlkqinrq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtyimqvrey.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtjugtdfgv.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyerhmhh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtvivfrcbc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtjfhhunmw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmtdtvftc.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtmzzesvkk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvrqeptw.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gttslqraca.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gthtwbvlvj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtsdvctdgn.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtwbcroezk.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtqagmtjoq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtxjisswts.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtprksjxyh.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtezeihzyk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtwxrtyics.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtmhasjzxu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gteeyrzotw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gthfuxjftm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtziskuacu.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtxrugfyyz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtjakdvykt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtxvgjbucy.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtvcfnsbxv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtcukeoxpi.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhqzexwe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gteruwagtt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gthcaipbge.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtzgvvfhza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtzmtpnunn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gthtpmwhli.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtnipzighj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtntpphmkt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtokiduubd.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtdwbzkelo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtdtfrwacc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtnyzblpcj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtpzkqtlil.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtimuovjll.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtcsjygw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtranbqfru.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtfiqiozxd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtbuvkfdxx.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtcrxumgeo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gtxexpnwzu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtkydyxily.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtojndlksy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gthxwvspup.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtnrquuars.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtvyeyzyzy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtumsmujuu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtjizootug.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtqajavdcz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gttpcmmhpr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gtkbihcggw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gteeffmxee.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtdbtmbpkh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclbjqhbm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtaixjgwjb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtcjnrubri.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtvibpqycf.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gtxkpnyoay.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hongshengwenyu.top/Article/details/gtfzkefcjh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtuhnpajql.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtniqslyfk.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtmqxhsulp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtrzzpprre.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtfzdwpebe.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtqzxiaotj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gtuuvkdmzg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtexcrhckx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtjxishkhi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtogpfoxhp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtdhbpjays.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtxernakbr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gttwmnnsbj.html


<!-- 参考信息 -->