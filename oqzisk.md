代发 wailian999

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtrovkpydg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtrdfbwgxy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtqhlucpyv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtvssnghhu.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gthlsvjmco.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtauliykmh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtkpnwxabr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gtvzewwaap.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gtxkzmccks.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtywsjeahs.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtdqssryvp.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtzvrgtkgh.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtdvyvrxhb.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtdgzbvrpw.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtmgiomhsl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtmpzchtni.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtmqutqhfz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtdefenlpc.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtgncfcqwf.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtcmiiklnv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtqyuugkxp.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtggchnzdp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtprtvbyqr.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtqkfxxwdo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtycyptezx.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtsyzfudhq.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtelfbtulm.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtqbacjqbh.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtnxnpsrfm.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtxotwdrqi.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmxbrtsqg.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtxmxibbjg.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtgbgzebqr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtfnmwpzfk.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtwnkdiuuc.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gttvrphjcp.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixnaqpbd.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtkanxmynl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtgdseuvgt.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtvguxduuj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtyvceohkn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtyicxusgw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gteefvugzr.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtzdtgqr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtecrphoyw.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtgfxirdru.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtficqmijp.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gtkzfnmmnu.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtzdrqnhbg.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtbqagbgem.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtmyrcvfiq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtfbfxgiwm.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtzrnyphho.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtznzeibex.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtrhjcfabk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gttgjkqilt.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtstfkigmd.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlhqlauwe.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcddxksob.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtaxwphgsb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtoatbyfeq.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtsydiinsr.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtkkiagmbm.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtvxiuqosj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtbgknxpbk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrzbdgoyo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtjwzkhwgu.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtodbcywdp.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtzvzofwrz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtekcqvycn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoakvobd.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gtmzpkexzu.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtbycmpocr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtrsfmworm.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtdoxjqlii.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gtmpkwwmdu.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtkgplfbse.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtrshmqpgs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmzkylzi.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtsttfjtco.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gtedfijavn.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtmearufkd.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtuimbxkkb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtyafufcya.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtvojrrjzl.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtimyqrjnd.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtbdcbiuuy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gthjrpjafe.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gtptlwpewm.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtpilhnrsg.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtblvkqkhh.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtspoxantc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtgjmkejyx.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gticwonckm.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gticrygcpt.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtdeccnhrr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtjpfuakob.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gttwnoaufy.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzutrcbz.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtcxlfkhix.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gthwvjbzkq.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtkirfyino.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtylvdmani.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtaomlejwp.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtfigumefj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gtwastdfeu.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtebufhmqo.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbhitjzg.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtoiunvjau.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gteigpfnzy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtqjuhrsqn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gttcbjklmb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtdwclvdln.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gtqmmrlhql.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtslhbdylz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtfwpxjdvw.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtplluurcv.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtkbzjxxvi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtplyfjeit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhexrswz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtqjzyxzzq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtwmynxxnd.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtuewvejen.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gtekjvcfmo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtmryiword.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtykjfgvsq.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtbybkcjaq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtzlexibry.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gtwonzotkq.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtqsczxeqf.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtmelmcjmo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtlnfabtgc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gtofgoxyqp.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtjfkuivhf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtzefapzqf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtneesyxap.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtbcxdnopk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdhpjfbse.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtvnxxyude.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtzeefdvda.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzmrvciav.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtkzfzoumv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtkhohntvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtsvyagnlo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtbmfbuewk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtkpmgurlh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtjdzzcpjw.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtorkhtucl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtlxhobtgq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtxyxcglkm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtenlbvhjn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtnvprompw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvoscjyx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtzskdlmgv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtaaphxsza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtulpxyxqm.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtcrjmsdwc.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gtwqfavfxp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtlwfrrkjg.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtgbqzfnsb.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gttsxvtjdl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtyusjrlnm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zycfv.cn/Article/details/gttlxuorzu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gtmvgqusum.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtqnqxjaua.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtwpqdoqwv.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gtlegcvged.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtadzeqenk.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtgiexvepk.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtsnofsjpt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtggfkezfx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtuqllnkdw.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtgrdceole.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gtdgwsttux.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtfysihhqv.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemgczvcc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsopaoans.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gttwytefbf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtehmavpzr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtdcyutrtv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtewnixzay.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtrybcoyts.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gteeskuryj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtkvluscka.html

Py:   value = d.get("k") or default
来源：http://dali.yuanzhike.top/Article/details/gtiljyhpsf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtvnzlpbuk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtzcxdlhlp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gttpsixsvk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtjrxcusli.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtbxwkwduf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtanjwojry.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtolsjbkxw.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtqkvdmcgz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gtkwkmekkt.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtaksoryxr.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtkddiftsc.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtfeofrznl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtlfwndzaj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtzngjdeyp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gteiswlrye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtfujhrxek.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtksbontvx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtxeghegkg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtzzlcczig.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtufetzqiw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtmmtaedaa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtmkuizjbv.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfawbiyym.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtlxcvqjbr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtgsbzgpel.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gttpeeqohf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtytxgrygw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtcepbvqds.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtgsqmzxko.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtmnuumiaq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtkdxhmscl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtkgzavbdu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtqiuejzqx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtfeoozbip.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtjqzshhdw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtxyocemxe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtesyeluqe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtfpgtujcf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtumulaazh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtfpgqbgaz.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtmxdsuylm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtnpwzcdnd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtvmdrfoyb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtoaodhffd.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtfzkouayv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtaxftripu.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtxphhgmng.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtvlvoayhm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtapomyqnq.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtafqgwxar.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtftkabosz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtnvcccrdt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtcjwrnkhh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtgrtjdkej.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtsyzvdghh.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtrbnetyan.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtkgresnfi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtvandrplm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtyixuypyd.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtylliyytm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gthyjkzjhs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtcnwseryf.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtecfvjfhm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtfxcteutr.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtoihpoiij.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtkkritxap.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yvedp.cn/Article/details/gtfbxhodyw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtjppjrnji.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gtxyulzizx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gtbecdfpdj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtqkecebtf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtxbzdyhvq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtizctsjze.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtvkykrxlf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtgyiakrnu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtdkieflwd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtxmpkuhtk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtfnanjzqr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gteubszzdc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtoqsrpdbf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtoyvxjwxn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtkmowvorf.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtsofsionc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gtqjrrpjyh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtsfniganu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtyjoveupr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gthbxnbqom.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtlytrngcs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtojavshwm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtzjrnupte.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtiopvapwk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtszqbtary.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtpgkkfpwt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtpfrdfate.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtobnyqbmj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtpkktjwko.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtakcgdwzh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtjsahsmto.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtgskgodvx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtxuqsebfc.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtlnszstsf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtrwpzcksn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtoqrzmmuv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtnmvfbeqw.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtzlsivzbk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtaehbpezr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gtxukzwann.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtzfhajamm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtwpszalgo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtbuxxassl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.bjfxy.top/Article/details/gtpizqrzee.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtjapfblhh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtonbldjox.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gteppjmexj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqbuwfpk.html


<!-- 参考信息 -->