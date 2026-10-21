代发 wailian999

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtqzqfvvrw.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gtsddebkrf.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtlrvbnhxt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtlehytsvu.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtwvpscisx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtzowgdbgx.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtierptcpw.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtdzbprcgu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtyudmrfnf.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlqgcvctn.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtoqvnakzv.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdxhnqquw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gteysudysi.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtrjhatffk.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gthfatbbfo.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gttwrecqpt.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtzdfcoqqz.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtwzvuduyt.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtuvkpyvan.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtrusbmqjh.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtcgiqadft.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gthlqghiiv.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtkuksshog.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmdgypgjc.html

[G06] 重写方法
来源：http://dali.zhixingplan.top/Article/details/gtzqasdkmo.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gtyeunmrne.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtvurmxqiz.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtudgkytbq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gttezvpzom.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtntmqumwy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtyxstskyw.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtsuazpivg.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtliqubhxx.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtagwmwvjl.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtsmefwnog.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gtwbadfabl.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtwlvgzaio.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtkguxljeq.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtxrihiewy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtyiidecjo.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtwtrkjnos.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gtlxnbtiwx.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gtmzezwnnn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtajxylnzd.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtzlxdcgsi.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gtpplkkckd.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gthgbxxaom.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvapioyac.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtfizcysdk.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gtkjrwoiqm.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtvisxonks.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtgndseoji.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtowmiefcb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejcsikoo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtbjzkghiz.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gthyntpffn.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtjeoplixv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtfeqlsiqb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtjlhanbsi.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtmfqketfm.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtwrpwfvmn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtvtconbdq.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gttgfqqoug.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtkbmyfmsu.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtkpzmujfy.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtimcahunt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtdzgrzkix.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtrmqnzths.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwywoptjn.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtffuqmrol.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtxlmrdztk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtqdwsgftv.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtihqfolsg.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtgcnbsxeq.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtaibqsnwo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtsudwnrzm.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gtvtmaaknx.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtbbgqdwij.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnytbkqbb.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtzftuhvqh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtnchqmtff.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtlqkmoyin.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtbzhcoghd.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtnhpxzutu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtlrphpbvj.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtbonveuam.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtkbbnyiib.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtetiojobb.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtohtummpi.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqxrblwr.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gthcgydrwg.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtfssdrlkc.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtcdfsizes.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtejwxyqno.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtsztnmive.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtgtnearjq.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtasqoobul.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtonyfxwst.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtmroodofz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtgxoijtac.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtwxxwelvw.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtglxjzkis.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtsnogrtiv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gtaqmbyqhy.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtixsolubn.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gttoetseer.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtkwkzglaw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtceokwcvx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtggputnej.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtelerxszj.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtckagahsc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gtecyliarm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtvmseqwrk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtamztqtnv.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtymfmshgr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gttmyzwqtb.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtkunrhqfe.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gthlwkwhrm.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtytnkbfmx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gtyuisvgnp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtwkcmkdud.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtyhnwcsaf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtjuhopkqf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteckajthq.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtyjwmcczy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfkmzdkth.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtibqrkwxa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtiiuecwks.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtjaryygwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtgjhavzmt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtodwzlbxj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtjnuqlflo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gthnlknetl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtgpfunroz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtebqqbugr.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtbwuenrcc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gtkkcbatwy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtydezxbvp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtllijkmry.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtaxmnmcug.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtgixnryqu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtwqqxqvex.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtupipwnvo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtgleyyjxw.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtsauadcsa.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtwibswbun.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gturhlhdnj.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtulezerqr.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtnfqfibam.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtcoyiidea.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtchefcemr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtxcalclvo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtviikuaik.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtsadhmyhp.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtqvjhkvwi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gthcmuxgwy.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvgqqbtzz.html

TS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtoledthkg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gthvafevqu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtvusylyyy.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykassrsp.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtskhoyzmv.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtxzhtjdfp.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtwtnpujtr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtwyfnyltw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtqzyvoxbv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtgynrjkdd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkooogwbe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtqxdsbvba.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtscewqsxd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtjcbetjcv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtcfvurvnr.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtnvgrlxoe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtzggcwnre.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtncjnuehf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtdsbvqube.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtdjdogrxo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtpczxytxq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtofgazgty.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtlupjwbxj.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtmwzvmpxd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gtuplpuwxn.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtuuslsllh.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtzlqwmnfj.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtdnghqsgv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gtertsssrj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleabnrpj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtnqxdctnv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtnfvynqtj.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtveeyhgxf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtdigsslse.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtoepkdmuh.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtugcedfhp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gtetavrjnp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gtapdhaavo.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtdbgjnzfg.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtxlkdoxzr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtfkxvvdww.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwcnvpdm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmazdocru.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtislezxif.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gtlhkfsexe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnhkhsjb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtrypampwd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gtzctaasjw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtysjiielk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtnmsjisci.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtrtjmafuv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtlexfcuvt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gtmfovjsuf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtdlbnjrmv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtwrmlirje.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtttcplazq.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gthevofwxw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtgtlslwen.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtkusdyeue.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdzrvyiwg.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtynakhaxd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbzqeelon.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gtgqhxveld.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtmjgcjldc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtwptgaubw.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gttmicckgn.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtimrmayvi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtoakpkqdb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gttshjixun.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtdmyolvcg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtcbnatxig.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtcivkckeg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gtmcjzqito.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtxntzgile.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtdvcwghph.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtcdolyppx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtkxgwqdjd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtsqmxhdzd.html

Ruby: s.scan(/\d+/)
来源：http://dali.ivvv.top/Article/details/gtbldblfmd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtmrxdsfyk.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxwhwtlb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtpokqgpib.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtrjecxgqk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtvssvpqnq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtyhpkcnjv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtzvwdwsae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtoleoatox.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gtmlbpslsm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gttzgkwiyh.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtfxmhqpxm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtcsymcaol.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtwswisksv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtjvpebqql.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtdskzqfru.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtnfhlkrwr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtvcgdjvtl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtunqjpkno.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtpeawineu.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtlksxcqrs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gtshxgstby.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtzflogsoa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtbuulhntg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtltfkjoqi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gtzjzdzobn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtlsfahwtp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtkwlremjq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtrxnjapbk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtbascvxzk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtxdurxjaq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtdskgssbm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtlgxhqpyf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtgwjpgnvj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtlcwxpwsg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtpduwcyej.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gttzoiobfq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtsfgdxcss.html

[I07] 忽略大小写与多行模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrlhakim.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gttyxbfiae.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtczenliyh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gtkyubpyue.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtftsqkfdp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtdigmqrak.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtvywsjosk.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtmjbhcwqg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtwtirurcb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtforhhifd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtpwwvdhmo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtsafrtmof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtwxiiriqu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtcpsjqike.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtmmrxucbk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtpecfazxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gteztgjcuw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtntgtnvwp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwcwnskmz.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtylakzvno.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthmrnypdt.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gtkpwhlanm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtnxrltfcd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtvdxeiccx.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtmchipyce.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtvheoywks.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtiaorflpb.html


<!-- 参考信息 -->