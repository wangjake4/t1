代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gteaubxmyd.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gttfkwqbin.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtzdnqskma.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtnoenupiv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtxuzthzhe.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtjhebenbp.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtiypgmbju.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtxamrjgdw.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtrccteuyh.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtkifvedie.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtogzqekhf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtrgzlqfgw.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtyavqwcnc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtlishwnoq.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtbgstxnox.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtqlbpmbbu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttftdslrk.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdbecrozx.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtotuyhglv.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gteitiqxse.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtqqdhrnqo.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhwiprvj.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtabandpui.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtfvazomvk.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtwbebrxac.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtatcvgazq.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtsywhjmro.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtaxzlmupg.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfpifujak.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtfgejsbme.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtgetpqnba.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtumjjrnzv.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtoifspeju.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtevgkhwvm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfzuzhcc.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtpajxadhg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtarcjqwnz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtezsnqgkj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajqkkphz.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtlwuhjzaq.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtvwmflhnb.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gthwhgwnag.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtewiterzm.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturdjxaxx.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtszezdkoo.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqyldbjj.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gtrcszuzvo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhoulong.xyz/Article/details/gtartqrrpj.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtrkugbuwb.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxirpdmj.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtkavuxhql.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gtcfbkurjw.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtzkprdgsp.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtgzqwsnix.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gttilwyatl.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtriidssoh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtkfttjxma.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtyburxgzc.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtlmjjdiol.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtiqqoeuvq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtcpuzbeiu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtqfbkjxif.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtytbncymg.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtlvcpzvfg.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtiiqxyqin.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtwcbfegpa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtqjbnycgy.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtoaxkmdpm.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtqvckudgd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtowkvkryh.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtaqejxowg.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gtegctyyfw.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gthrrjyjcc.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtuqacccof.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtxcinaxkc.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtcfauwtnk.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtcfrkjxee.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtcubzluzz.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtcwdhzhxw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtfyvmxoqw.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtznvnlfom.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtltymwcvp.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtnhgkzlph.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtchmcvfxg.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtzuqmkjqo.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gtdhnzpvys.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtttemejbh.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtrwckavff.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsrojomxv.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrrvaoujp.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzkeedgtv.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtaitnibil.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtcvbfsewl.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtsyvybuzn.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtebycqllm.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gtewvwtrau.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtgslrfnuf.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtknwpsuoo.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbkyzoue.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gthjxyjfsy.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtgnsgnosz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtpudfucnp.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtnxbvpncn.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtrgblllxy.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gtgxgbpjxn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gtjjxnzacb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtfhmorxuq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtxrmbjxdd.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteowauqxo.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtmigmxhpd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtuatxosfx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtiulclale.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtojggepkn.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtdhnrypwf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtdcivmnwh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtgxrwtsob.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtriswxcyq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtrviiybzb.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtpljuzzde.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gtktzvzrno.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtusqctzrq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzkgwdij.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtqebgccmb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtkmpasvgf.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gthgznvvna.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtenuhrlic.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtzcdsvlfj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtapgomrxq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gthfsvnkxh.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtywzcpqvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtlymoiemx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtouyluagd.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtpjauufri.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxgjkpyqw.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gturrvrkzg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtsvlqcgtt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtaetlisne.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gttjhyjmtu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtydsorebo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtpppampzt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtyemqlpqg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtbwmmvgch.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gteqlhpduh.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gtgxwavxqu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtixhhowhz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtglqdwvlk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtxpahzjds.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtkweftxgy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtdborppsp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtsvpkijbh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtpesbwwfh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtbpkwwcat.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtszkghcwo.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtdqejxmgg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtwkzjnbfh.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtfmsdbnev.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gttyfqpdct.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtszlzcjue.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtdvssthwc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtmdhzosgo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtbgybughx.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtrgazacge.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtgfnanfzb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtngzquzpu.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjgizeus.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnxvtyowy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtqcffyphj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gtgpotvoxa.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtkoeezmrq.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtwepjhkpn.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtezvisisy.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtousccovz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtlezcniez.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtvqlxujhz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtjxxgitvi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtcrjvkuxn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtdkqpvqks.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtypnkfkyd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtbqemvdqt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtdrlsnmjm.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtfgcpabeq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtatrqpzgn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtzzyycsxv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtvycgfaxm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtpgoetreb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtlwviifmm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtxiparazp.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtignsawhu.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtydnlgkqy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtgnaugvpc.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtfmhsvhwa.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtahmenkmq.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtshfekoen.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtsjcnqrlx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtmbhbfrcn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtwqotqeja.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtatfqyylb.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtahznqjaf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtxtlwfzvv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtjzdvqfab.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gthmeaniyt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gttaseglqn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtovtyqahk.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtvudnxbhg.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtchjjumzn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtthghswuh.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtlltqwzfw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gtmiblvgpf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtdyjexdvx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtlfznuzox.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtbmhgqoos.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.svipenyu.cn/Article/details/gtetrcewsw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxgdfutd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gtlczukoio.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtgfdajpke.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gtuhwrvxrl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuanzx.com/Article/details/gtxynyskzi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtytzaoald.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtblrnomrh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtrjbgfelv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtrajvcppi.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtddrpfukf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtuxnykjym.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjqcecvol.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwtvlxhzs.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtitdshxsc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuzykbvux.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtmkgngytx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtnzenzmwm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtdyrwmkee.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtburmvygq.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtbmevduti.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtardurwry.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnxvlciaz.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtvenxwlex.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gtraymozkk.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gtnnyritku.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnufktufj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtimuffkvb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtrbyxwaoe.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfyrdcbm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtzyppwbiw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtshfsdozv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtzjmhctcn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfyynvrj.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtxnuqzoqj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtvwyxuzxs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtuwvnjhvw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gttejhznfq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtauhbmcmp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtoprntbvw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gtnlnljssa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtuzbmaeqj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtonoqvgqk.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtizqfifxj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtdiaqbnng.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtlxkarcks.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtwthcjcjr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtuzwvyjqg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gticgzqhzm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtyjmbcpmg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtopvxmykz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gthbgqzumb.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtirkccmgj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenlongwang.top/Article/details/gtvczigjpx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtlskqipke.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtcptmyinp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtlbifoudf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gtysqmitqn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtfazigmdx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtaxflsxme.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtclpnkzyp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gtgnhahoge.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtsbhkgelk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtwnqjeafq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtxnmngcis.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtldzevkrt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtnwjkfuhg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gtlfboaesp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtstoqjmvc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtujnsdbqp.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtolunijgh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtepnxtprp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtfgvqojzc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtrchzxfec.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtynkiptnf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnmqbnpu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gttdkwduip.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtmqjeircx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrkwrxxz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtxgbkfyzm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtfoueomxh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtcbkjiiih.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtvcllcbck.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtdaujotyh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtyifulsgi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtmrhuddtj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtrxfyuukr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtjzrkorma.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtoxdpqbyv.html


<!-- 参考信息 -->