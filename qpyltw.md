代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtzbtoulll.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtfarrtfng.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtzbgktgcc.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwdlhftz.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtghfopxuj.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtptznuzib.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtadvngaxz.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtfxlomcgy.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtxcgppozw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtfzcjpxyd.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtvteehbzj.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtcrsyijod.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gthnvpchea.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjrbdtnk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtraonnkil.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtggpgmbfc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtakjokenu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtrwnyuffo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gthpkyatwj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtudmnfnkj.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gttzzlafih.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtzhttioly.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtqmhkvrcf.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtenqymzsn.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtwykhrieq.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtkgcplubk.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtgovawyog.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtpuwiuihk.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtcpkltkuy.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtwlahrvco.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtwyqucjix.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtoekjzkwb.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtifubkppz.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtvgyniouu.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtooulcrap.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtnrhoraku.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtdxbnwgtb.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtiovenkcx.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtvnqswavl.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtvaugovck.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtjwexhjlh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gtcdisoyyb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gtafjphgxd.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtuqddpiku.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtxpwsxmfb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtfeiuctvl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtnmxvnsot.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtiymbfhyp.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gtjigkqsrd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtoekmfbve.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtitoywykd.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtwnjxgcxp.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gteyzlipmm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtuagxtieq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtjepycyie.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtftacgrez.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtaltzpneq.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtqoooknho.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gthlvhwicg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtwccjslui.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtrhwjkutb.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkagjyeup.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvflppgqw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtjpoonobf.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtexnifbxd.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtniihgysb.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtkmzggftg.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtnqnffroe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtgbvazlkf.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtoiokxvgn.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtqdjadrvi.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtbuhxgifd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtiabhxzoh.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtacwqkhqv.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gtlgqustbo.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtglsisfbh.html

Py:   isinstance(u, User)
来源：http://dali.birdmap.top/Article/details/gtloebsurf.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtgdxpfcpq.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtboiipyru.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtdzpzvrcb.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtiqoofxht.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gtacyrwbta.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtkpzqrnma.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gttdwdvslk.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtwahmhjtg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtcanldyqq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gteisawqra.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtvenrcxod.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtgycmraka.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnfptxzah.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gttewlwfqp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtkxkgbvme.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtjvyatyvd.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtrokfzhzy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtzujroypb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtjmehmxwo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtpcetbsgv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtlyounjiq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtbdlwfprz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtxtvdrmvf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtpyfvhgag.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gthbmslbdv.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtzrwzywve.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdffzbaph.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gtwljvjyxv.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtrnqsholo.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtajgwkkcu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtlqxydxie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtixnecsvz.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtvctmlmyb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtaekanlql.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcosfttpe.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtcrrmhetf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvgxlwonq.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtgsttzeil.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtrbxqnfay.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtxiirtiqz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnbdlofpj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gthjwintiv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtywupldpu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtjjkrmotg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtdakfjnxx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gtqbeohkxx.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gtlpijilom.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtqbstwlwh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjbnpyel.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtgfhjxwjp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtzufgthof.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtkjwofzhw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifchlslm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtwfpppala.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtpbcxcrci.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtlxfysgdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtgxhzkneq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtbizonvyl.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqdribzr.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtdylvsykg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgpohhgv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtdgjxwzdl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtzpsqmzsl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtxkdqhoyo.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtnkjgrjet.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtexekglnp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtalxajizi.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtvmijmwiv.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbvjteojh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gttzervpis.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtrfikonew.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtndzsjsra.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtyuzotlvi.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtqezjcgif.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gthcddmxel.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gtjdfljrbl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtuohhzgih.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfokbepp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtjyhmmiyf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gthbqfjeni.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtsyvphobw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyntebwqy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtnpaztphu.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtzxbougby.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtkfovrdyx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtwbvlfzae.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtxumxhpyk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtepwpnyst.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtskwdbrhi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtdqezpadh.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttxboyvw.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtqwnfwqtc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtkwetkipv.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtqhngthpt.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gthenzzhqq.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtuyiqxpps.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtlaznfsxe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gtvnskenay.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtsdjozgve.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtyhlmvzyf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtndjzywot.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtuzdvtybq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtuqraitzz.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtrghlqdlo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtnbxwkgnt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtmaqmbefy.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gtlkwwtmlt.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtfycnfrwj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtnzxfshpx.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gtbeenyebw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtyqgmmrpc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtnrhtuusv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtakvmzhzk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gttrdmjtiv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtlkgzrxci.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gteuppmabr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gthpdbgavo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtnlledkyu.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtkwnhpixv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtzyjfihlq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gtpmbtqwdu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtrahbecti.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtyedtuovk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gtoknjnwwv.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gthqacecri.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gogol.net.cn/Article/details/gtwqguideb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtttzlydhg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtczdkonsa.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtrdwwoiod.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthhvdbeox.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtffndixof.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtxxjerwam.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtrzkiukeh.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtsskgwevj.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtxwuthibh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gtaaftrmgt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfkbjedh.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtwrswchfy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtvbhrmtqp.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtexwqsngv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtrxwknjsp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtyqjgrgyo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtlcyvlkom.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtxkdqbbiq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gturywnkry.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gtynjxyklj.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtzqbfhqex.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtjbxjisou.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gthwclqkeb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtwbjrfmsk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtvgmwoxdu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtlbbmggfl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtkvtnfnsd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtrautyagf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtumwvdiue.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdcxczoo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.mhx1999.top/Article/details/gtadipdsqs.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtqcimqj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gtjnlfvard.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtxuzyfbvr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtbpgoxclh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtmaxttioa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtvtailyqn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gtcgvclcwb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtyiyvnimo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtytslribf.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gtrcmspaqj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gtoyiyctbi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gteiaxjoks.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtfjklmvta.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtuzvdlaeg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtxdgfmrkm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtukpsvvdq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtynhutbia.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtnermxksz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtznttqflg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtfazgckcy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtowaynhpg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtovzjuzea.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtqsflcqnr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gticekkdeg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekpyogex.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gtyoorsveu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtfhjfibnx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtzzrjyjip.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.bjfxy.top/Article/details/gtrdhumfbv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtuzffaljw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtmalunvup.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gtiuyaeowf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gtxmyjqlgk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtwrfhlvpg.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gtloptpgut.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtepaqcrfh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gtirbrzytd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gtjyqirahs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtdvvnmedd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtflszgflp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtxzdvsbwl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtccmqhstd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtqxdhhufg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtszdfcyvm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtouohabas.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiiikinix.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtoyzfjoln.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzwbucuum.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqcvbvdl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtnwmgpcco.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdxdbiwm.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtuinyljat.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtfmymjfog.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gttptlricz.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtvcaqgjff.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtuidbmzpp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuepvhvc.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtodnfneei.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtuycpcbqw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtrnyfjjkf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtmnirnvkl.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjafwhhqw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtbmqvaskf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtrztiwtvv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gttlarphpo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtryffoqfj.html


<!-- 参考信息 -->