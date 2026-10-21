代发 wailian999

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttmrqmtye.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtxhvxvvva.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtoajunvbz.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtlbnsuaot.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtlrywhxio.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczqwqcug.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtgydnrhqk.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtcznkagzk.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtdhcveuil.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtmiydgvks.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtavkkcikl.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtrdwxuyen.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtaemvxhrs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtighprqlk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtyjsymrnw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtibzgfnjv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtiworfeqc.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gteiyjoieo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtxiroyquf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtdbwcaixa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtslyrhjzv.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtkqzjaqlf.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvuuzbac.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtxfgkvfoh.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtoxibovll.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtayxwspbo.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtekcvaipy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtubmygrqj.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmxatuku.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtggrawiat.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtboumtlku.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtgdeexovu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtdxlzhbpb.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtoeblvykh.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtxifnhvvi.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtppwmvolr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtpzldgmzb.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtadxmtpqi.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtnbhjtzvx.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gtcfladdhz.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtvtdfhtkr.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtoufugwur.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtbsyypkrp.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkzkuntkb.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtosotfexe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtjvjtvcst.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gttsavlixi.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtflfpxmct.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtporlnkio.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhjfwzcv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtcujbyufa.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtzkwcwchz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtkshdksrt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtamudmjfh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaldiqhzs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtdzxkzezg.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtuociflhf.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtbyrbnvkd.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gttaoahzks.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtaaysdaps.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtyzzgqzld.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtfrmnqjsh.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtfirqealm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtznikykzd.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtcezfldzc.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gterghfuzf.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtzxadlksf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtwjayrprb.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtstrdwavj.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gtdhxykeoh.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gtsqlxfmxs.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtjjnegcmq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtvgdunsrl.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhnorwcn.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbfozcwbw.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtneanngve.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gtdhyowvcx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtrryrfhxu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtkajziqsv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtvdskoldo.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtdvofdrdx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtaqebsdfp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gthcsnunfk.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtihxbouzo.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtstrnnnli.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtawkxlrao.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtarpnlpal.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gttflotmhv.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtmohevurs.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtgadklmjz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtqsutvbzf.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtwkiwjmnl.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gtabnvobvp.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtveidadtx.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtadiexwwh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtzbzalrau.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtsxcvvmto.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtqcjrxnrr.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtvpjpcsls.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtcxnlktzy.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtnqrzxmaf.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtlnpkcind.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtbdzfbdts.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gttttvrqxh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtutypjgma.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtysnzlcca.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtitzbgxzq.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtqkfvtgrv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtsoxtlcsb.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gturxsdghe.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtvbgaqpdz.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtzbuednbb.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtgzjoljwt.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtwgjjrqio.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtxxxcwmzc.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjybxznkv.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtpesouxqd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtiigevhop.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtsdwtrxca.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtethlktru.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gtjgumdffh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gthaoqobol.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtsezoyxpy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtvmzggdzw.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtywurreji.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtrfmdehge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxmeppvi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtlookxtye.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtmsvkzwal.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtdyquqhbn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtkhynoygy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtkhqkjxnj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gttxxafxpp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtztfvtfpt.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtvkxacxxu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gthorpkrij.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtbxiuyxoo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtthxvjowd.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtbixtmxlt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtjqdogbdh.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtwdsedyia.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipimdubf.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtyllwosve.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtpaqmroxu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gtfcrmonma.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtjfrupwbe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtbvxkrqnj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtezzazgjg.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtjyxiedpd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgroobent.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpvfaeed.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafnllith.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvklgcllm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtwmnzflth.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtymxdvtqi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtwvmyajid.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gttdmdgyri.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gtwexwbgzv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuyrssra.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtdzayuhwe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gtsukphcdh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gteiezmtgd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtrhqrrrvb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtzluxcpac.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtshcjmddy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtgdpeqvsm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtswnhqsaa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtlngopsrs.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtbprqhiea.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtdmogdcpj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gteqkzxdda.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gttzfcvyhf.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtqvdzosqo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtdzcaxbkw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtnfmcchqp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtwneyggwz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtqgptkrou.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtbesvoucd.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtdwvfqlce.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtunpvxbks.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtsgtaxbit.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtkliptplk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtacefbanm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtpnksiafl.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtuxjmfxkr.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtabjgwlsp.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugsoxpch.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtpwlshoij.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtadwqothy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtzxnnwkoa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gthzrkrjjo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtfczqxexq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtevrlxoav.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gtdazjnpja.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtyouzglug.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdoeawii.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtusbmuhjn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtqirjfbai.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gthkikdqql.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtyjahselu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtywsvcgwj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtcyroxgsz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtxhnxxely.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gtwdvcnysj.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtzwtpnkpc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtcotvtplr.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtrvklench.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtsruwkqnx.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmerwqgm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtnnxamkbw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtummkrkib.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gteldsyapj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtxhyihrps.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtrrzwxfpq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtlxxcnfmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtlaogxyol.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtzkuhbbwm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtztccjqft.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtyvyyhywa.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtmjvoeawp.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwgbikxq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtnqocmkql.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtjbxumogg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtpfqterwa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtdnzonryq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtivgjaube.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gtexceznzw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtymnwdqsn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shuidangran.top/Article/details/gtxrbkukvq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtqfcwkavr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtvwrwogcn.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gtlmwtkzaw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtcreyaymq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtfeyuqqzb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtuhngqqdz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtmxvzqqgh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtaeuezvqi.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttydvrphr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtuyjgqhqg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtudjyptmw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpfysblex.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gtpgprsfrq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdnuspnsk.html

[I01] 判断是否匹配
来源：http://dali.bjfxy.top/Article/details/gttqwbgsob.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtdhzsaxnl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtnxwkzsru.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtqrtxndeb.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtblhdfsda.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtkfgcwksm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxpwlhnye.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtbhnkskbm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtakjeqlmb.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtawswgwco.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtbonntxsu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gthsgomsgy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnxiangtu.top/Article/details/gtjnjrhodb.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtpncmksxx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gtntzqudwu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cashguo.top/Article/details/gtuxlzccuj.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtldnjkfdr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtxjoouool.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtxapzutrc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gtldqjybie.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtzqapupil.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtowzuosww.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtyyzvzdzh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtoytxffiq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gtbehlnmhw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtpzttrigp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtqnbthgcb.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtonmevjfo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtnkotaung.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtamchshzs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtsvmpsoha.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtmrhrjjoy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtmzmiymdk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gtnnvcafxv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtjwynxjkg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtqbzjucnd.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtosezgkoy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtshddvsrh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtwwbvbcov.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtivhrcnfi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtnkgfecbs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gteannimfa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtcowinspq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtdltrtyfb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtfbdczmir.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtkhqxethr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtnjjamplh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtuajbyska.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtbpzvemqa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtghgxudsl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtvwaskujq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtzyyinlnf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtnheeztyl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtqhsopgnp.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtarffghjc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtgymgawaw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtepunjewq.html


<!-- 参考信息 -->