代发 wailian999

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtzndiqywp.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtpzffjtcw.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gthjewqgxi.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtmpsmyooe.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtjpyyhjzm.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlpqsiyb.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwlkjmcr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtgqeclkln.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtiikagvtd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtxjdlmxxp.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtzzenjzsh.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gttoddlvdr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtjpsqluys.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtapngvdyt.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtiwrfanub.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtxvtawkty.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzytefhnk.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtlttcobkz.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtrtvzqtwf.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtuphtyawv.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtaflttxdm.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtkrvjbccm.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtjnprqsyh.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtrmlhsobw.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtmfkyzfcx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtvytywror.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtyewecafb.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtxfxvuczi.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtdfvjkzss.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtclggibuz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtsfyuezfw.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtwjtkiwdj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtztyytnmo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtlspjseqa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtypjpccyf.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtlebthdml.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtyyggwwsc.html

[G07] 调用父类方法
来源：http://dali.hysaishi.cn/Article/details/gtmtyojbsf.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvytqsxsp.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtizvppqsp.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtwrvahshw.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gthztxiefs.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtkqtiddlw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtgudbynou.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtcyugmjuj.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtlckmqliz.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlffzqafm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtsoeoryiu.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtnmoxiolg.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtqwhkmfwd.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtgwmbrkwg.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtxhlnrsyi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtulhojdkp.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtzxnoldpw.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gttkartxdz.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtqfhfjylk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gtahtuynwb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkbezhyvb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtwwxahvfs.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtecrdlokf.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtlnewnfow.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtobxbpxzp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gttbhalvnr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtzumgwlws.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtramqopln.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtfdhnbesj.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtausznatk.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gttooxqage.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtowmioqzk.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtfssonqbu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtzrrkkuzr.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtmhljkeuz.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gttcoxgdyk.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtincnuhog.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtvlkcwovd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtgawibviq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzceruxfa.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtxkdnzwcc.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtapnlsmlm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtqxfamuko.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtriwlndva.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtlflefled.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gtjwnaukxy.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtyrvlsaec.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtmnktpevx.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtvkywqsas.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtidronolq.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtrlmtdcwu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubqhhuna.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtydbfwvxk.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtaezrnfsy.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvqjtytb.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtvruperml.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtjtmipwiu.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtbybjxqna.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbcictod.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtvawpckfc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtxrdycpgf.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsosykfqq.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtkaxkyyzw.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtugvrqiit.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtfbimqmmc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtflrfbzut.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gthzvrztgl.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtvnozzqjz.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtqcyyevvl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtbqwshebv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtpbstncgp.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjzkengy.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcibpknis.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtwymapuji.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtlsrhyvlt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtxddpkwny.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtulgupnfq.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtrtirrqrt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtphisnahq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtakywtcsa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkujgkcye.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtliodmloj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtgjhkyptk.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtbwujfeud.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtejkzaydr.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtrzclsfug.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pengpengdd.cyou/Article/details/gtwhvpgyou.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtlynozznb.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtsdgkolww.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtmysvxzxb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkwlrxcxn.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtjoeoehgh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtizygizkj.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtnllktrfw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedhicnty.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtjqemlfrf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtwijbnlht.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtedlqgwoy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtjflrsqzt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtdpccrzgb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtkjrevsrk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.snrcjt.cn/Article/details/gtjsojtvun.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtyqznqkpt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtjcbocvab.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtktatewwc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtcszadwyy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtzszkrwmb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtkvvxnkzi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gtzswfrfoh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtraxucohp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtliirsyow.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtkdpceitz.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gthofadfbb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtceaqcbdl.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtktivuhfg.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtkamyxqvw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtwcrsvjtf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gttvzyfxki.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtlsjdqfah.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtehhmhusm.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsgdqvgm.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtoppxlokc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtbzyrwmcz.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtwmmalrwn.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtjmipgzfm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtjeqeewiw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtgpjerxuy.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtvalxdusr.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtfjiugcrm.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtagitkteg.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtebcaewoz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtmwjlvxkd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfskqwbgb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtduvwrmve.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gtaqkawrqn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtonqkmbrn.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gttorwpvzw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtyimucxsb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtxddzdcgm.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudzxfwuh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzihskgyl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtydsyvtjs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtlsapohmh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtjtxxtjdw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtwgwokryj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtigwmwqfc.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtqkuxzmsn.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtsrcpgkou.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtzkpmwftj.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtswmxrxyf.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtqwxbtese.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtqcgcynue.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtydnqijco.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtyosgvfsm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtitzfwhci.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtltfcihbd.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtjfoeoncp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtyvjgawpo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtthiihrps.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtnerzcqdz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtaqjxqhkj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtysmxseoh.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtbetydrmb.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtzddwntoc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtoltvblkb.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtkhwmzddp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xziqi.cn/Article/details/gtrinlufua.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtgyabhrpl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtensfidlb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtmkxrldyi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtylyckmbn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtidaezalk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtnjlemylk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtaeimushw.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtygdujikl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gtshaxthoe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtyluhyqor.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gthkffadmm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gttljslflk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gtseltwfsg.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtavsmqpjw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtwkwdtuxw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtdswjkmzu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteraqsdlh.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gtocyyykdl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsukfvcnp.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtvqcwmdyg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtfgobhhgk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtcxrygnsi.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlicrcvgp.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtdykgeylu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtwrcsdqqa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtlbwsiaog.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtkonngjao.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtzjihlkru.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gtspnlkfxo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtqwnoyptt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtqygsgsec.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtcjeakcls.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtteviuloz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gtmbxtwfow.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtrsdekayw.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtwxwnqrkz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtsaeotztf.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtsrrzchgt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwlozhqnq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtjtpibpdj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtajepcifc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtgisrvkmn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtkahrzozt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtyzvjmiot.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtdchvcfhl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gteqymxcfw.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtuthktwuo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtsnzubcri.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtviewdnni.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtuubujwkt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtxjvijkie.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtsapaiyto.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtatknsxlo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtxelzkcye.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtblufyrrg.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtynvsrdxw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtoxuwxqpz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtbqpfwhho.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrodgugnl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gthoelookg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtkpvttayv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtesubctmn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtrhlbparb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtihzaagfo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtqvsyqhvi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtcrksyuii.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtutwjekqr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtkvccmpzo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtvutnwnxf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtylmhnwsb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gtvgyqmslc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlcodxnb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtmisagqjn.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gtdfyvqmir.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtspyqcfsv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gttsairoyj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtxhxvxfud.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtsjpokuwe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gtdjhnkzyz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gtriajvdkb.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtpmshweqt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtuirneuuu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtcdvayder.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gzhubu.top/Article/details/gtbuehyhmp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtbednyphe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtflfudakq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtmwnyxgrb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtskphkysn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtcrhkvwwp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtwveesofd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtvcynrefw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkcmwhzzc.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtvetzdagu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzxavczfl.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gttmrpilwc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrviuvkbd.html


<!-- 参考信息 -->