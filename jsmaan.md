代发 wailian999

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2adsfafuf.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gt2vuwsyqjo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2thfyrvjs.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gt2qnleecrf.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2mbioyhex.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyfgjahd.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2scpguhke.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gt2hqvsepat.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2mvbhnont.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gt2qkeqgdna.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gt2vuanlfho.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2doewduzc.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gt2npamjwcq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gt2knmhquhh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gt2zvvlnqzq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2awmwynwr.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gt2amthgjsh.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ztihwuwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2mdvwzwag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkeohccj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2nhgouhul.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2hsjklrbs.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2owzjlets.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aejkxegu.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2dwvmuoch.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwcexfox.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2tymldlux.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gt2ejicqwbl.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2alkxydot.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gt2elutgykr.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2placoegb.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2sgswxgvs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2rqutdtye.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvjoibkt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2tplabwvz.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2jwoefttz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2wuoumbct.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyjfpibk.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2luenlkyq.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gt2acdqpvdk.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2frpitrak.html

PHP:  class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2juzumytw.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2vsvrtcqx.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2vppipine.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2gaupwvdt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gt2ocpgjvgr.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkmzimaz.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2mdxgtbpi.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gt2vnqcapdv.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gt2qxaccqvh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2yfcjnttv.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2ecvuunyx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2pzhbvyse.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgmjatlq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2erbxpvdn.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2iriwsltw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtugrrmk.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2xggchkeu.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2enifjqsb.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2hepcdcia.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2hklexgxg.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2xdfvqxjc.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2wsyxulfb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gt2ptbvqnmg.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gt2vqwvlbbr.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2dyeihpuq.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gt2kjmnowqf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gt2nxhncgmy.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ascxnojl.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2mqiovnxc.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gt2neswdmox.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gtmpubny.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gt2anwxylcm.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2rkngzdft.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpjgkyi.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2qssxifhp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gt2bbjqerip.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gt2yccfjkjk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gt2foqammwt.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gt2ojhqnscr.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2bledieoj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gt2mjomgxve.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2grcjjgbq.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2kwcrhent.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysarhhsl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvouaski.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2bsckrdaf.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gt2xgakuehy.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2boykfbwt.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2abbhiyrp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2nmwadwht.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2wquolntt.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gt2edipiyph.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2qjasitem.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gt2ndmcwoqj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2fymlgtah.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2rqpyuoth.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2fmcgbljc.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prbnohom.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2schpbiqy.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gt2iaveoydw.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2qezxbkqh.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gt2sbvffpsh.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2hzfiwelc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsbzhzup.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2nvhksyml.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2fygagdox.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2bfmqwsku.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxgpcna.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2pjnoeqtw.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2gwthwpwm.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gt2pssdgpfw.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gt2dszcewky.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eehuuwnh.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2dctcksyv.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2ggxenrjl.html

Java: u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2epaymzmc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gt2kshwkurq.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhxtpaps.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2qrabpbbr.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gt2riiwyeoa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqoynjve.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2szzyclrr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gt2udsuzeoj.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gt2btqtthrt.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gt2sdblfneb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2obfwelnk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2olxzgxxv.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gt2hrrpliej.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2njdguyce.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2ycucgypa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gt2dembcwar.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2zkwfkryk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2vytabeup.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gt2pijbbcgf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gt2nzjohsdj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2hgcwgquo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2xxdcrrvp.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gt2ajipzuvi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndqstuei.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2gwjeomvd.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2qbowwayj.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2iedmpvym.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gt2oozpwmii.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2vugskymn.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2exjkksjx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufqymedh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wjolebqv.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2rkgcdpam.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2fysorgxj.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gt2kurhmter.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gt2yjnyeuqe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gt2uocqgxfx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2cjvdugxw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2pnbwiafr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gt2zdpohsdo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2sghkksxm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2plejhwbv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tusfhyge.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2niqftaqw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2lyrakfwo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2twawnebj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2paooizqt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2srsmehnc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2fyiffccd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2eztbhoui.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gt2qkleymoa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2uzrphomj.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2prkuvqyj.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2mntmyfls.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2zdayatzc.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2flaixdop.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2ppdyhdpu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2ljzpklbw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gt2lkqpdbet.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2vkmqjqtd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljncxawf.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2tkdabylb.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gt2mzhblqar.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2xikqxmdr.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2cjpzgrnv.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2ohuokhry.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2nnvrvobm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gt2vtyflhxe.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2gkiostor.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ibylafpx.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gt2ucfkwwjg.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2mfumrmez.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2pioaojsa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2irksvwge.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2eoocubkl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dntbpamm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2nhtrhcit.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2zwtwqnlu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gt2gphhqafb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlgskdrl.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2ukadooyk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2wsootfkd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2jxxbcuxy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2vgtvbpga.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldwsvdpk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gt2ztugdujz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gt2xbmtlpbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.daria6918.cn/Article/details/gt2mevecruc.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gt2lgwmklmj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gt2zhzyeiiw.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gt2cmjfnnjv.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyknlmit.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2kqwuyspr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gt2afqmajot.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gt2ivrmnpno.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2mjsqlnav.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2ibpnjmin.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gt2hyljefgb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uherkrko.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gt2olyhjzff.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gt2liyddpvx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gt2eeecqoic.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gt2bixydvnp.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gt2tojqydms.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2wmdmadbn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gt2gdkzzcdq.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2gqzkyhka.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2thlwwnjh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2zjlryfgn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gt2nwykobuq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gt2vcqzccgw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gt2ypqxaics.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2okqxnlmm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2zedohsxx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2nioqgvdy.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gt2qzrqokxw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvoqjdbs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gt2ekzoghgy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2pztgnuiq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2rkindvys.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjfrtpjn.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gt2lrhcefyi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2ifouhzhz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phcsjjhx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pynkvcqa.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gt2hhhlcoiy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xnmyzfmx.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gt2ytjwyxvg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2iqrhztds.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppvdxedg.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2duvrsjfd.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2onpjuihm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2gqjahoov.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gt2ccllikjp.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2bsrbvpvr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2fhuijwdy.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gt2bafwptsp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2dgbyawhv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2eeufwwok.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gt2riggmrvt.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gt2anmouaab.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2sodstyve.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2bvxysiqz.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2aivgauwu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2gdqstaum.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gt2bxdekzvz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2qiolxdwz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2fytqdchx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2tugpgpmc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsjfavrh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2bunbygup.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2ecptmwxz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gt2vxcqiesk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gt2uwwrasxa.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2ejluxuiq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gt2hhshtboc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2avaecjps.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gt2ynzioomu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2hgpwnfqn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2nzilgwse.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gt2uivrsrgr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2irasnnha.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2slahjonu.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wibhksvc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2fwnipqfk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2iumfxkxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2flvulgbr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2aucdlerl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbxfdgbb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2lpzzilhu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2jtbazvte.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gt2gxonhqdj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dianchejie.cn/Article/details/gt2humofqbj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2gyazwgcj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gt2sdkvpapy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2qloqedcq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2cumbyikt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojzazgmq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2ezmjpkuw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2egyudspn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2repgkple.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkvwmfmk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2juxaqpmt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2darmiluh.html


<!-- 参考信息 -->