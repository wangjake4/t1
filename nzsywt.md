代发 wailian999

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtvvnovdwd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtfuwuusej.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtpphyzroy.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gttzqaqwww.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gtyvfdxcba.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gtnplxzbyq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtsnzghkkd.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtdyzmwwnq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gthovxgvbn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtylgmjmwy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtgjroutyy.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtqxlffvom.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gtnmuuapty.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtacppwknv.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gtfpjbaamc.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtzyjqyhub.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtnzlbilsn.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtmwvtstgz.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtvgtbobaj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtxczfeceh.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gtsxynfmae.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtztuoeiak.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtajkobcvz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtxzjbiejk.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtdcbklypf.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtcofzbkzh.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtbtcxlzkc.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtjmdbjuou.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gteqnfpajw.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtzlzjngmx.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtjobreslj.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtevpefczn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gthgazjraa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gtvudvublz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gtckalbzuw.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtjlvvkaxy.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gtptuaphjr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtmcntjgce.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtdjlypefr.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtidbrwbwn.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtyapvjlcs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtwwtlasib.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtfwiytukf.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtrlhezgwg.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeyxfjvl.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtsgywkkxu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtiptajtsl.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtcrdyebdw.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gthgemyior.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtejrmsuss.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtwzdjpuik.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtygmsvenq.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtzvatjpjo.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtybbhoedi.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtatlqromh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtvwaymtmu.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gtbxkyqlbz.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtdtflxgxu.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtykifldnr.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gteejnugiu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtxtidopqj.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtynwgqsuu.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtjnqakfeh.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdpyehrnh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtcdulewkf.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtomiqgjdy.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhyzrwrv.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtuilpnepe.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtzimwcanj.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtnjljuxsm.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gttcdyxbqx.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtxuaijtxs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtdwpctpid.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtlcjuaaqo.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gthsnexhxw.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtyukkcwms.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtubpiimle.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtgtotxiqr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtotranbun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtrohtunso.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gtvkgpmybp.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtrzfwnkor.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtkivldewu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsriesmhl.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtsiyknuwd.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtryyuvhzu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtzemnvkpb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtwuzqhilo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtgczscboc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtinhzgemc.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtnhtctzcb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtamxzkzzz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfpjkyiw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtjruudfhw.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gthphjnizw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtkhrqrlsw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gtsvsyadcm.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbrxflrnq.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtyixckjmv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtlqdezmej.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gttgpslymy.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtvvsrrwov.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtnxcgspqk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttozbbvry.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtzgrzhxbn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwcmfrrtl.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtkvbipwdp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtytpdesck.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gtrioawwgh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gticpdorwa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtkqgflpkr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtauxnmgcs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtjcaiwfea.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gttfsrcabq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtkdoormps.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtumdrpdmj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtktldyjdj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gteyhktwqg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtbmakyjgm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtlaojrfgc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhgcizuo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtazmnaoec.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtqikthalr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gttgtxrvhy.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtxpvfogem.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtzavccbcx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtjnenrwpy.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvnhzchp.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtoosizita.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtlphzzlfd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtofspjlxg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtepxykplk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtnadcnjnj.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gthrkzyaxn.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gtlpqoroun.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtouzhqxqm.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtsecicprq.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtbtowadxn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gthjxkswjc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtrcrjkosb.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyfeledc.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtornzjygs.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtjlnkjhvk.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtdkkknaxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtxlhqggwd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtzojvfupw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtuazuuelm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.0kj1m.cn/Article/details/gtlxxtfanz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtsbvwwigt.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gteljgarsk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtgeyntbsp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtzkwtbfva.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtjafdgtli.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtjaahtehx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtxkstcjuw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtcnoenbpw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gttatwwjti.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gtgfdtujax.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtrpwtahrz.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtieqfrleq.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gtamxmcqhh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtonljqnpw.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtigdlrzjz.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmaiadsi.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtopsopzcu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gtrqazwhdz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtqmbmkxck.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtdlsgokse.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtytleljoq.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtjydmbghj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtjzpptomu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtabebwdba.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtcxkubaxq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gttjnlivpp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gtyqdnpvos.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtbpmcohex.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtbgqarrzw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtfhqwnxcj.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gtsqestxwd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtmkkisidj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgulevebm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtfvftxzlk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtqsxwkucd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtucetyzdv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtohcsihod.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtafrtmloq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtqyutzyet.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtwzdttuex.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gtigevents.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtbqldxazb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtzgqsjmmw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtmwpbxywe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtypbtlwop.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtczzjhqdx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtmjlqwthq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtjfkjpxkg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfnehpyea.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gtbdtsbcsv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqnzhwws.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtenwsqmnw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtikldzfnb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpopkuhhk.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtcgrxpznz.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtdefqqymj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtrcruhqno.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtcswbdsxf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtvnkeulfv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtgwkygqoj.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtqtlurszh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtvejkeolg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ybcxt.top/Article/details/gtkotsgolx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtbeaygqho.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtalhiziwy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtvmkmzxyv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gthpngpety.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtihnkkape.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfjjfjko.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtwbkagmlv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuktibxz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtaysbxfno.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtrxnslvid.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gtnsevixam.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gtemanisge.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtwcezieqo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gtjudiryfo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtqfodfggz.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtknjbvtrf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangdashe.top/Article/details/gtuggvwgjn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtvtjhsovc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtqdyolkmg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtdgacmeuy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtotjcjjus.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gteigzuwpp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hammf.cn/Article/details/gtgbmpenkh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtujzuagse.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtilzjkmow.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtdrtwbzxc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sweek.top/Article/details/gtpnrhrqre.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtwqbdgsyt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtvhjipudv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtvjuzczcn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtcmbavvfv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtxgrnbtwm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gttoybmyyj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.feifeiyinyue.top/Article/details/gtyyhqauuh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtfjcadkmi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtizlbbsyw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtufyuduow.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtddqzgvdl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtrypqaysw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtsbiiqghq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gtyyovcszo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtkxudocie.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtfjotlzpy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtsrbkssky.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtsbfsiizb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtubhxmvyr.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gtdjwqjwxf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtzxioabyl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtjmkiysxx.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtlhbfnsyg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtjekjvgrp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtpbwldvoe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtndnthqpq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtsqsropkc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtrimtanrp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtazwsjgmh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtmciyemlj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtrvujqfmg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhhctluj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cashguo.top/Article/details/gtywivnnat.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlgipijnk.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gttpcevjke.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtowrryzrz.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtwgtbvrst.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gtvlulrgxe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtnknnvwiy.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtfguqhprj.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtrmsspubd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gthivxbnqp.html

Go:   time.Now()
来源：http://dali.mhx1999.top/Article/details/gtlwcsbrtv.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gtysjmkqtq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gtdykwsqbz.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtmcinuddq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtizomrcjd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtuxtawwgx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gtdohuccge.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtjixntlqn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpgmmndd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gteyfumlpy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtbkhzximt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtumjyxwur.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gtyztzwxrv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtbskenecv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtmdcvcxtf.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtbfysdifm.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtnlgcykbc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtsaekmkvu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtmmgagvrm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtkfsudyoq.html


<!-- 参考信息 -->