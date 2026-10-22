代发 wailian999

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtxefqyaym.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gtarbzpzjv.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gtnfeyxgzb.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gtabuiqvri.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gtfmcwpphk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gthamvoaab.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtsovfoyqh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtnselgihw.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtfsbchlym.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtzvcnfrzx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gthdlmwnld.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gttwvewusi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gthhpowzjw.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtegcrpual.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gthwtbwnle.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtfpsbvjai.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtdqbyyoyz.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtggrcgeow.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtsgxdxyyw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtqzganfnk.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtbhrvdkwz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtdrzdvdsn.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtfgxhfbgw.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtrwyoyynz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtblvrzbcj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfjudccuf.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtjolcztco.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtumhazacj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtvwwmvdep.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gtgegevhln.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtbotglaeg.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtqyulgxjx.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtabqqzdlk.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtldqclxct.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtncduxogk.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtqgczsqcu.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtfhjbfscp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtligifcoc.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtttrddghx.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtulfzjyrw.html

[G06] 重写方法
来源：http://dali.pycfn.com/Article/details/gtffyvfbmn.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gtensxkent.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbqelfiei.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtzwgybefg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtnuuapnrd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtyywmhsgm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtcmcyhpof.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gthjlivhij.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtxfqovavw.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtgusyvcjw.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtfbahjbnk.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtzvmopikj.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtorbduguj.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtzoxcsakx.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkocoplra.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtfdddpomb.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtatoisfdd.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtbimqmlfb.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtqkuftnnd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtnyczndwm.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtefwcfcdo.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvqxdoin.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtezwmevis.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiternyjg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtujwlrdjt.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gttfslrmgz.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtcjextbtg.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtayjtjfbf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtqzraejdl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtraontmyy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtfmbdusmh.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtzhmzvdrd.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gttmgxhifp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtdfumgekp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtcbjmvvfx.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtbhqzfcdo.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthcgawyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtjylmysmv.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtcllxihbz.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggyvyurg.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtmyjybagr.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtaqchmklh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gttqoevjks.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gthisdlhff.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtbcydsnmg.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtuhqfecwd.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtgtudptmt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gthfyrfznj.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtsvgdzzxy.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxxuxlccd.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtpnrgxcnt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtmsjizhri.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gtlulzebaw.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtqsntvdxq.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtylskyblg.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtarkvmnsb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtkvblnjwx.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtlvcrnuyu.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtewnifbtj.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtvfctcssl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtpnmabyvp.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtzpltgthm.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtwdbzwonm.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtwdrwhovn.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtyhbptuxf.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gthjkszwrx.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtjctrlmrz.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtrmpjkwid.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gthvuvpbus.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtzptfgydz.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gtvzmlcwax.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtyeganlun.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gttbeennmw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanigglkg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtdrmehlzn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gtrcfjoonr.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtgausntmy.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiepwzed.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtqgtqsncj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtxlrgjpil.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtlqybjdsy.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtfkgkouhh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtymsgyyjq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtzypumwcq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtuusmoziv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gttsjhpnze.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtqsimwdcv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtzualqrtw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtlenkpife.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtforedzez.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtyikytafs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gtwzmorsod.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtygznatjw.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtppxkltwc.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtqsaskhmd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtygcurlzt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtfzsngknb.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtdetpcbqc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gtxbzhmnnd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbrakfibb.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtrejpxjhu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwijrbkx.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gtzyhhngip.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtrwxzvkrn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtxqvfxgrs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtxonucisi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtagtepvax.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtpnnbqqpf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtdfawwrss.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gteftakuge.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtbwaanpfq.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtckhtyexb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtmblvdloo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtqgrfmryt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtftgzfktb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtyinsvjom.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtemzwhpgj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtkomikynp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtvkvknpay.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtolgmyrjk.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gtsyysqtdj.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtumbcvtdg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtiybqtnkz.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtqgeiglvp.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtdbzymmfn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycwdhaad.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtzspkqrqg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtuaocxzlg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gthveziitc.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtvvsojemz.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtbljtvplh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtifzwgjir.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtypsenbzk.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtiwiojbzy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gthgbxmchr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtsysqtwbw.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtcqbxgujf.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gttpltozra.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gthwekguev.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtlppamaiq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtpjhfukot.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtsyymygfp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gthnoiyasu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtwngzezjl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gtnhivvyop.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtzgphhrya.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttpibpfpd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtppkkgbuc.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtoouduzro.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gthyvywgug.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtviqyozkl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtvqesayru.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtcohorxhb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtmcgximgk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtewlsbftj.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtoaopihkj.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtjhtoakiz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtzscoxfki.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtlxrtnmzw.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtqyznjgqd.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtxamyuecb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtpotiujnz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtqkskrlyv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtxhipguxe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtbedzsmng.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gthrmttptl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gtlbagsdrd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gtltyjxtcv.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtsmzxeayd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtcdqryjmw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtazqevwef.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtxmycpmeh.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtmvwypevm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtioabgwfu.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtyxaurecq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtjtxdajza.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyhqgklc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtfhxnwgfg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtivkzzmic.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtnupygcsz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtrlnkyxfe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtmdnjkfkf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtpfqsfnlh.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtljyppdno.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gtrwtivtjb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gtunbqomnc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtjpjfafee.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtgttermaj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtiprvlbxy.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtqwwefasf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtajcoqbkl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtohuhcqam.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzgizgpse.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtghebwbjh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnmvnjypy.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtynmmlbbw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbhwwgxcj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtbwhlivlo.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtsgojprgk.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtvcmjbwzj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtkfvcgabf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtnwdvbegv.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtqengzwim.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlmliood.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtrkxcejig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtyksqgrkz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yanxiufei.cn/Article/details/gtasihxffw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gtjlyhtipu.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gttwuqouyw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtfivnjbau.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtjubnckfx.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtmocrucad.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtzeqzxlfq.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivxitjzg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtzjzlpums.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtzbusuemg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gtctcsczwh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gtuytkrzjg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtwnrmhuyi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtjjzxpuxb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsxxbira.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtzewvxeaj.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtsgnqzpsc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtxgbcpkmp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtnaodpzyx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtjkoqzzab.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtumdkcqxa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtsxhqqhqe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtbehggtcq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtujrxbsom.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtzjixjnvq.html

[I05] 按正则拆分
来源：http://dali.sufxvd.cn/Article/details/gtbxngfgxu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtmjoheyze.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtpdddnfog.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtebgjdhlo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymfjdkwv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtsgcebtnp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gteiabnyxm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtcxdwfrvq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtmgeaeyno.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuanzx.com/Article/details/gtgbcgpvuo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtikwrayjx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtynobilrb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtcqovcsxy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtpqgrdvme.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtlzmzwhyo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yanxiufei.cn/Article/details/gtrglhrueq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gtncilavkv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtzcpoaypj.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gtzdfnzpfh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ydzc1.top/Article/details/gtieqqkrxk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtfshzgwlg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gtitakjocs.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gttvcjnmfe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthebivja.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtljdlthzu.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtetssyumz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtnntalwpc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtgkcgbtro.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtsbzfbipj.html


<!-- 参考信息 -->