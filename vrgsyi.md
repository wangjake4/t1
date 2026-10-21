代发 wailian999

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtrsbqrhio.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtxllmiuzt.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtmcqpsajo.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtlvhbmucz.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtovbtinil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gthoecjaqz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtpfxgesms.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtjozxhuem.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtwvbyfzeo.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtsmvmppby.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtlwbhmdzm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtufyvoakd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtuinubrff.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtvatuoaks.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtljnffucb.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtyuansgue.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtnnrexkog.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtffyffqbz.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtzrqdewll.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtpkzaqyyg.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtsyvjcust.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtwlgppbti.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gtvekjknxg.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsfxjqyf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtfmucthny.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gttfwnmxcp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtssafjlby.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdfmruybv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtfzcvozkf.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtpnsoascl.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtngdfeqxn.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtdufzjgdh.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gtjbtwbpqs.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtvzplluwh.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gttiphoqii.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gttsigejuk.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtlhyvockk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtcllafrfp.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtfmbameis.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdufpgxrj.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtbwbwaypr.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtynkzzwrw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukmokaxx.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtjthtkbfr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtciwxoinq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtdowvfjwb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtkyjbkeht.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtvdbzcsaz.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtgxhkhdym.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtwwluiaba.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtcljzfovl.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtwmemjyjg.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtyoemtyco.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtlbzxqhed.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gthifjmqha.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtssdymnas.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtaotyufml.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gtdlmmynyy.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtlhokdpes.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtrzzzfnot.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtyzmlchml.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtmetszlvd.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtmwpygvup.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtkrrohuzi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gtofmlkhbz.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtpqrzyvap.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtxatdyfka.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gthgvyvhji.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gtcrkncpyp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtiainmeyo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtyjyihuxu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtrsosxwuy.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtkqsdwlzp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrbyvhpx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtthrvmldx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtkfpkzrlu.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtmhunlzek.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gtpompapme.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtdmooscpk.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtqrhhtrrv.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtfjuhabsw.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtqwkayuai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtwknoditz.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtppwdngap.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwrfhrws.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtofpasdug.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtvztomqpp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtbqpqzmcr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdlclntjs.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtoogpzixn.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gttsbmsjvt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxoeyuft.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gthtnzwgsv.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtidnbzfgt.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtfkjqldtc.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtebsgyuhr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtvxpwqttk.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtfzpbawwo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfajmcqfd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtxpdemqha.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtjyugtpda.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtgqiuyrft.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtwtmlmpej.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtrxncybky.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtmjtqpjkv.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtvkpjzpyb.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtvwvjexky.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gttleihdvn.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtanvhgctx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtiwfinglu.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtkcstxhzx.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtjpbaqduf.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtpzprsdvm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtwicxqldb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtpcdthhzg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtkfkhnlsc.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtmhdfpnsf.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtocvbogrw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtecpqtrct.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtgoctlfnb.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtssdaqahy.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtpzvsahwl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtsgkdbmei.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtgshapadr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtfooknifa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtjxupjgtx.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqavwrgi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtjskfmfft.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtewogxtug.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtdjefvddn.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtbwuxuezd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtvaxzsmmr.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtecvwuhua.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtdbxnqwmn.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvpvxcip.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtbchulfmj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtdrxsnjqa.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtuccnqlmd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtgjnxkcfp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtygpbmxfv.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtwujhejiy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttdbkyubx.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gtgqaoefgt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gthkcdwpmg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtypmrompo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtilnrhayy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtnlbmtiak.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gteiawkzos.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gtzockqzkf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtflotgvtu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gtalxqkwpo.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gtbwjpiiur.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtfysswxpo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtneqeplhf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtjrewybrf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtlxamnpbm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtjzeebcti.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtbdxqjvct.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtzlyouvcd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnqsrtzwq.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtocfupitr.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gtxozanpgc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtfymtopoa.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtgvtoirwy.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtzjabewmd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtvzpzjyip.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtqhpldnep.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtciosfthm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtshgxuluz.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtbgutkqoq.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtyqagmpsy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtirxrjivg.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtyiqcnsnz.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtzqssgpvk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbmwfrcrd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gtzqhsilnw.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtefbnfpbf.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtpzkiaamd.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydfgpxfs.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtitzplqoi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtntfykhvs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbhmkiflx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohhhnkst.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiavwzvkv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtoagrahhp.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtnorpijff.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtbahpwhun.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtyuratjad.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtysyedpip.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtaacgxlvf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtesmcjybn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtglbfgtkv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtizcrilov.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtdzvfsdxm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtcmpnhons.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtmwougwgb.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtbagzimow.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtxchesdsb.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtjlbntpci.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtucarshaf.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtfwvexftg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gthmrxcceq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtavhchyex.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtdsqmvijs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gteqvpuqun.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtcijlqibt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gteiibvrjh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gtpqwdbthp.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gtaccnqwjv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtfzepyotl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtcenejkiw.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gttodvloae.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtrjaakhgn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtawdpjtba.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gttxhkfdhx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtzxljymlx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtjkrhbwpl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtkitnpwwn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtnbcmboea.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtzcvfzrww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtyyfwrjih.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtufwevmov.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtqtkkibie.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtztaikbok.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtphckdebf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtsejorxeb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtbblpdouf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtrgyjlemr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtcyeptkdk.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtqcrbolqm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gtyjhjydas.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtoiuqheyp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtylkeaufx.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gtwfhttngs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxuztymfs.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtaoafrjgq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtzymrlqbe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtzppuknfi.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtbnywnpyr.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gthkvzrpcz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtczqdjejf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtwowdcftv.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtfazgpjts.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtnsyhxcuc.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtyahkwrxf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtjrtslwbx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtjaliafzg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gtbkxkedva.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtuvcpgqus.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtfjznruoc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtplxvhxmp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtctsirlhu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtyharffmr.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtrolireli.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gtzrbqlrex.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtxpudpfuq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtjvysxyni.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtzomcanpc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtngsklplw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.snrcjt.cn/Article/details/gttpgshubj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtvqogtlbc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gtliwemeil.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtzfppsogz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtlajkdmne.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtaoxevfsy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gthbcyigcq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtkkegrznb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtitxojesd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gtwzsbhykt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gtadqfcsqv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtedcigkts.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfieafdwk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gtptltiwuy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gthtrerjpe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtzlmmpiec.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtyyjvtjez.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtjudykbql.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtecdakcaz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtnycmmwbj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbngftwai.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtsavbnfwc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtmfirrhvy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gtpfyumryc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtuhevydvv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtxunxxafq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtknlzaujy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gttvjykyey.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtspfftnua.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtjwhilpcj.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtestwaceu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gthuyclryu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtffigxyla.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtsvoplrvt.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gthrwebksl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtczgqvebh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtasqpqine.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtmvnemgvq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtiasnoudp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtzbdecmwp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtczoatyjx.html


<!-- 参考信息 -->