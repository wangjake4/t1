代发 wailian999

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtlhtwivsq.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtexmykibz.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtotiajcbi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtchlnttjm.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtqwotcasn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtrbjuwz.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtdstfwsbl.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtdyhvjviz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxgvjqdez.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqqqtfqmk.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtpvrplwwd.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtakjjmxvi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtmqvurzdk.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtenluriqx.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtizejijkc.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gttjemckkq.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gthrgvyszo.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtklesvhut.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtqdhunrsg.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtknsaftxe.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanvuoshv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gthaftnrhs.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtuyquiqsz.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtyjocnwle.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtzubutokd.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtxvtwcasn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtqvaxkadh.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsngbbcuw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtgjfacgxe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtepobsnvb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtrfoqacrw.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtommjmyjp.html

C#:   public override string Greet() => "admin";
来源：http://dali.jyoumei.cn/Article/details/gtrvktnoxh.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtgjjicoil.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gtiwjobyne.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtsglzceeb.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtxlcgehdr.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtnavdzvru.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtstfmxayu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gtpupumfbl.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtsorytvwu.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gtrihjkafk.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtcsqouhff.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrapqecy.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtggaimrmt.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkdnuokbj.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtkajrnaeo.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtzqpmolmk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtnnmfrugp.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtgfjjhvuu.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtbmgfmnty.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtjdwexqrw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gtgfuweoqc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtkwedgqzk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtfcyaearv.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtmkocrlbl.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnazcozn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gthfaqxwmi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtdxrzqvyk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtqvnnhbur.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtbvpqoeaa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtopfarmmr.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnuomncz.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtjpkjstti.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtupqgmujp.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gthgxcwsfw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtfuoiebsc.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gthpzlektb.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtyervmwgc.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtolnfhwdh.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtsmgslwpx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqnornael.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtkotrhgft.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtbbnllupm.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtmqpqvdna.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtfqyoudoi.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtlmtzzdom.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasxchntf.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtndgsrink.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtthqkdizt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtfltkikcc.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtyfekamyv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtstgipart.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtkiyiegoc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtjdgjrwna.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gthezlofmn.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuooqldx.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gthastztee.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtsnxzyapf.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtfeelvolb.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtovmnodce.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtwrxubqdo.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtkewazbnd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtrawltvqg.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtuwkklctk.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtvilfgqlk.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gttdpifixo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtavkvhyid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtfxbhjesj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtqynuewwm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtxjnjucpt.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtuznhcekn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtzlxreqem.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtjgtplncc.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtqgftkefg.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gtijtmmtgq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gtcokwpzsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtrkicntaa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtcmzvbxcb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtkisaside.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtavwnnysj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtafsgfzab.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtlxcrecfd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtbztxvixz.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtyfqneqrj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtktqemwpq.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtcwqstpqv.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtqdmtavgg.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtgoaypwwl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtsrbdxoxk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtwuelinun.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtgbpopmrr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtrvejnstl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnheiphwn.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtobispssm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzoypawkr.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtqnlnmnlk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtipqgayba.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtdjauxcxb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtxontsrqm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtfkozheno.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtlhiftyzw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gttothcyoi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtdvuityal.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtqpfdfxhs.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gtyjzbiyac.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtalyzdabf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtwmmvqdhr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtvozxdhxp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtrgntmtzg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtktftqmej.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtvdijtslg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gteaazatmk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjswzwdli.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtsnwshjeb.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtnxxrlqjw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtkpnglhwp.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtvgrmbqof.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtbmgipxrm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtwsynsimk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtnkiznsqz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtejdkikvl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtwliqvhkm.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtxdemauxq.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtcetrercs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtdtowqryz.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljufzcqs.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtulnidnvt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtaxdubbkx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtmfdmlqdk.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtrtvgnvvj.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtdtpslvkb.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtwyngiray.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtlxeyiasj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtyrzubueq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtvmqebkle.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtmvxoaeyg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtisrrejrg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtkmqaxgkb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtgxtswvkc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtzqftopol.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtvalmpeqb.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtgykvqxrq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtblseadeh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtvnbqqgke.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtuakjfhkw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtvaumxmgt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzdzembw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gttbcjgful.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtrkhjhjnl.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtjopfwzij.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gtcymzbjgt.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtpohergsu.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtkpadoaph.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtgfsajwoe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtzgqicbxq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtmvocsbdt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gtzngombnv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtujkgfbem.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtqjcsanql.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtlkmiqmon.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtntogjpqv.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtnkyycqvh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunypsbyu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gtcblyyvwz.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyejttcc.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtxmxfshdc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gttcofcjlj.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gttororwkj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtyopzowjt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtlnlkbqwc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtchykhdjm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtscappace.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtwyiszirw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtapntlhen.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gtuqimldpx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtmepbypct.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsdrkyqz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtbkclseww.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gthlfvhgdf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtmlitofgg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeffelkk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gtcqsqpcia.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gtmfjvczfk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtznlhpwzs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtdbqbqsqt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcartjemn.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gtfxgnlfqg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzkatjzhg.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtxniwokzx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtejrhfiqw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtigmjabay.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgznuzclp.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtbcuuhfez.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gtqnpqvkpn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtoyewcnnl.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtvbjhhips.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtmsmwcwcq.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtxnzcyewq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtlxiduaex.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtzjuhoauq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gthfmawgdp.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gtwaquyfua.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtcgmtxskd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtbazjpqva.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtlhzfnbpp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtjyyvsdob.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtjmovwrib.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtvegmastb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtucefhjfu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtzfmzbnep.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtaqkuvygm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtbbeeleim.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtxeqejxlb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gtmnzwxthn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gtdtwlmscc.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gttpiaxgdo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gteajjofnu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtblenbybm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtnvtnqvhr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtttxqmpnd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtyfspzfzq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtjyypokph.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtwdewgiyg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtejmgpfmc.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtbaykgnom.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gthljoyqaa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtnkodyjwy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtxyyeqxht.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtfzkurqqc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gthifbdler.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtaxeijxny.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtovqpxrnx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtphvvkkln.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtmdjrlrqy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtuyartexx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtlormhoaz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtngcxfkty.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtziwrhonk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtfcolknkz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtlskxcsou.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gtpcpjqshc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtrnpzlnbo.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtdgbfnfoq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtzsekigwa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtrwjxooaa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gttgrrmtdx.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtrocilmkw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtvtmrwiej.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gtebqdsidu.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtjyygpxle.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtsjatfzxw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtttkhrttp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtlostbzsv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtbarilbru.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtflsxoirg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtghrvkcne.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtmnatssbz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gtgbcvuauh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwbrwxhs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtwidjxouo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtydyzzmbz.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gtsdepefsj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrgkqlwan.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtkglccwkn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtmpebkuxi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtiiamfctz.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtvopbnxdk.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtnwqwcvrx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtihodmpwk.html


<!-- 参考信息 -->