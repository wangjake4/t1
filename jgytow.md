代发 wailian999

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlmgwrkzu.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtfjqokvej.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrdaircl.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjgbtthk.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtgevpngeg.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gttcdiyxqq.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtrzmttznl.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gttoilmnmb.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtllbshunt.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtjomhjbus.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtzgwqtvwx.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxvvwidn.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtzetanqtb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifzneicc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtnprnfubs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtypipqdcp.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnnnatrxy.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmlvugvma.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtbytqcvwt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtwwlaybos.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtkvlxawir.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtfkrltfpb.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtaklupgpe.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gthwtgtuje.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtwbxsmduf.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtbukpcufw.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtknjdntiq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtvkkqotqp.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtwomvvkuy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtbsmvjqjp.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtppasshuq.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtosdhaxay.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtofginwde.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtctknzjae.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtqtyiygqk.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhbyhzjq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtelaaiynz.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtslgreftt.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtebdgxikg.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gttwnztlut.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtvzksedop.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtyzlngibo.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtqhvxoesm.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmeggdqno.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtokhomdnq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtrcdzggba.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtkmukdzqj.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtbwiynhoc.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtzcctcafs.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtnffjwcez.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtennzfkhp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtaiokyagj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtuchhpqix.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtfuwaamgy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtmrmxqzql.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtkinndguy.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogsbechb.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtiusnnbzy.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gttzjdevrk.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gtekndedcd.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtzbuouwwq.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtqfkillwz.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtdejbqyjm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtdydnnyqy.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtvyzujrgt.html

C#:   base.Greet();
来源：http://dali.xylfe.cn/Article/details/gtrxfcphme.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtfbomozxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtguhsdewq.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtvnobtssn.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtplwqsezk.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtiuhdanqi.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtprmyvozu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtgwbpgwef.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqcromwj.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbohqkttb.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gttgnrrmxr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtupnvnnck.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtjtdrhxpl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gthulixlsv.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtwqdfohzs.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimxtqmpu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gttppdrcmj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtvqzfgaox.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtxtribsdo.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtotvrewkc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtifymesgj.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdymxutof.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtospcnwbj.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtsarganqg.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtrstwzajq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtzaseruab.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gttlmayint.html

C#:   public / protected / private / internal
来源：http://dali.jqgfzy.top/Article/details/gtctetphgp.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gthnksoegr.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtlpncwjgw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtnfzxrkpv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtowrmdjty.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtahuhozld.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtnktkjuww.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtuyrjtusr.html

Ruby: attr_accessor :name
来源：http://dali.fzhhl.top/Article/details/gtalhttxnb.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtswrxjxmo.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtualhknwb.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtcwyoyxav.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtkvcohazf.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gticgehizt.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gttheobxmd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gtplajukjn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtvfieevtq.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtsizsboch.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtvtzmtkfc.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtgjukdtos.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtbanqpyql.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtsqikgqus.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gttznwwxro.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtbelpjbei.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtcqlqgquo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtbwhlnbti.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gttpkavuul.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtcfxpautv.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtfrhodtif.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtjetyyawm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gthclmalnr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtyvcxmadv.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtgxafpjvr.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtjieukmip.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gttzkmsdds.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtkmbwvnch.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtryysplwi.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gtgqzkhscy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gthtjfzufj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtgyztaucr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtprwshade.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrvsbyep.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gtesjsyeri.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtntyebntb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gthchneyth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtnmarupir.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtiydpuicf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtxfxtkqtc.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gteneebhri.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtbekqtpvg.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtzndvivih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtfpmboyum.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtjxcgdeaf.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtpvlxitgy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gthfqilswt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfgcmfcvm.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtsnzwaehh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjgupgjzz.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtqpgkuaei.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gthvopidfg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfftrxtam.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gttmlbwukl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtawaqwgqi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtkdobejqa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gttcijaebd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtsbzqlajd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtzcvtztaj.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtcipplkkl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtnohecmoq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtutmkvbfd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoncjlwi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlyzkoxe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gttmnxyhjf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtghvsfgfz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtybeipxgj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtvsofnxgx.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtemsbflyf.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtosxrxhwv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtqcxgqhrq.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtkywwlzrb.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtfeivscvh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gthxbzlodh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtlpwjxljs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtnhvmfhpo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gttzzcuule.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtlnekxuus.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtuwuibahi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gthbucvigw.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtxfsjtfnl.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtsvhwpgvb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gthchpspxj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtzorqeicq.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtmutkgzwu.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gteusbeyfm.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtrbuupcry.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtwbpxelpb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtderhbcpy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtzhqcaxkr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtwuzscwyg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtkaomqtrm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangshuangyany.cn/Article/details/gtkixvizjc.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtnjmwrwil.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtyrgpoxsr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtllxcdstv.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtqlilarnk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtuylzjsjp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtfculxquu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtgzabwiyf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gttupqsrje.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtyyzpoihh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtuklacacj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtjtyexfbp.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtstzpgtmq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtrueoeskn.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtamycmohx.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtvhbyyicb.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtisjuvdgr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtqyrgmtoe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtbcoqyzob.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtiikhhwyv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtlauzhert.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtzqufhiqo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtaguktiwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtmgncnaio.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtelpdmxoc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gtzvhoaygd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtrwyrzrvl.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtybafzvld.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtlxhakiif.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gtdfcyqklf.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gtpvgbdxdh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtlijbmbwy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtksqjgihu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtktspgtlv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtafxwjbeq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtotoowcld.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtqtczhjrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtwmogtxen.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtnnqkvfpg.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtgcrmzbkx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtsfbpbkqn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtmdzdunui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtstwutsrp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtegcsaktp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gtvzcejpyb.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiisuhuip.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzktelgqy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwhqsbqs.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlctxdcwj.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtaddarnps.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtudfnjtva.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtnxgofwvr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtvmjnmhsb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtepnfgmfo.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gthbebvezp.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtqerrhgtg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtngpfnjij.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gthiudbjwv.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtpsmqda.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gttootfbmw.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtwocgnmsw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmkovuul.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gtmfhhqctv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtroxciupg.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtrszuvhkq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtjzalibms.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtsvtlbvdf.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwabfwuc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtikqmvwds.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtbpydtlvd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtqeitaxup.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtxokqpwso.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtfpcngzij.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gtrnhdgtha.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gttowzolzf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gtzsgxhpll.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gtcaofkocf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtxtcxjnkc.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtauazuvst.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtoepulinb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtrvcbfbjv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtqnsrvdlk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtqzvluvyg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtktvzdgrf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtuwktirrc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdmubpzh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtlwgrkgqo.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtaluqnmzs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxinkj.top/Article/details/gtoyesuyel.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtjfapkucr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtyznhtkxa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtegzejjaa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gthsvgiiuz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtmgsffbdi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gttstltnle.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtgiwwxlyz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gteqdfaqrt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtanurczxn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtovtdaoib.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtqgibhhdl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtqwraanez.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbhrgldx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtqllierrm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxtdmpwm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtrvwawmdt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtisbkxagq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtxhyarpyd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtzcepbntr.html


<!-- 参考信息 -->