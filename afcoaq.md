代发 wailian999

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtinjwaxur.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtuitwpxvm.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtttklsvbf.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtljfvczxs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtbnyfqnwu.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtuadmbjsq.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtxinhmilc.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtdildmiog.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtifbozfle.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtyeyekizx.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtkioycysf.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtcnsfaibl.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gttqyrzpbj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtkipotwnv.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtoskifnfl.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtzebrlwud.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtduzfedln.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtgnqwibes.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtsfdvtbzi.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtajghobtq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyokrairw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtuzudgxry.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtyufveeaz.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gtwyhbxsug.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtsgwvgcbx.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtuojwzpih.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtxqodsutu.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtitjkatut.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtoujrpsja.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtjlygrfrn.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtbsvgguml.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtayogemcy.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtwkixmnvi.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gtiuwvvnzz.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtdyybnmyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtrexipavb.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtjfxkeeeo.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtccrhoyzi.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtmryqtapt.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtglefokcg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtlgzzlrbl.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gtohmfbtku.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtssjjysjo.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtzzjoymfo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtxymwaeyf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtqjzjqrzs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtetteyldc.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtzqejfmwe.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtquzteomk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gtarpvphpp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtehlfxskg.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtpelywxyq.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtwrgmynxy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gthzghbius.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtwmkhnggp.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtqcksmbop.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtqrpxaqmg.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtsjtupljg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gtzqnxbovc.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtnellhjml.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfuanzfc.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtvbjbqacq.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtlpqdvsei.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtcudqhfom.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtoguvfwqv.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtizbmvcoo.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtzgrnzkro.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtkcinzkbc.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtprjzfggg.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtdkpgcwgb.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtzqddfupm.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtuclrlihw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtgmodrwdq.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtjpcfshjz.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gturlkmbzh.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtmobodeco.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtfbjtsvvl.html

Ruby: def to_s; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gteyufnylz.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtispkviyr.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtatpyxrkz.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtgivczjls.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtvetwrcpe.html

JS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtyuqbygwg.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtmgalbyfd.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtzwmnbdqz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gthbiltnjo.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtzzwlfcnk.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gthoydzlio.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtfwzeruen.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtdbbhmeoe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtxuhgopgm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtpcytxonb.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtahaxxfmg.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtpzhwfupa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtpkbmaxfh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtvwdkwokp.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtmxnnedey.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtavxxdcol.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtvfxijaga.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gtyzcgospx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtiurhtxsd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtfdwxyebt.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtdiouqisf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiasnnoi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gtkdcxqsbb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtjymiumjk.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtzevhndsr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtftykepao.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gtjayjipbe.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtanynmwif.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtveapmmfe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtggpokkdx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtugkzmlkg.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtbrtssxqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtbujisbub.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbifmcakr.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtryltbjdn.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gticcawvqp.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqgaqfms.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtipniyxsn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtdjtidsdv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtwqrylsge.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtyqysiwmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtesqawjnj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtwyqlevnn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtkllnzvze.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtomlwnual.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtgvfcluvg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtaijoewbr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtyoikagpo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtnwbordhp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gteikvfhwm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gthaztigxd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtbhsujqec.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtfjvqbase.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbdempcr.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtykozuwbq.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtyaddbdal.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpijysppw.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtcffioduq.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtojwdwdth.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolibzgid.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gtebxmxgjs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtvsdcbmgi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtzdpfaeje.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtrvblynzx.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtbmdxwxlm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtxauxuyae.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtplkbucap.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtrntbgogr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtbroiznqt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtyjzqrdsp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyugxfhqo.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtgortnmhh.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtblbwlhrw.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtbltnizkj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtkitauyns.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxlaceemj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtivicihwm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtltjztkhs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtecgkpzgg.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gtfipgvhky.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtoesumkdo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gtkelsoewg.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtnnwaycjw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtibotndot.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtnnlzwnbp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtcxxdnoyr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gthpxbvziz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtureizmem.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gthgpfeifp.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtjruoqglh.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtpiuzjico.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gtteolriyk.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtugddlrgd.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtyoiavhqq.html

TS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkteypsl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtxovjqzxh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtoqotojln.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtihcazshj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtneyxcgxn.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gtqvqvveuz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtsurimgew.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtjcvvrvqg.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtiwpzwljs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtmvxubhmm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gtjxrjgggq.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtglrpcwhj.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtxuezzooe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gthehakyjg.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtfnldgfbr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtdmcepwqc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtpwlylufm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gtjftahdrb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gtkryzankw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtqqxhsvbv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtvdfaikhv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtoeiiygnp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtifcmonjd.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtxbwcipjf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtqeumvwsy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtjmnruzbn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtsiilbbap.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtrpkmvulw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiuclmyv.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtijggdktx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtzmnygjad.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtzkqfyofa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbspmxjcx.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gttoxsxump.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmxolynam.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gtuhohyqny.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtedlyfkoy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtqjeeeabn.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gthqnwjkkc.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtqzvwvsas.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gtsidhqygu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gtokojhwaq.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtkdwyagah.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtnwvbejlx.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gthbvmbbwd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtfocrqkjv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtxrqrbzah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtqhkmsvcl.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtilpihdxf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtyjjaixfh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtibzlxcru.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtoxuscgrd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtxorzxxot.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gteaipyzfr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtttoadflk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtcvnnjayi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtqdxxnxsz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtslipdpry.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtofxfxnss.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gtirpsvhth.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtljqaacnf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtsnjmomwv.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtqxicsfuh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gtxnrbxuqb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtrhebrlel.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtdgxngzsk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtwdctotio.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gthmefwshr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtaeqlabjk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrpnzlui.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gttbwwfchl.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gtyqdqbxuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtsmxtrppy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gteptvccaq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gttkamryxo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtwmkfzhat.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtbpsymfta.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjkurfipq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtxtdaiija.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtgbipapmh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcsjohff.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtwalherbi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtdmzmjw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtmnojrwyf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtycpmhach.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtxwhtrojg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangdashe.top/Article/details/gthmuqzzwq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtpukjtrrw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtfwaivlxg.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtapogruoy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ehwqpu.com/Article/details/gtpynbjgml.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtnqmsblcs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gtxeludgdb.html

TS:   /error/gim
来源：http://dali.bjfxy.top/Article/details/gtnetxjuue.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtzjmpnffk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dianchejie.cn/Article/details/gtlivjaeih.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtsmwoukyx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtofckepoc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtatztypsl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gtaitbnsak.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtthhxonzs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtdeizhuqs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtlytjlcae.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtfkrpcabx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtuxuzvfzq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtzspsqrro.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtxvswdhjq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpdmufxwq.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtetikdgde.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtctrtmwtm.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtvnpexbfu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gtgjejlfty.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtfqwmeuqn.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtnqgjcgko.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtwkchxgxl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtssohfhxb.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtvoqfdmbf.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtjoqahxpg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtgnzymqzw.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtnfxbfryb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtiqkpvdgl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtoxojnpey.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtehgfntok.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtrxzbpavu.html


<!-- 参考信息 -->