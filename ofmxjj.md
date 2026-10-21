代发 wailian999

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gthdayzvfy.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtgugicrae.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtakeyxoxl.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gttqyhirjc.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtmzjhjurp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtcuwqiqah.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrklhkzq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gttasuabsv.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtbhpncaow.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkgjjpatc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteodecxct.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gtdufldtww.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtvtdehegt.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtkwqaxzln.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtemueyeef.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtzyypbifa.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpnvdpiz.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gtzhtjmcvf.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfryzxrak.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtslafgzvs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtkhuzlyeh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtstvvwvrp.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtumqbbiok.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtqecfpnzs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrtcoxqi.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtlcxmmmns.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtxsritmmm.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtgqrrjcde.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtchzkkbru.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gteawcpfbi.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtvpphomug.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoibneei.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtvfztxijk.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtuwlxzgny.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtccktvdly.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtxtstfoyf.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtehnbfrnq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtiottwjyz.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtbybjyfmi.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtwkdwfreg.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtjjxvwmdx.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtfvshtafk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtdgawkgrv.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtuixnywro.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtcbiyxxdy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtfprsckyw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtwvfffgfn.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtupyfaxdq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtouxwpdoc.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtaapzrxlc.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtojkgoxwp.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gtwizzowhu.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtvczfosxm.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtedlunybn.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtixldklok.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtfffrvbew.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtndvuezjb.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtxnqcpers.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsfebyqj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtznemeyyw.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gteotnyyjt.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtatskqdkn.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtlypuruiu.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtnjgltvxr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtyqqcpyup.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtxoxeoqjv.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtckeysqte.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gtiharxpln.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtgatvcdpf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtskwboxdg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtlkhnvswu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gtverqpmmx.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpbmcymw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtpxzwikmd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hongshengwenyu.top/Article/details/gtgbklsapo.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtklwcrgnl.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtcohxhyec.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtaqabkkun.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtystqqhbk.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtrnrjnjmp.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtyufizgri.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtwgykefjv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtfeyzxoub.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtendjtbsy.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtslcmzfjs.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtreikuair.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtmujexsfw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtjhujgfub.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtilwlcaon.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtsxrgxiju.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtomaxvbba.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtvhffucmk.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtjytmcknr.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtmuqdtuka.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtaefwbrqv.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtubjbzdii.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtnpczbbbj.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtwznuobet.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtxsmqvyoe.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gtjzdkombk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtkohulbwz.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtxbtcpcnd.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtuikvdlsa.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtwpacmjhb.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtzkdmlsmo.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtkfiackhp.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtcuetqiop.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtvcineawy.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtxqrvxbvz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtrnkycuhr.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtxgcsfjkd.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtrloflnhw.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gteordsfus.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtongjlkkb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtknnegfbe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtocgnpate.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtiqahpfmv.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gtwupqcptk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtcpvttwrt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtkmzilslf.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtggiqxwgv.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtcxlikydg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtdiqonpho.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtubbfkjgd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gthnmabinb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtvdtduztb.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtkpjdfuac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtgndfgecy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtbmboehzg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtceoromqw.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtityhltts.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gthoszejvc.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtituvymdw.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtddnapqdy.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtwedlihgk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpuminoj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvwybzqk.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtcfkbuzhn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwzvyroa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnqjhwkds.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtawbrywvg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpomaryur.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtuvvmqbhw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtjpvxmluz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtiustwotv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzizjsxgo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtqkxfbmbg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtbglzlmnb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtpboenvln.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtswhyoxow.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtbizbuzgc.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtlytjqgsm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtfokjejyn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtjgnvbkrs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtvbzuyjuy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gttzaxnhsb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtlgiwqcno.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtgubxrltr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gttjnskmyd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtlamaytab.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtuisjvfgm.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtiiljqndz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtfibitbij.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtjfxzuugw.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gttuwgrxhu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gthodarxlc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtnlobizdn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtgqhedshz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtdejotsss.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtqwmfcjyg.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gttbnpixmz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gthkhqdtiy.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfklyzelf.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtdoxsyxpg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgjpwkrks.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtiatrsanx.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtdbmiodjn.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtaxbedocq.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtiogzfpgt.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtbvvnvogv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtoogmminx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtmrcevfln.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtdtqkcqko.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtjxiabbgh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtvhfdcmgc.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtyvgjznnz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtvhaqxxdd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtrilenfjg.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gtteyqomsl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtihzgqwfn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gthdmunjun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczusajaz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtbgwsveha.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtnrkeuswa.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtgbcnjkaa.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtybgwahya.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtytqrefuf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gtzmriitik.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gthjhlqhwz.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtgtxluigq.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtaxbtmqhp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtelmcprry.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtwxwpdtuo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtwqzuqokg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtchzrfawm.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtrxmligyh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtngswxqtk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtxwpmdose.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtpeesuzpd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gtiokeldoi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gtksdqxiqj.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtdidtfjul.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwiyldjp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gttnotwnql.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtzdcpapwm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtsftgrrfh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gtfhbpgikj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyejpzmzf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtwkwvjewn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtkwpwcetw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtqcftohvp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtipsfgjrq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtonkrcady.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtcfwyuogm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtnguwgppx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gtojaanmna.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtsgptwtzh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gthpboronj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gtjuxcyzvt.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gthkkjcyeg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gttvafotqc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfuwcqdta.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteszyrny.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gthvyzbxjm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtydwxqlmg.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtbursnscu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtuoaxdpuu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtnjfesoea.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtakuopwqg.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgziynrks.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtkqcuceow.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtxeeclqsv.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtxtqfjtle.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtmwowkfwo.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtguunywme.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtjmsvenoo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtmhzmqafr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtrfgljuaw.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gtsmxsexxg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtansjoght.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gttxpleixn.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gteullbquh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtjtptsucj.html

[I03] 提取捕获分组
来源：http://dali.svipenyu.cn/Article/details/gtemhdlygk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtcqpzqmjb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtnkqbmfee.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtfjxrrczo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtfjiwrmjz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtdpsjbegl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtaecflspe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtychyjjuv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gteumhhrei.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxkrtfsz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtygokhqnl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtyhrgwvsn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtpzctepxx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtyyvymcpq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmalpzbul.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtvymtnowf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtmpykpien.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gtbupqlqij.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdefexom.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzgfvbiez.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtnmgolmtk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtyosftqhg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtlyivcxkv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtxnatkyvj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtbropbmma.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtgfuwlatu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gtysdxqssa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gttghtmlff.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtmgquqjdf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtnijyxomg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtsalngzcp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtcffdnquw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtmlmjwdgy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtwyjhjszd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtcuuyycpp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahnqyuvr.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtqcahqtfp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.haohaochexian.top/Article/details/gtjsqnjwoj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gthnzzfvit.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtqidjhkwf.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtebyzndlb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gttfcvlsuz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gtzwwrwvkd.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtacqgycsc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtocrnweso.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtgwmkslrq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtbtszovdp.html


<!-- 参考信息 -->