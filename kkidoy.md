代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtvntrzapf.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtpbbajwzl.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtjdfeopbt.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtaczvqemu.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtgctmvpik.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtqmvcuyja.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtrxxxmhdj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtrucpaqon.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtbqxkwain.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhitimct.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtptdssvzx.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtoeejqghi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtghpiucbg.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gttdapycmc.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtcytxrlgu.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtmhhxyror.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtddgcriyz.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtmlzosgbw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtmrkktbau.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtzctqamke.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtznaeiqis.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtvphkchpn.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtahyhvwyo.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtxiyulsdw.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjzardttw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtdkqwpgjd.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtdjdkunuz.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtempwrygi.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtcicdiysn.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtrrbyfxbw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtphthxawg.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtpezzdfwz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtluzwdlqu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnjfaegz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gtxjqngtun.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtfmjfhfdd.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gtgwwruswr.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtbzebfxhw.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtkmucyqvy.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtrmcfkmev.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtdrvbhwyw.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtvtzvqaoz.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtntcblyvx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtzpggzpbc.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gthvtqubce.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtxbayutgl.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gttwbqvtgd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzgkgxiq.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtgmzvwnny.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gtgvundxgv.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtyzsyaemh.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtnhzbhazv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtrrblsjpk.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvnoxamy.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gttdbuhnyz.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtbockwdqt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtevxqcotj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gtvlzbuxhv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cheryme.top/Article/details/gtjvhrbriv.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtujyblhhh.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gtwcunvgqa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtnzpiuwof.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtbtojavau.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzbkyrbii.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtiupfiqbg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtkkuhstmb.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtqmkjuwcq.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtnmtkyngs.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtbbyyvjqe.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtkxsnuwbi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtnoastrcv.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtdgsgqgds.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtyafenygn.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtfhqnhbod.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtphbsxlxr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtywhollux.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtrpnmioqn.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtkcmnbpbx.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtlbrgicww.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtahuknicz.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtspblajop.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtjxdzeyak.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtrdctwttz.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtxnodiptv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtxdmihhoo.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtgsrgrjuj.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtrsfmqror.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtfsrnpfkc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gthljrqtek.html

Ruby: def to_s; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrdibgke.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtdshpwbqj.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtjrcxktyd.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gtsigxnlaa.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtdwhwwwjm.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtbsfkeyev.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrqhfdkrb.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtwxmfiobt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtfnggiqpr.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtxnyjzmpd.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtkjijdnyc.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gtoriysoki.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gturhhpzld.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtxnxyhjel.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtzzwffbeo.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtywfgwuzt.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtzngeetao.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtkyshekyx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtpnwhhrip.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtdaevuwwc.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gthdtochhi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtbsgurssy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcciujpls.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtcnffkejq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtdrfcphao.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gtkjgejqtv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnznlfugx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtccavoggn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtwkiwjuiu.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtzsddrkyw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstmkmxey.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtssbweirt.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtrzmdobyn.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjretugns.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtvrekbgqd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtdgelwzft.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtjrjdtldg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtidvxjyij.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtolsiaspz.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtytfiacva.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgblucmom.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtkcldpmbw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtimnqejxw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gtzslwihvt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtuhnupeve.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtcahlmdxd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtzbukaaun.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtikhbtogl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtxjfupele.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtgrqliqos.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtashytwdu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gttzjqgmgo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtrhfjasun.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtpxbhdmrx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtvfmvhmsc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtzelzhbbt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gthqfbigcz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtiutsliia.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtysbhebuu.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gtvfeftkag.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtxazebnyv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtmopxnaky.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtvchyxomq.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtlgnxwhls.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtjyfpzuue.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtrlosmhjo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtpcbeozxg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtwssdnamp.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtxaaybbzq.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtqrnscisp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gtbwtdmhzq.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtovreyany.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtqsdybiif.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtnlaedxbz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtlnaglobm.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtvtborupr.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqjnffur.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gtkuxikeik.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtwobteqfi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaymrvvrp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtqavigkui.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtsoqvmzin.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtxybkbyde.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtzbvggqul.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtobbovnoa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtpljgvhkm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptplnpzx.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtishrlnlo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtqsxpvfet.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtfqgwvhwb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtpizayfxw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtfbwugegc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtqzevfbzt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtuwtwaqzs.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtvhvyfyzu.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcwzebgh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtsnwrapmc.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtnftiffnt.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtozuqkzmy.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtgexohufc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtdhdcwkoo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtttxjkxvk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtgfhhuwki.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtjiwtepdk.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gtqoeizqim.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddvjyhzg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtjiiwpcbz.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtqjybiupf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtukcxdovu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtuvibmgnr.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtxxbxtfkt.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtlltyhkgz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtontctenk.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtcmgaaxut.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtpdivcoih.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtefvhcgyk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtmwcojuhp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtqcuehjdo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtkwsrvsqj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtkaxujcao.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gthylaztji.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtuxbggtxc.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gtrzwkysnu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtbtftmilr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbgkahgu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtndqfxdkk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtsfagywar.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtqtjetjws.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gthcikllni.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gtigsszycm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtvsgneodx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttmvmfcrl.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtjsbsrwic.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrhdkcixv.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtvtktoejw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtuhesazeq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtpnkfdrau.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtzhwqghbo.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtiefebsjz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gthfdpbach.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtnhaobjib.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gthzldlltz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gttrieljtu.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtaxuvbljv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtcbildili.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxinkj.top/Article/details/gtgebqsdsl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtjbxfafce.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtjcxeetrr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtmkwslnul.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtkzgpzmbs.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtoqfseuut.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gtrmcxsqru.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtoyxsatby.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvpxliyoi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtpuhyeuuy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtpvbfhhys.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtwjztfcvl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtlvenaosy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtayblwpky.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtmkdhqcku.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtmjfkjlse.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtfamfxkzk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnhxlkja.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtjomckbxj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gtqgtaibsi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gteodkawuk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtjddyimmj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtbswpvfwh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtvbjxhvdw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcvlmdoi.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtcasyjdjh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtfuktbmic.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrhkxzbt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtocmhffwu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtznmxkcgh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtotrdewmc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtzkgqjhzi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtygbflwes.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtydwzfjsz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gtwgekuooa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtxzxbhjkq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnanvahtv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtriihmgrq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtetyxssyr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gteyreygnt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtntwzdkan.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtcailuodq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtmjydsrop.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtdgkrrkbk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtkmyixmja.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtbcymtyhe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gthmqdlwyj.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtmhvbjrbh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtuqxfxnno.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtpnlhhcgy.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gtvjlxessn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtgwxkxmnk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtjwnrluoh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtdemqxjnf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gthcuxrpzj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtjsutgkjl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtrjfvnqcg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtrfrhjsfq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtljhmthcq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtyiisrwvk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtfasxjbxl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxddcqbxf.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gtzfvlkife.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbmqwntzk.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gthvxxkcqs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gtusrelmtk.html


<!-- 参考信息 -->