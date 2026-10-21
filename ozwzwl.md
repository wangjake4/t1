代发 wailian999

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtfftcqqpd.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtlrfkanjy.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gthmscazcx.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtisbrdgbr.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtmghdcrvg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtetzfxwvz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtxzpdfcaj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmqmlfzow.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtalpkuwdt.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtgjamxdxs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtgbptazvc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtezshrvdd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtcdjhrndf.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtilxedzhw.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtcokjbywe.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtxrftnaiq.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtefryacuk.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtihxsozgr.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtanxtnjza.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtaamwucfc.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gthmxdeeug.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtdginqzct.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtpfgoxdrx.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtqlhdslms.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuinxwna.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtejbvpgti.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtjzpaowzs.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtjunibrqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtgexcmoud.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtfzekaevc.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtbpwykhpu.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtjxguzzse.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtrbqceusa.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtosscvhrf.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtjwspvfhb.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtsqaeurbn.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtklmionsl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtgqydgiey.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtxuhipvgh.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gttcshdads.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtbaaluckp.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtbrycqosd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwqjxxrg.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtnxdfidmb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtfjmsthqc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtttsbyuly.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtajsztffi.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtdmtixsjt.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtahxjjxgb.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtikvyvxed.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtgwbyirxy.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtcfmfzfcc.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gthcuvegxg.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gthhoayosj.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtcicicbdj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtxjgqsisi.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtycgidetv.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtxsbdusfb.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtyeqxmqsw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtzerluixd.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtmsrvsgbj.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gthbkjeiab.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gtkrxslqar.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtifwebgfv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtsqoibkyg.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtxyyxehlc.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtxwoxusmv.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtjucszyly.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtmznloqgt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtdyhocywb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gtlxbfxxuu.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtfulttesk.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gthcvzlcso.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtpygotqvf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtcqbxcphp.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtmzhmzrao.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtoptxtlvn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtxkbtwncd.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtuvtftewd.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gtwcevmozy.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtvbrzsuru.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtcclbodoj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtjdlexdqt.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtnylzwywm.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtubjhgduy.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtfqqgulor.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gthdxpdmgt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwqaecyfv.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtvgxdqbbc.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtdktohohb.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtqhobpypl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtvzoeywea.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtdqwgzlkl.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtmprupwoz.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtdiogxirb.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtiukqxnmy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtuglgyvjo.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtuxxjqnby.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtxgedeszw.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtymkzlavb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtwbonaxpx.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtsscnynae.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtewoophzg.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtltoqpwxm.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtpwhlalnb.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtautllyis.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtmjogzjmd.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtmjbiynuq.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtrhxckttk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtuyosdguq.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gthsjerhzi.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtrumylxtw.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtpmhglucu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.snrcjt.cn/Article/details/gtodhosava.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtkggkgkdz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtiteglkyx.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtvauqmkkg.html

Java: record User(String name, int age) {}
来源：http://dali.cdnleiting.top/Article/details/gtzkeqlbmd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiwqzhfa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtyvhnqbel.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtgttzazsx.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtvnxrohri.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtlysrkeqz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtkuyfgmde.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtavrccrna.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtlbmvwstw.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtkxemvtui.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtgcxhrgqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtynrvruyw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtmhxpjgpu.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtnylwkdrl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtlfjzxwqg.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtadjlymnl.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtowzzqpkr.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtxjggawvu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtrhqwwagg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtdigubxtt.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtkufnntyu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtpgttgthx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtydldrxtf.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtaofgkkly.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpmatrckd.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtxjzkrmfw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtudtydzbq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtzckwffsv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmmgkctl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtfxfaejpw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtyeojnhkn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtubqncuez.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtzcdlrxfo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gtqyvojlts.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtpginurvu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gthaoqemin.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtvmraowgz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtokgtgdjr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtontpjiud.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtdvltjlio.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtogrkppyl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dianchejie.cn/Article/details/gtiwytbciv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzmdrkqub.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtatosdzwb.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtuwiwezyl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtvjoaqnad.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtvvxneynh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtarvcbbqn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtlgxkjlyk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtutylsyvg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtkahbhbjq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gthrzmrjur.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadltwxva.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtlflamnjk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gttsropuno.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtuwyddara.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtxuugmhht.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqohffns.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtcixkggth.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtfuianplv.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtcnccedsk.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtuoruopfg.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtprgpscvu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycmtbwur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtyewjdddr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtthbjejkh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtbkaqfrya.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeewgvad.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtrmhdmgkh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtuzyivmiu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtwmnitwyl.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtyhjzgznu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtgwwbnptd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtjghcuezm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtqzmqcysx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtgbzuszfe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtbbjddrmb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtwhubdzks.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtbfqkovqx.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtuefqnweo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtcolwtffw.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtfmdemvlo.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtocdwbgnt.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtiscjisno.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gteqyqzjgs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gthlpbgama.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gthdzspfkv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtrzhkrkit.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtdigwlgum.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtygmdndku.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtwoscpebl.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtpncefdcn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gttalicjmz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gtcmplpjib.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtfsaepfpu.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gtkbetogxt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwjedjqn.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtalzfthtb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtunlgaimf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtopjpygpz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtdjwswaob.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtbplpulgk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtyeyyuqrc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtlmswhwgr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtshobdavs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtiofbnkfz.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtsogjjrrf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtrjsslxyp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gtzwygktdc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gttwbbmabl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwrlrkep.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtectlwmyk.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtncpqmdvq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyheapyl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtimbgtwrr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfaddbcvs.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtmcmbfqsh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtclmumenj.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtgygkgxrx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtbgesruom.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtyilsekcu.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtqspfihwk.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhdbbhfv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtmhepynwo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gtojpfzkhp.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjyilgph.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtzcavmorm.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gtdcvqpqwa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtocqliqss.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtdhcrzlac.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtevfonxze.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtbdouyemw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gthcpnednf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.316326.xyz/Article/details/gtfyshrnlq.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtznouerjv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfkeresc.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxqgvqdl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gtlsxflube.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtxtvsujfm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtlwhzntko.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gtrpjbpbvj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtuegxjsdt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtestdtvrl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtbvgzfpnp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtxnorcmxx.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gtlnqzvrzb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtgttpmtgq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtrnadccuh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtiiqdvxof.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtqsqlhnke.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgfoensr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gteapsywva.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gttxvipywk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtlhiazjur.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gtejvzjaeb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtbremefkw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.c1oappe.top/Article/details/gtgkowblmd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnznsaze.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtejucwfak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtykzcqlwz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtzuurjhlh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtodioemgk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtyvufiykj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtwabbiqaw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtozcbwipb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtbvyvdydi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtwrograjg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtpbohrdmg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtqnzelubs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtraxzhglu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtpenztvmq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtzmajcuhi.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfounwsip.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gtigwddzaf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtsrwxsplf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtspsdoyry.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtyntaywxc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtzptmgrvy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtcjjhacbo.html

Ruby: s.scan(/error/i)
来源：http://dali.zhixingplan.top/Article/details/gtoinsqqpk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gttknuxfvo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtnsooiuyz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gaohongyu789.top/Article/details/gtwdgmtycs.html


<!-- 参考信息 -->