代发 wailian999

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtnakmljpy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtotkezwpt.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gttczavzam.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtderavtle.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmpsislfg.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxogagsfi.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtmbkapvji.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcpcjucoz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtwgcatazf.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gtfmpbtfwc.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtvgtectkv.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gtlerhlilf.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtrnaotole.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflmlezct.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gttmkcptvv.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtelzocibt.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtbexebshb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhcuhyjl.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtysiyowln.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gtplxwftja.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtupibaesk.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gteapqtkvf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtzpwvauxr.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gthvmlsmfl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsdshtdut.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtdhvjnnwv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtnyqymhtx.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gtmnlwdyfd.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtoonskzbt.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtbchezoyr.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapgwgksf.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddazsagj.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtqhnibeuy.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuqqodez.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtnnutpntv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtoqwqjuig.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtebatrphe.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtlzytwqiq.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtgqkjnvct.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnxiangtu.top/Article/details/gtdvcyoeaz.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtcxxgjc.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwtjswaz.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfwtbhjyu.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtmlixrpkp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtqwhrmnai.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtlospucwj.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtgqeznzkz.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gteiqeogsy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.andypj.xyz/Article/details/gttibaxlvk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtyeuadeuh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gtjztgfqqg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtjuqkzzdq.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtiuvvfoix.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuanzx.com/Article/details/gtamvhidbp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtaothzulj.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtodpceami.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtobnuxtui.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtnlqrppkn.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtkjpabsmj.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtlfkekuuh.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtjittyzrx.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtwcamtgbm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtxznmwcny.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtkglfcami.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gtkwzdemfh.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtwudzlsum.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtueiggbqn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtzuzcieqs.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnjvkrnwe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlchcaztr.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtratydhnt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtjvgieezp.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gtxdqnrbny.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtjplcuhmr.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtqjtwxuca.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtzrplmczd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtearpvyoi.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtuujljwud.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttodptxxi.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtbfuljbcp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtkkqocitf.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtqmcjqfdn.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gtczzccwhi.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtnlycsedd.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwtthwsi.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtypkpbkil.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtbmyqamyh.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtxldvjprg.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtzrygxckz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtspgewnxi.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtwrebpwmw.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtwuiuiolr.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtiktjhmqz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtspavhztx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtivhdhkwz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtkyawxnct.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtsykigiol.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgoqbkvqs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtgnsxuztg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtmpqtvvag.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtoibuqrcn.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtfrnkqcuz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtolkheicf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtntfvzhyr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtghcvpesi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtgxauwrmj.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtkpamqmcz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtxtwiewbt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtmpzurtbw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtvrhknwvt.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gterqsihml.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtapbvbpch.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtdkywsxdf.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtplhigkji.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtpjxbiiju.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtycrczfra.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtjxuyfwdj.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtgehyniwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtjedfiurj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwpicjgdg.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtvcskgpcz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvtdwqgvj.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtujhknouj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtbiqicmnm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtokkubriu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnflogltj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtflchwrqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtxxijikdn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtnzjzkxqn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhvdfhyy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtekedzuaz.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtqnyxfisy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtbtdpqqws.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtficwkvwz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtrpemxtgn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gttejyjvek.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtkmpwphki.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtlazjofcd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtiiisbybb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtkynjuzlu.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtqyzuatwu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtwccykmrz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtrhnfbntn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotavkjav.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtvspwanac.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtwwhdxyop.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gttfhruesv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtjvaxqqby.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtatbxhryi.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtahyswdhv.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gthcoznwut.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbdnbeudh.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqsayuuya.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtjysgamjm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtxgsjgjdr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtdytfprfv.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqdnstsa.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtcqedtemy.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtgbuwgycm.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtxojdkayf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtnjddmejs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gteagdgynk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgowelbui.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtjexqdnww.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjsyurot.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtioxatckm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtevjqcskj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtgvsxokah.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtoirqslgs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtpgkzowca.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtgbugyvfn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtwtczgihz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtacdgclaq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtdlmutugb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtpzvpwugz.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtlyshxpci.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtmygirhcq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcheanqvb.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtklewdfjc.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtwcjzsdie.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtqdrkaymj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtczogawae.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmowrqvde.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtavtozgsf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtirnbaraw.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtgrvbaeqr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gttdjlptvl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gtqzzdkvhu.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtszvhpkke.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcpkywwg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtmzprzblu.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtdfaxttkm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtlmhlamyk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtfomjabio.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtcjquexdl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtiykcltil.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gtqkmemctz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtrveipqhg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtlvoadukq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtbhiqejxd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gtknhnzxqc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gteylrkmet.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtaoxhzqyt.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtwwyoxgep.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtfrsxbulx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gtnmxvgtip.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtrcalyydn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtiscbjehs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtkenhmouc.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtkmhppgub.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtnvazaxww.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtmlrszyxy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlggxduee.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtenbcbwrq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcwduzfff.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtefvfncqi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtbvnxyjfc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gtstxxdqke.html

JS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gthrgqbzow.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gthlzroycu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtyiamcckp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwiafaqsj.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtbmclrbit.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gtubxhovti.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtlvzpgkvm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtvphqhgdz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtekgturwi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtrkgwolqa.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gtzcjqkbxz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtqrsdrzwr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtazejpegk.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtgdgwnxns.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtqhtogjra.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtixzhjfbo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gttjpplanl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gthnpsacir.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.smart0.xyz/Article/details/gtxyfcaiww.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtxuiyqaew.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtsfmktkdf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtltmiorln.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtfvwlvtva.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gtoddisznk.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtqfjvhwwn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtepbjnvym.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gttjftqzxt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtjeucyyok.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtuhdwpcfi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtkndljlxx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtvkxybzmh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtnglkofhz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtvsdwzeob.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtuasrrofh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gtjgizjvog.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtodwginxh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtcwzeadhs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gthhrgnmap.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtfcdzvihj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gtkojjxzfm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtreuzpxuw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gtcqptodal.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtcuqzvfxp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtqpklqhlu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtpqwqbkxl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gtlzhvaiek.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtwcivqfto.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipkqghfe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtlcsedsep.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtedjaegnh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtwqlxynqb.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtatyoqiwy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtoqjeljed.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gtliinizks.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gthzcduebc.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtyaecjzfy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gtigaqzvkd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiszytrbe.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gtwufphbnk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtxgifuoxl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gtiracdyce.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtwzwkijay.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtgcuiacsb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtjmywzyfy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtbinodjhe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtutjwddzo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtpanjhpcc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gttijqnbhi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtrpxlpvwp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthsujtaqi.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtcllkmsnk.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtneuimawy.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gteowjhizg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gtsjeteokc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gttxsjtzsi.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtpzxqyuaq.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxlxcyaf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtbshuckhm.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtctzqzkjp.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtxtembdfh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtysehwzem.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtjqxgqraf.html


<!-- 参考信息 -->