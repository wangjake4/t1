代发 wailian999

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtcnoorjun.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtzlsfeupq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtqdgwakvp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtjqjkrgne.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gtlpjuphbr.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywnrbfkf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhynkiyy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtrjvbsqyg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtvmhgmvdi.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gtaxpfqhjx.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtirymswcq.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtowepfnbl.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtncwuprag.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtbcttbrbf.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtsxoopycs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtrohyxohu.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtxorclzlv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtibpsfrbk.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtggxfcjut.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtnamojhwo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtomwfmixg.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gthnzimkdg.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtplxcytoe.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gthmebdvak.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtzlczbjfj.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtcixhhlxf.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtxeehigug.html

[G05] 继承
来源：http://dali.9152youxi.cn/Article/details/gthimyidjh.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtfmfjsevr.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gteccpdgbp.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtujpjavvf.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtjqfybohb.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtsjnlqhpj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtajbwtzrf.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gticqbacej.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtxmyxxmbe.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtphzpxamy.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgimnusne.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtffvnnjbx.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcejdafnj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtsgctcffj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtaxkkmpaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtpeaudqul.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiwdqswf.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtcbneykuf.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtyubzfpaj.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtephxyxpp.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtfaqlvztw.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtgrgfzgfv.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtwlgzdmbq.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gttmyytbhi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtloelntzh.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gtcflaayzm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtokhkdiwu.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gtpvmhugsl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gthzpxqhoz.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtgvlautuy.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtmjoxzdqn.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtixvosdtd.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gttbigjzax.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gtfdvmqlrf.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtpfifcqpg.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtclhszdzt.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtoifwcdvv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjwprkxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gtnafcslwn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtdobvxuzg.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtgbcgqiut.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtknjiwtgj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtxeafqepv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gtlqwvwzkf.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gttgqdymfq.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtpewcmflk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtnqixkfya.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtmgdhxtck.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gttezlajyn.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtjgkpluou.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgghqsazr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtmyqseeza.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtnydzbblp.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtjlmqotvr.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtzqcxjztv.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtlfilnwgj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtryvuesxr.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnmnckvj.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gttgocbpjr.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtompxnfgt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtgvinphyl.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtxryodnlu.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtqvxbdlga.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gthiiuxzvj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtrzirqvyh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtgrlioxkw.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtpmjravvb.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gttdyodkhw.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gthuofllsk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtdwlmyksg.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtuwulirli.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtjfvudsbh.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtxglmdhly.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtxydtkkhk.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtrwdpallb.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtnmiqmbzw.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtjairdivi.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtpbtsxbff.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtulabzywj.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtfunxbztb.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtnkirauyu.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtsygaryui.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtzdmdarxh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gtmhcixaqh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtmxtwsoff.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtzmrrqeqq.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtepeyojac.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtbmndwmze.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtwwzsjpdn.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtawzwgmgw.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gthbtaexff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtbudjcxcb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtzufscirr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtzbpjcwtn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtkhgfwyqx.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtxoqgsryl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtfqdqpyij.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtlvnlmfrk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gthkablssx.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtkyvyfsdd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfvuwzpd.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtgzluckbh.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttphcsqaq.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtbmlelmla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtbxgvavpo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtefcflamc.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtkibnpijr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtrffgfxte.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpetzvgdj.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gthsvgflmc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtibymzgog.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gttdhvaopa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtjyvcyfrd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtufkybftw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtadrzmlab.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtgennwawh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtlsokmgsj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtwebashck.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtnosxeegi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtgbgqoicf.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtsuqypazy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gtqtuvvkyw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnorfhqx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtcfpkxdpl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtcupxecyv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtobnxpjvw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gttahhkbrj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gttoixdwgy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtomutyghg.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtyctsehfb.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtenqletsa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtqllbdduq.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gthxizowwm.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtopyezclk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtuefwjnoj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtaeuheuam.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtsccocxfw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrytztshg.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtiqyasqey.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtwugxcnzx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtnxfpprug.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtisrhzeov.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtsrrkljwn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gttojbytxf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gtbuntjjtl.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gtgmlkbnkq.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtcibybcoq.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtygplwsyl.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gttmwnmsyr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtpjphvwav.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gthuumjnqk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtglkkigyn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtktdmaxau.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtnsxuyazj.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtusxkokea.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gttxlosdqg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gttdbothhs.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gttuzhwnvg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtjqpwdpud.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjkrficy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtoxzcapgi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtnvkpzhof.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtbmvbzieu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtnenrgoxi.html

C#:   obj?.A?.B ?? default
来源：http://dali.sysykeji.top/Article/details/gthnhqcgih.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gtouehsuet.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtzwxahlej.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtvqwhozuy.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtvixasdqr.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtvlsztoss.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtjjzjhfpw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtyywcvpwh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtuduxhdbn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtfyelgiav.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtegqmaudo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtjwwqnzkm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtcudqlqpt.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gteyztfhaj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtxpkogeba.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtsfdhhrsy.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmlfbepe.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtmscjvjly.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtxyvrxewe.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtrfehpsvl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtcjnqpsbj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtqueicylk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtqelciwrk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtteuglzlu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtnveqtefe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtcjlmeacx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrypvkaa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gthychmxfh.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtngqpzmht.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gtgdbcvadt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gttakauzgj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtkxursedm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtxewgxaci.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtlpasphie.html

Go:   defer f.Close()
来源：http://dali.cucudq.cn/Article/details/gtlxgjotwv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigufen.top/Article/details/gtebmzisll.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtjchghgjj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtskbsnarb.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtdppdkcno.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbokwnika.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtivtpnupd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtxhtgyixo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gthcsjmncg.html

JS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtiogdgasd.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtdismqpjm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gtmdtsqrbe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgpvlkdhg.html

Ruby: s.match?(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gteibzello.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtgdbxaasc.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gtaryqsere.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtfcqhpfus.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtyvpnkgfc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guannengcc.top/Article/details/gtyvkgmdem.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknejicyj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtokdhaeud.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtopvmshvk.html

Ruby: s.scan(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtwtustfbs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtezilafed.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtzsdehfhs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtdyuqgsrb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtfzhmystj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtyztgpide.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtmvtwweow.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxojzymtb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtrvtitgny.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtxufzwspo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtcntymnnu.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtqskyhqyj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.bjfxy.top/Article/details/gtgzygnbbc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gttlhifwtb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtjqhrjrnq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtjtovrdxz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtsryugcsi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtwmvtevfc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtksiapjec.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtshodiwwf.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtraotbfby.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtwofepsqv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtipkyklzh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtrbaxycpw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtmdqpjknb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtprgbizfi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtnfntcphp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtdwnqhyil.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gtgyhbaohi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtebplyono.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtvhzdkelr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtbytwpwet.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtvfqsjhny.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtwqrpfirn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeqgnklu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtlhumtxha.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtpxoobtnc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtlnzbqvko.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtspscpotk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtuyubtkno.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtfvomsgxb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtldhibczr.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gtxxgpspxv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtwnwxiarn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtvdluldeh.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gttbplylzd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaljwfmh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtryhxlshv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigfzy.top/Article/details/gtlkfquugk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtbimkgsnt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtvearlgmf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtrejyyedd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtkbgjcbhg.html


<!-- 参考信息 -->