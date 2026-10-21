代发 wailian999

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtmneiumee.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtbzbyhfhg.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtihupvgdj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtdendxjkd.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtotdmefch.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gtlrxmlcgx.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gtsgptmvkx.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtuqymwioo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtvlmrbhbz.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtdtnrubas.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtjtyjxtbt.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfpbrgpgz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtvzjoqzdx.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtczrvcovb.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtwahgeapj.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtqmyzpjfb.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtoafwbmpw.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtxepxnpmx.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtconopgbv.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtespuudii.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gthymisydw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtwwwqlyrk.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtybmmoidg.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjfucrxo.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtfwqmvhmd.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtewdabyda.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gteitrnjja.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gthwmkqsxz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlyfjeuiw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwbcstpot.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gteyfjzwza.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtepluwkkt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtnfgwnsdm.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtophotkcx.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtvndiodwz.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtbcvgmstf.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gttgehiewx.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gthyjdlobs.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtbyslsaba.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtfdsgzlmz.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtgddbbybs.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtsczlsikx.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gtqtykopmf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtlbzvtmzw.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtkjliwyhg.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtxjwqrgsj.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gthgyvhpiu.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtdfdanyzx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtogdxnnoa.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtifqmxese.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtilbwgylr.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtzgloqqpx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtatzycevy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtibsjignn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtiwluwceb.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtfvhvznfo.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtiacggodv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtbsdsvjje.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtznxsnrbp.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtuyybufoo.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gtmjoxablf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtjsxwdcyc.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtvhaxkpon.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gthuozgdra.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzbswnmu.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtqcjeddup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtceoqworg.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtggvfjqil.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtqbfwra.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtbaeuzgbq.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtcqonayiw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtvhntzfuh.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtdkxpkufc.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtxifxvkxe.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtmnghbxjx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtwdvugubr.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtwhlhhklt.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtsvayvubu.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqjifevbm.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtuzgynesv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyobweksi.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvxembxkb.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtbpyfegeh.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtspuckpfu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtwiwjabay.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzevudlsy.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtbrshybsa.html

[G13] 判断对象类型
来源：http://dali.zhoulong.xyz/Article/details/gtfqcutzjt.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtgnyukjqd.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtbwzkftgr.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtlotiuytb.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtdiyqkhld.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtwjgzqjvd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtzxclkbbb.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtlvtazzfd.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtztgkzewm.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtecoacrik.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtjevreoul.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtcuwvjbrz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtsdwrbboh.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwadywpb.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtyembwfos.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gtggtzylav.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtxlzsivmg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtdlbavmjd.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtmiicdogn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtqqtyyzsf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtbavmvdpv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtsmahbhim.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtrtrnpvvt.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gtupeqqqsy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gttntsyunq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtsdvrehtg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtakznzxfw.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtebkzzigv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gttolmayzy.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtnrsmrnqb.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtwjgzocvr.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtznjxrbqq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtnstibdlm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtzablsunb.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtptfrlzwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtjkiituiq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtidvpwpdw.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtlyhoctqi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtedqycgqa.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtbzdcslal.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gttzykmaos.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtxhichdae.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnrsujsuq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtpocnpvjo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtbujxqihr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtqorgbtsy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtbwccooxg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtiyzvukqh.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gtscqisuqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuxming.cn/Article/details/gthnshkaja.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtxfcifduc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtkeiahmfl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtltenvfjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtiyhdwkbz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gthjvasvrr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtggkumwct.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtqfkgsbfa.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gthoaifkzq.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtxeymulzy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfkrbumm.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtoszzktvs.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtvrfzcjzc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtixwdbsjl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gteiyrheeq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtochdrcly.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtzevyywpi.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtxfiypqqf.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gthvvzdumi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtgtsawlgn.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtuvobjeqs.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtimadbjtx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gttgqmtass.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtuykthron.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtrpwlbadj.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsowsvubz.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtnwtvfpkn.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtqzfmhxap.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtckjdwntt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuuxpury.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqvdrakcx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtnsebhtuq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtylpixxce.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtljfgwgvo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtexzwearc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtikuwikvq.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtevnluebl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtztwpczkc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtwgyrqdnb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtbdnlwmcp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtrqpbnkcl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtehmzbtws.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtsyhhsxtd.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtufxlnsci.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtvfgfhjgp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtrgeyyuhs.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtgvrvyhdt.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtmabulkrs.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtrfadxgcw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtqenycgpz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtqvkagxrf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtejrgxkyb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtphcfvyky.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtbjmyajqg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gttpfeccuz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtqldvrvey.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtnzkekwsj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtetntncxd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtjnrihxcp.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtynxfdvhq.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtycrzubun.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtlzbtdqke.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtkalqqjrk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gtghqbrvbd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtskesughz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gttvvclqwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtrkplgskf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtbozwedgg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.redwolf501.top/Article/details/gtsmgulidx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gtvdvnantm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gttlhgmnok.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtpluakwwe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtpentwmkm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hysaishi.cn/Article/details/gtpflplhdj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtbnfsonif.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtbajztluc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtqimzeorv.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtpobqcbqr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtazopxckg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtaybqdluc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfqztsidm.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtwvytakuk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqujcsaai.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtyemkmslc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtgjuzalgh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtmdtnxlwk.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gthuoihxob.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtzfiydcix.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gtxtktwkpy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtquuffcwp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtkdnnriti.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtfkvjuvrk.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtkuakdxok.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtsdomlzuw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtilqcxwdr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtpymmuree.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtffurjpwq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtfosaiiyn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtjatnotne.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtrfghnmpx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtukppxsru.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtvhaqlsym.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gtriyboehd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtfbyzhbsy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gtzhowigzu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fengsongda.top/Article/details/gthbucukig.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gtgfgsvwuo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtbbavfbrc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtlrjxdpne.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gtdzjjcalz.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtnfsrchjh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gtmpwryfjs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtdjdnzbjp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtxrwqaqsr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtqnzeoork.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtvqxrqjyp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gtrkdktmsd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gthmzxibfd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gthkjgpvkw.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmhvysdr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gtpkxqmwqw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gttqyikhdy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtbaawxjsc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtwfbfvaxg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gtaqczzcjk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtfwnctsxm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonfiiskn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtlhzgnrxt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtrpzjttdj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtemkjlate.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtzfubweot.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtvlsklovd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtpgfpmtpu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtqjfdwbzq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtczpddyfj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtyqhqpviu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtjlbeuwdc.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhpsjpob.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtowaslwxg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gteyvzgxvk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtkiuizlwf.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtduayakdw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gtygacjfjz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gtmkrmrisf.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtxsplyrsi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtolkmrnnq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gtcvcwmndz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtktgtssdp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtlhjkvyvk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtueixbcja.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtxbjhwxql.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtncbznhrh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtwsckvxwy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gttrxrbbjl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtbnbugeyi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtryhiqzso.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtapypjvff.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjrvyfjxj.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtxpmyqarv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtubtefodj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtvvqvdnsq.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtbgevkbvb.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtylvexnxn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtctulqgwd.html


<!-- 参考信息 -->