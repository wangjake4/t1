代发 wailian999

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2hxpaydrc.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gt2hnezawmc.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gt2koiydcxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2deqogbhh.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2jnwhiveq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gt2ckekskjh.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2ewugvlpm.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2kkamepdm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcjkymkc.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phiguwhm.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tngayzyw.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2unwqpbwv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2erwnbaeb.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2vhyweeqt.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2retxknnk.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stvgldtk.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gt2ogtxjrlk.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2jznaxqhb.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbdrtyyj.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2uyglhosh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbduszru.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gt2ckdxvvrm.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iagudewc.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gt2rwkznewd.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gt2zwoghufy.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gt2kdrubiav.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2sujudeio.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2erxaweei.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2igufhhgx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2qzsjqecq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2frssdaer.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gt2uciktylu.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gt2xxnozwwf.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2zwnxgewj.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqcbupvg.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gt2uatvxebh.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2pltmzznd.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2surjmxvk.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2mhxvylff.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2oywnuzza.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2wwdrteeh.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gt2kzevvnsb.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2gvjqpelc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdypzpld.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjoszkdr.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2dpctvgdn.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2vmonahrw.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2cwvoccmp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gt2fchhqtac.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gt2qybbjehy.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2bxublgee.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2ogrbmnyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gt2kvwtvmms.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2ourqtzov.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2izduqtvy.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gt2vxcannyl.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2hjsoavdm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gt2ijrqllse.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2umpwovid.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2dttxetxd.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gt2rtugocwm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gafrotzm.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2ktjyeevh.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gt2iokgvojx.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwldxzlp.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2ydltpdij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhvtcipl.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2suqkglcy.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2fpiswhus.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2xierujdc.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gt2vsstjevs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukqohjne.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sgxmtluw.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2zwebwxjw.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2fpjrckca.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2dknrkweu.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gt2ymxjzkcm.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2ujhvsuhh.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2ggbvaacq.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2kczvdven.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2rwkcexlv.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2igxmpsaf.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rtulahqq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2uuhpbrwf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2wlopyvyb.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2qfegiwsn.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2hxwybugg.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gt2nvikeycd.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2skdsemso.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2woutfcbe.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2kgpzyxek.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2axuxpels.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2kezvcqab.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndwrgydo.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2jtszblku.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkmewoic.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gt2kzfkjhud.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgdtjsje.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gt2aecyblhg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktqaicyd.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2atkbqbtu.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gt2otwkjusv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gt2dwrrwmuh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbuwcqea.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gt2oedluwgj.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2gnwelvig.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2cvdhtmrl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gt2qcdvphez.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gt2upbgreyb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2ziacausy.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2dhgbcijk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gt2bkypwnxy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gt2fzcxvnyu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbblsarh.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2oijvyaqc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgqhetoy.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gt2xegociwn.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2jjccqzkv.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2jhbscsyo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2bqaiwfzk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gt2dvduguyg.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2mueikmrs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2tghiaxwk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2rpkoibtz.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gt2vkrkwgqd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ykuedalo.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnjezaat.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2hilxcxyw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gt2qgpasnce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2lzdxrdph.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhzqwdko.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2myqlzaex.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2qfmdqcds.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gt2rbygjezh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gt2goqetltn.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gt2iirrclwt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2sybvvloz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xgizpsgu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idnxqtac.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2gppfhtfw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rirzlgkl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2uvuubrcg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gt2xyvlcmru.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2uqjbnbgo.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gt2wuvqdmvy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2ucdgcuhc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbewpls.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2qfapfuad.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2cttcxyxg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2hxhrnjxm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2zqwjxkir.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gt2vqziqenq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2bsnojswp.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2hwhvwlya.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2jbmuxdcl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2urrkrmpj.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2icxgtalm.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dzssrvdd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ggjjissl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2qkmebpuw.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2vmrrumkc.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gt2uzlfzlrc.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gt2rxfeuvjk.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gt2qdisysej.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2lxllqtpv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ykjijvcq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2jyeepmmr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2pupaioxg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2foprbhmd.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2tzpgpuhg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gt2hplydxmd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gt2ppczwgsp.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2awjaydmm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2aydtfccc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhygmpep.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2wzytlvda.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2eonhcuvq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2bplapcwg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2ehagdioh.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2ecplacjq.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gt2qfaihsoj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gt2bfhxqbsn.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2dqjrfsen.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrmncirj.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2jhyqnwfw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2kperdcuy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gt2uofjrops.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gt2mfliyjhz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2pawmwbax.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2asbywcmw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gt2pxrevniz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrdzebra.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2zwyzedqc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2wzxiiaub.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2fkngcjbw.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gt2hbujjiov.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gt2nwejpyro.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gt2uoyalvvq.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gt2uteeygpn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gt2kdidsoko.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2rebzlnwy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2drukaglj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gt2ckknwegw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ydwwhqyv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gt2augtntto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2kbsltjvc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2vctfqrvh.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2yewccrtg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gt2rrhkntwo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2vybafqow.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2xsycockj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gt2emcqtcjx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gt2jksxfffm.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2swagyqfk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rebnxvtf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2pfzbjuwt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2mmlxbcyl.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gt2lpqflvbv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zgjaecmb.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2snxhcggh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2wcptnjpe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iilaporc.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gt2uwerwlhi.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2pzttctgl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2cdjtuapb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2uouuvhdz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2xjbmawvb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gt2ljyfbzej.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gt2tbualpcy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2avtbfwlo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2jysskvmy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gt2tinxjfwn.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gt2rxoratln.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gt2sgcktoos.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2bptjjtgh.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2phfshtrd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2xotctqgm.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gt2kbjaggft.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2mjujuubz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2mxsdnbzh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gt2vrlxdgav.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gt2uhpuonpw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2hdgbdkfu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gt2hhhagkjs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gt2izprbays.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gt2psrcetjz.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gt2zevgcspr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2bdrtiymo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2sxjrcwbr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2txwbitct.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2xyismxdp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gt2xlpctqhs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2umkvowpu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2eyoapohj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2clvmxnev.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2dwilonnq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gt2fhwhcefb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2mkfnruwx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2xmbohcmu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2oqwjhilk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vllnpovt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2igooxfdv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2vwsbgbbd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2qdmsxtpj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gt2lotryimj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2tawvheem.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbwcuanl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2pjylgfle.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2bcqsjflm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2gfwnldig.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gt2tgumxalq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2fmrvkprt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2fxwowtgg.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2qennayvm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2sakmnukx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfufgduh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2uennsywg.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gt2tscfusnj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2mfzqivdx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzrvnbce.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gt2nrlbkygb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gt2hfztajup.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gt2dawwytlu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2tuxmgnza.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gt2fmxujryi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2cdxhipwi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gt2seyxhbym.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2bfjaaqgk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmymltc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2llrxnnfe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2yiozdoxw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2jruaacxs.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2vvfgwdke.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2nnitmvnc.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2pfodwyja.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gt2jjuarlpo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2eekdxmxk.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2zyhnppuo.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2frtqfjkb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2ykwofvpi.html


<!-- 参考信息 -->