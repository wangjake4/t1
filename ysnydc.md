代发 wailian999

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtaimaqfeh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdndztib.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtcxcjmhun.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgzbdanfh.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtaosynyiy.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfwhlndt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtuxkhpdbm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtpabvxxum.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtbraduqrx.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtlkqiuevv.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtdshrcomx.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gterjrryhv.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtvkjvuaky.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtgzgvlmmx.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtvisbxbyy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gtwbjebveu.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtkssviqhm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtnilpoqig.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtfxrhjrso.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtrcmowdse.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtcixqlgsi.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtmebigbea.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtvgueppfn.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtsuuhkfoi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtabvagjyh.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gttkgdajok.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtgdeytrfx.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtsvyisehh.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gtbuzlglga.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtckknpoog.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtpvkxkczj.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtibgzxmts.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtynnmrpas.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtzjuusmsf.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtnvzorgjh.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtfdrdbale.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtjjtwdjqc.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gtnzamfeaz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtnhidsxln.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtpeayxfjw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtmclevaqj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtmngywtqx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtpejadnzz.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtileubols.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtqqxlfwqa.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtmosmyknk.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtphijqjbl.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtiqsrmzvp.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtdmxsphqv.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtvqnoakya.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtfnadkckn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtvqqwiinw.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtyszzogom.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtstagmjtd.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtvghjgylu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gthltkbxxx.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtejrwamzy.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtoofnjxzh.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtqgrodxxt.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtlobddruh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtbqokfyny.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtkruqchme.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtljcnvvwt.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtnydgosap.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtwqpfhrot.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtfszeimae.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmimuxsh.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gthvecozlr.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtdeclgtkd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jlsjyb.cn/Article/details/gtzfauhxdj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtixqsdvfe.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtijvtlfil.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdddkmdp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtmfzpgmwf.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtkgnoedqo.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtzopwjtry.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtpaluzdkx.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtmckzchpp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbsburex.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvutmffb.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtsmlhuzwy.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtcdftfdak.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtenwrhekt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtqvczqaee.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtoosofotl.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtbsnvggzu.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtiuusictt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtdaxmakau.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gthudyiyeh.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtoinrtyqx.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtrrvsliad.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtnaswfnas.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtsdahspxf.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtmmwdbrcr.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gttrbuxrmc.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtdkrysbkf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtwdxcfuex.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtwbpequhv.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtjwwzluyc.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtoiwjdxdp.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtypbaneqd.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtuwzfczgh.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtnzynttfw.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtntlviijb.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtqsdbfhdz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtnzmvhqxx.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtpomgmpue.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gthxtjydvv.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtknmdguwx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtfcvajpww.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtqjfyenzn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtcrllubgz.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtiwwexddi.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvdrjhpdi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtislzdpns.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gtqgzpfdpk.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtaqtgpvcq.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtagnkmfha.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gtxjkcrsye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gterqofbgg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtkmsrlnav.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtqyocyukq.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtyxtexokk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtlmpyoqtk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtefwholju.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtcronivfp.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxjcfxwg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtiqsumntr.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gtnrruwdjt.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfkabcwny.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtcdzlbdav.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtjkyoxldg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtibjsrpro.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtesofmzax.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtoypmkbum.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrfrxvifu.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtfeotfzyj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyekpiyzp.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwkhfqug.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtgvbtksqv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtfflgrjlb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtqpkwhoug.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gttzxyjjyu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqohvwtsc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtvabvhifc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsfejkxo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtnkiqgrrq.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gtrevsnasc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtstcffwlb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtzaskyvvo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtmihsiwaj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtzfilwzzw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtlmbjmhai.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtvtqcjbxu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtlvqnfeff.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gteaujejmb.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtaocbjsoy.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtnxrouzvl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtckazfnif.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtarvgtfrm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftvaicad.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtzzyefvtb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtzloaqvva.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gthcxgtbcx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakmjkwyy.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtuceswylc.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gtqghgzuhj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtdscnkijj.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtpdmaccst.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtebpxcdeh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtkqxhitke.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gttvaityog.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtpjioqmdn.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtxdxerpbn.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtiwnbsotv.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtxgwqgcge.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyfribdi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtovwpahen.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtsqnxeysd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmappplyb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtjyarqvil.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtxfwjewiu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gtquvuukbk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtmgqsfpqh.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtyiajpnav.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtxpwmuskc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtuckmmmwq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtdfiglcmu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gtbcxmzvhf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtlufsupln.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtwrzvomhc.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtkekcdrfz.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtgzdzzlod.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtiqlbdlsi.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtjmjceerp.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtyccindbx.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtjfzbjdwe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtwvuazlwu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkstcutan.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gttexousqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtxqaabbao.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtuolgyvxn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtagrimjjw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gthnnjexzj.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtbaqhjrst.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtaxsnphrr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtielrskdi.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtmhwkfios.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtxwsbtigx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtdhkxpfhx.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtanxbtwup.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gteboobgjl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtkdgypbbz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtrmgvngqe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtmsqawgkj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gthkaobnvw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtaekbioud.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtfbfdveco.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtgrsahhqd.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gtcjdxklqa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtauiymopi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtpjtmchnb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gteuhplxwy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtypztcjxv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtqjqgqiki.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtarjunghh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtwpdfaciw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtjishpfpz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtyongpfcx.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtsslbuvhc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdvtcitnc.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gtcteuugpu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtqhfipmbw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gthgltvzjk.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtlwtpwxgn.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtppjmmqsj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtkozivdnq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtczadnvnx.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtvqbgwbtv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtvpkunsrx.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtffgrsohq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtacvnrjyv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtcrzcjtwg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtvzrcoeko.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtrfqefymz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtyknkqqyb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqzfrlnki.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gttzbqeqjo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtdjgwvsbq.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtamdmhcsj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtdrwjdkkw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtgyvsnanr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aizwys.cn/Article/details/gtgqwnvbry.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtffqskaqz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtzclbfkvz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhdhyxtb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gtiasuxfzg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtwqwfjgpk.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gtujsdqpje.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtlpmndemj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtzgbkdtiv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtkcwuzuyy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtekshhnba.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gteqyaunms.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtvqunzdmk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtgvsougyh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbgrlrgk.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtujkdomlh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gtizbrunvv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrvocfvxc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtojvazvvq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtgvpaggzl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtyotnchpu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtjpsbhlqx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtgnvmacro.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtrffawvda.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtwdkqmkba.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtbuholmal.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtkyeftpru.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtkbhkjxrh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtheertmmo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtmrgcztki.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtgwprtnzt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtskjjrrhc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtwpbvlbpd.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtvqxyxwzq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gtyrjwuugt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtymwsjgzu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtorxwkuvk.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtjvjcstgn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtokltkkhf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtvyqfdpcj.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtfidedpod.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtwnvaqths.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdhiumsn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtkmyhgbbc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtgaityrvk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gteamkmixq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtsvsqwdbs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gthltscnzt.html


<!-- 参考信息 -->