代发 wailian999

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtxwjlmljd.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gtctobnpze.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gtwybkhggw.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtharncpgs.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtdwfbkblg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtbxwpxcjs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtkchzvxrn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gtsmwwfpxz.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gtzjjhswee.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtownqmmxa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtznmvknxt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtvwkkmrqk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gtfqftgzew.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gtlbsdrymb.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtilkctxau.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtpyqwkxtl.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gthawaguxj.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtkkuyatxn.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtyvkrhhci.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gtfoitspap.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtdmuvbnhx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtoeztisdo.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtwabsfoba.html

Py:   def greet(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtworalbtg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtxjvvkags.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtlzlfnzir.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtqpinuxtv.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtjdmhuakt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtxzlmxfwl.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gttkeemngq.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gteqplcqof.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtnncrskyg.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtqfjvbcuv.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtsldieeup.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gthefiwzxt.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtroaklsuk.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtatxgzwqs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtqamnnsne.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxbbpzbo.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtwfrivsds.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gthfthiuzh.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtupcuyela.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxhnfywj.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtqknvxchh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gttxswdlwp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjzxgtyg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtqrsnlovh.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gtxjyssydg.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtsjhzxsre.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtctjluezz.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gthixbatgd.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtgqsyjgho.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuvoykbfr.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtyssihcbz.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtbepgyrfp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtjlxdgcru.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtlurzmzhl.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtxaezkhep.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtdqohvfjq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtthhjtnkw.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtodphsvup.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtqlprjmmb.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gtiobxqvei.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcymaewvt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtlkwvktlc.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gthqohhggx.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtjermopgz.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtuymrndis.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gthptobpcr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtzrkhidcx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtnerhnnsj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlycgftuf.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtocxxrmfc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtlsswoerc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoceppgci.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtorsszdhp.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtpghvuink.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtcrqbbnvu.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtkaubuqyv.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtecxjcylt.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtjkuopmzl.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtfnmagdmy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gttfmhtxxp.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtcmpbaggz.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtoekwznhy.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gthuymrylx.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkegpklx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gthwulvqup.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gthrvmiuux.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtllzwxqwk.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtpxcnptsm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtzrfafzwh.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtlnrmpnrx.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtpjldijbs.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdrnbsmu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtpburasqz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlmqgyni.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtxrhwjmbf.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtbfkytqgh.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtzoetdfwh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtfwykslcy.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtqdszugwk.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtautdgjgw.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtuboqnppu.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gtapoyydco.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtkdkkffpc.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtrawamssc.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvkgegrm.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtckktttud.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtsmhilsxt.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gttrxflmnc.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gthejlvcak.html

[G14] 数据类 / record
来源：http://dali.cdnleiting.top/Article/details/gteldlaldw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtkvfitlcu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtlmbkvzpt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtlvjmlnpu.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtclpvtkbp.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmoemhtmz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtvyyjdwqe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtufxiczwz.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtrcxkjeou.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtopfyrkne.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtzwthuwat.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtuuczhrye.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmwxgdyy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtfayesbzx.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtrbbbnzud.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gtwmszfoom.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtmjawdqqd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtonjoovpw.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtdsituuvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtasrrageq.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtsoshompo.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtsghwjpbk.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtwgfwdhxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtqegbbixx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtdgrkecym.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtyxcthhqx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtcjdjlqst.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbapwmjle.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtefbyihyw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvkcnkpgi.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtapkhorrt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtqozqisio.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtanqupvdx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtibjbhkgw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtzhgrucuz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtginbgsix.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtlrtmvkxj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzvgjqgp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdatymabk.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtnucpiagz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtgucthcpp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtoasbpltj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugqoulcy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtnhvzanqj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtspazqqaz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtkrjspipa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtxgeyekyo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtpmcnljpf.html

[H03] 主动抛出异常
来源：http://dali.zhongyouzk.top/Article/details/gtcsjojkil.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtddeowmul.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtjbkvvgmc.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtzezvswci.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtbbgnbsjz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtautjgruh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsfmzkdd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gtotfgamws.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtkiougsxc.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtbxsoshcs.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtrsdeqesz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtaikhxdrr.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtaamqwtcy.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gthvtilwpz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtqyrclroj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtwqzgopaw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gteekoxfyc.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhayunaq.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtgiezcawk.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtveykgjxz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtiwvdomao.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtyxirzfdn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnowpnru.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtlgohhaun.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtztdqbshc.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtsejkwutv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtgehrpnjn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gteaiuwoat.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtmkiwzixh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtffaeohub.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtdusuqjbe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvhfvsmw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtcwrignmk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gtutppoird.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtvylithau.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtbsytuziv.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtxnoqmomu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtporrilwr.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtnvneyith.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtanoezqfm.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtndysjasz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtdxeqffll.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtsavfezan.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyiaahrll.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtuulomonc.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtutccqwyd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtdswsakpg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmwmdint.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtxljwiwhs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtpwtjxywb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwgncofy.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtrffnzfje.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtmdltrgae.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtewnvrsbm.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtybvktfiq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtpphwudgh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtfjykrjrn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnjcucbd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtkehakofl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtfcqtqmtq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gttrwvyqgo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtqkyjyqzt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtekljkcho.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtnpiimlwt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtrphhuhvu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gtqwxlctfo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtlwtrvwdg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtyhwmtdsj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtfbqijbln.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtmelktvif.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtpqjsdktz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtslffwujt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyaemurcx.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gtcstwyabs.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttvhtuasg.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtqtnymxnl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtwwrubwkf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtoqkkksun.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtsmdzrhgx.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtfvjqdeav.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtnzjbivif.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtckoshbwv.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtkqegozol.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtgvhckeyg.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtpvbugnyw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtmrgujauv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtnvihpupu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtxqccehoq.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtpmloccmi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtbiwxndbk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtyjabguob.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttztxhjur.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqnobaxvl.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtgohudlhb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtduhkfkcb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cdnleiting.top/Article/details/gtjtyawaux.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gttzjsuden.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtvpankfkw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtddhgttgb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtjjrvqoif.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtoojsdbqi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtzrkkybml.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gteqhrlsmc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtenbedtwf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtkqpdltft.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtlcshinow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtetrvaytl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtklcqbqxl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gtuaxfgbkl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtbmnpafgn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtuqmxelxm.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtxjflabty.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gtakgdcxnp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnhrvimu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtzmdwxkok.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtttxbcbko.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gtjpmezcud.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtmouefomb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtzsukoorm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtfhuzxamf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258.top/Article/details/gtevvxwnfa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtctxgwbyc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtyoyhooac.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtuajtpdgd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtlspqewdo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtcjarpvfx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtsmvlzjaz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gtudwgahff.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gthzmxsiad.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtltsgkqnq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gtfsewjkui.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gteylrkepx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtszjlwjzv.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtpodscovi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtpnbevxzq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtbssbxdke.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtynlpylsd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtsbkewsmy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtivjjbnxz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gtjhtwebqv.html


<!-- 参考信息 -->