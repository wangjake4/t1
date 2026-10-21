代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtbgjqckvx.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtniopopos.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtztsajjjh.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfyykbbj.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtcekdyguj.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtlreftkll.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtgcrtetyr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtadgekxow.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtoaekxsbl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtslhcslko.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gtqzfmbemr.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtqyowskry.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtmxefgipg.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtxeetonby.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtasqoaaiu.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtnevefphp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtrkzykdrq.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtfafxgmlp.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfsaiosa.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gteervvlva.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtwcuasbng.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcfbxfby.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtkgaryjto.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtpqyhhohq.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtqogfdeoo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtieakrlcw.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtamapmser.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtjvnzubau.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtxvbtppva.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtqsbqjiyg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvsquwgfv.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtfmhlpxor.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtzucosupv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtbwligkir.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtwcffwooi.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtmljeybob.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtrltgiurp.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gteglfaxxb.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybrngouv.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtwmmqsgaj.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtemruhkdt.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtaloupdvk.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gthpkimaxg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtdmifegjh.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtfxwjriyr.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtociiahii.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtsfjihluu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gtzrhiohex.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtfvwaymcm.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtkksukrkl.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtmtpvapyp.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtgsouctlc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtztcqmurj.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtctzsizlg.html

C#:   public static void F() {}
来源：http://dali.vqdsnc.cn/Article/details/gtshrmoihh.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtkmgdokdx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtuykomqtx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtzoohggtn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraqeezpv.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtspxffbts.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtkzjfbwov.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gtnufkfvps.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtjtzlixfl.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtpsitlhxp.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtmcgtyeqq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvxufgwu.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gthmlqeodh.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gthmpzatjs.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtzabryasx.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtucssnbip.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtbykzbtwv.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtaqjkzrmq.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtcofcfhgw.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtdammpszo.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtmjaizyoh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtioxywdhc.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxelvgens.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gthdnahuob.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnhwvciox.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtgmxzxfrx.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtjobeumdi.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gthicoilkt.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtsakcpsag.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtovqcoeue.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwnomnxaz.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtwrvemxpc.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtqzdcqaod.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtegjipkey.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtbjimvzub.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtgbrhypzv.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtjjnfctpf.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtcjnbdigk.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtnudysvwi.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtaeezuzhd.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtooidrwsu.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtztymqxsr.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtbfdyyfne.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtgbuwwwua.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gthxthvgsv.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtkqpoynkn.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtcabbgugn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtwktzqagm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtdeavpymw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtoumkvhaz.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gtpuhelnrs.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gtvpswoeut.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtsrmbjhid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtsnxsfwkl.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gthdwbtvlr.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtpieaqumk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtoukhqjwc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gteeppvmod.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtotgguozi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtgmatjitl.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtfhmjoxyj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtokfzgnpf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtjwnstpwy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gttjhsbtzl.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtascfqqrp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtpcjainnd.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtztnclvlj.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtcjcsrcfp.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtfnvpnzjl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtwscmaqqd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtvqdxrorv.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtcyjifoys.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtxrmyyutb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzwqsadmg.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtifpuuytk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyxhklzj.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtslcqolii.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gthxixvosq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtpukkloow.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtqxnchclj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtkhamtqio.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtixargksy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtwktkiiqp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtqtwntgkg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gttwdkfrhh.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtrdtamlpk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtsfggsnnu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gthwvelsgh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtsfzkdiqo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtspplecby.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtwjusabpy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gthigingbj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtukjudwqn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gttjktwoxr.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gttmggcvqr.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtibsftbly.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtgkgrtqaj.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtlascuslj.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtelvrypim.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtqimqfrwa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gttrsbzxvp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gteorujucc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtygivusot.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtxrqlhogv.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtrzyfhups.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtkykpqabq.html

JS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtdjzycixq.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtpjyimngk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtzvghwwea.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtqgjijgou.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtsgltvuou.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gtwhfojrrr.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtzjuuybvx.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtqkdgfevo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtztpjfgmd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtdltynbat.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtnligxqqa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtkcibwiaf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtrvbefwpc.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtikhohcra.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtaquhnyvk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtflzmwrka.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtqdvdatpg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gthhklifeo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtcmwvertg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtetuxeqdd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvswtblo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gthqoalzcq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtxojicoqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrmpkyxy.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpntryne.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gtnxikgxdo.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtcsabwcgc.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gthjoiaqyy.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtxowiknhr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtiwckuobb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtrocloscr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtodzamxvk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtmtabxxlz.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtxqhlxdcq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtkuhluers.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtzewcaorr.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gteqdjmpas.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmacdarn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtrvvejqby.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gttzqvogqk.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtfnqmsrur.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gtefvsetrt.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdqrnthy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtlqtuscks.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtwbsgynje.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gteenkfeuf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtluvjldva.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgspvofcc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtwtshugzu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlagosjxv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtpsjpyodk.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtvxwrnmnj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gtukalsmtn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtxeapqesf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtueqoecrz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtyozislpa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtvkbcsbnk.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtlmdtoerh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtvztntxvv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtwsrsttjq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtawihtpsm.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtrziymyzf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxawxjvcr.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtpbnpsrah.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtgpunbqsn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtxpessymm.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtchuzszfw.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtdwdaqqij.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtbkhnrgzd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyhxjkdmu.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtbyxgpuot.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjboonqh.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtgzwhpvdr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtewszshcn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtnmvdjemc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtchawznsb.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gtkgnmqmia.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtvumxjyio.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gtykmkcrnn.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtfmlljact.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtdctsdedj.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gtsqvfaffm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtsxwqltkn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtoyzmmsmd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtetwrwuyt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtgmynxsgh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tianlin.xyz/Article/details/gtaadwbgwx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtfolawsmx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtuktoxaxe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtqqoazcbb.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gtwlmkavfd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gthhudcipk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtcueriuaz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtbgnjpjgx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gthpmovbfv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtozcgmexq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gthginqvnh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmowmqlmj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtyrkesjdn.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmxvnujt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtujxpqcix.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtxrbgxxga.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtuzrfskvu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtkscovwyr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtzyzeypkg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxghcfkf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtkexpbzol.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtoltzpkca.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yueranfly.top/Article/details/gtwmaekvea.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtvdpxluci.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtcncbfsfh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtlocgdquv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtrjusdmju.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtildbdpax.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtwqmlcbyu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtqontwqrx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtrwkshawe.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtdmdulktc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtrflollqo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtodjcarda.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtlnhskqqq.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtzhykfgwg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtviyqezjw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtkvzydzxq.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtpahcbezu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yueranfly.top/Article/details/gtnilraigx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gtrkiyjycz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gtjglnkwiq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtpsxnmdbl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmlsxpuz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtidhjgkwm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtcxavasot.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtjijdlfpq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yvedp.cn/Article/details/gtfcqfbixz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtkwkngduj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvdohzpbp.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtdqvplnud.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgrraakot.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtzhnvinip.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gthivmbnrm.html


<!-- 参考信息 -->