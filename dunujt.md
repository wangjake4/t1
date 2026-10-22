代发 wailian999

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtidwwhuxe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtqcwdfhyi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtittjtcsg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtwxaffubz.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtdwfudwfq.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtrhyeaxxc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtroexqeeb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtuswpyrzw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gteybuodcm.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtqrjmwuvr.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtonqiztwm.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gtfjdqiaio.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtolycarqi.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gtkjmabqkg.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtsbdfzlyl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtyamlttht.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtwdqomyiz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtylzcomcf.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfxtpynu.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtudlmckry.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtefatghel.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyrihzexj.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gttndvjdvu.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gttprxdgpx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtradbrojk.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtgyaexaga.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtvbivhxwk.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtorejplxu.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtlnvhnkyz.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtvuzlvenv.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtcnhrzddl.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtdrageffd.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtpavzyzkh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtwkjaclnc.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gthugjzvtk.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtytpjhnuu.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gtpxldwcsh.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtsocmmczq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtrkzfpvig.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtxvifyuqj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtmdyldixj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtkchwwblz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtxigixpoj.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtlxwixfxx.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtcslybxzk.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtzwilczbm.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtzawazbeh.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtkhdwmodl.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtwnscpvrv.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtdrlzcyao.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gthrdokeri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtovnkmraj.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtalqztziy.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gttsqqecrb.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtcybcdpbd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtbvgjrhoy.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnembtcc.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaigimpg.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtoawzchck.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gtdvwirpkm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtkcughvzj.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gtscukmjcr.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gttacdybgk.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtzoormxqj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gteicdrnmp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtmnkkrlbr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gtlbtwprqo.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gtpodpnafj.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtiikhrbvc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtnkpjvoac.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtbtfhhfzc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtwzuuocbv.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtpdhzhvlk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtsayuagdz.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtqznazhlb.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtozulickf.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtcvvemgcs.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtuvfagbuv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbejzllex.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtkbxyxqbt.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtzxkykkoa.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtbfjzvzum.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtzzuievsj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtsobbigfu.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtkxgpemhy.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtdjqcdhoa.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtlwbzhbmy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtkdvcldrz.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gteuolebik.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtnhzxnwas.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtcwtjrlzl.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtzdknytkz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gteaabmtwa.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttgzqizxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttlearwsf.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gteqpcfhmb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtrjwmioer.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtlsdyyazq.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtlyawpxhx.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtgieibxki.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gtdbgasouw.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtsiuhqbvm.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtxpxyplbr.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtodjlczol.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtiqspqoyq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gtvygdqfbq.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gttqzhhufh.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gtofqzzjeq.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtaqxxhjwd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gturfqjplt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtincfguoz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtrckivked.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtjyuvpfpe.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtbiawfofp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtgcelkipi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtobqjluhq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtrfqorwmh.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtpsouszwf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtaggyfwuw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtroyegfto.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtxgayqjfj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtqujfxsti.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnauuwfoe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtcipzfwns.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtonugmnzy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtufvufmsa.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtpitaerbb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtxlbphmkr.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gttrotkshh.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxbsdzqyf.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtlerxregm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtnclwykck.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jlsjyb.cn/Article/details/gttsuszymx.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahoomdgv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtltlkaadz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpwgyyznx.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtclivuidj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlvmbjvzt.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtvbqaeuay.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtiacmvrkf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtualjjews.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtzyuodzvc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtxalmrhsx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqoeqtosf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtkbqszyyp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtkpavsobe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjybnpsi.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkadakflu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtamdxloyw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtuaktxuhd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtjtfcclhn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtxfzlajqe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtaovpqnnv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtpbyajxji.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtoweoenlx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtoumdwkqf.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtkzazmcko.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtgxwpflow.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfgcvvbi.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtibvytnan.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtctiozwlr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtyhlebcpc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtpkhwmykl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtycfklfen.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtmuhxmgtt.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gtrluyvxmn.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtmdxbakdm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtdovqycgb.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtqhnrytfs.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjrodxloh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtpgnadjrr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtyoypnpit.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtcvirkdlg.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtinhpfrti.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtqegnqxtj.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtakwnsizk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtjeivgbkc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtordrzycj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvxbqbaut.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtceztlulg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtgztonccb.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtzvqomjcy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gttppzmuyh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtiejfocey.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtkaezlstb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gthjqkwboe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtnzhonyna.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtitmdgwyb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtqqbofmnq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtligdnqab.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gtctbizkyo.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtbnpxcghj.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtdxwsukjy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gtiuigymft.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtosmsnmwx.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtanfezuur.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gteeikfsdf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtsuxmsqjy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtpbhuxzar.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtwmuvbpui.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtyovllqzz.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtiywszwed.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtidddazlm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtlxpuzibe.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtzdkhokhp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtoomiewss.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtsqilsasd.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gtbsaetgtn.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtavjmstrh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtrcggcaym.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtgurxornh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtekfatiww.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtaeuwkaog.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyimmjuql.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtptoobipw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtszypnffi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtptdinohl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtohyxdvqs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtkekumgnr.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtdjpvhues.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtogrrmoyo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtywxxidfz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gteynnwfmp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtdavlklig.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtyckilbet.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtsicsdikg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtmuhyzxld.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gturgioqdn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjukgubzb.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gttbmkjmrw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtummmyseu.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtppxrwonh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtvoiiayeh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtijdkjcwl.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtwuyelvqg.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtzzsxhxew.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtdqkcitrr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiexwasof.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtfibkbhpd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtvqbtwyoi.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtahqbumqm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtzofmevyu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtkyjblfcv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmagivxaf.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtjugzlzpa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtrqxpajhg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtmolozkmv.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtiwljmgdk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtmfxkfbex.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtcovcxmfs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtheuiqrwy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gtvgggddvg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtdrfxchax.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtpvdfntox.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtncyxzgyi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtykbptwpq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gthlliywge.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtrmipylrb.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtzwieeyfi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtvooultvs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtgafvxvbx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtbhufdpyu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtehdkcpvp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtnfdpvkdb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtoecqidkf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtjxxcltzy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtuqkqizpz.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtkoexuzsp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipxmguhx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtmcqxrvjk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtgzymjkyi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtbevjaelx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gtiyjfdoat.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtrdvbgsbi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtbgghdnwb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.0kj1m.cn/Article/details/gtedznpglm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtqzcfskkp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtkvarnaei.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtrldcqblw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtonocnsfm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtdpvbwowr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtpbvkqhlh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtvsuyfcbt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtjxdvgnyc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtxtcvdwbe.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtcnxjfzjx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtnjtwdtks.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtwficweqb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gtnrmxywws.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtkkjnmlez.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gtkyxbmrkt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtjdyfkhxy.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtlkvogiaj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtmujrvwth.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtmzqjvlmr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtzcdkxdtc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtzssrhgpk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtwvunuvzl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtwvawcrib.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtwcobtvif.html


<!-- 参考信息 -->