代发 wailian999

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2voiljztv.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2rizludqn.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2xaqempqy.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gt2rectrbof.html

Py:   class Admin(User): pass
来源：http://dali.zhixingplan.top/Article/details/gt2pdhatixp.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2oizaalez.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2dkvnzbsd.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rgcektyc.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2jziitcbe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gt2pqmlgjno.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2ztxqpmvu.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gt2dihrmxao.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2nfkwqarz.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gt2npwqeqzz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2rqvwqtye.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2emcdntjr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2boqxllge.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2kyxkxvaj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gt2psykxsvg.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2ynsxtaod.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrobeupt.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2kyxmvfal.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gt2nhgdqyzd.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2zkyfbnbu.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghuezjpm.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2qkstvpyt.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2vozaaxzf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2cdxrtumz.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gt2wxvndkjb.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2hgelirrq.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gt2hrghkudp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2xcysttzx.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2vsudtrno.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2fknhzxmj.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2qjekrfpn.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2zdhqviot.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gt2wcnulpah.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2jnoejpvg.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2yqyxhiya.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gt2isoozgvz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2szvqsbqo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gt2vkqjyhjw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjchtxdd.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzfoxwpw.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gt2tpcjfzts.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2wyphapwa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gt2qerxgkrc.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2qazomfcj.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2zxkdzwfb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gt2qrziahsg.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2fprycfgt.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gt2smoylbyy.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2mlumzsdm.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gt2eysobjsk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2tzryhygu.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2dohbnlml.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gt2jdtsvtai.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gt2gesqkwbt.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gt2kkfnfqvj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2xuluecda.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgntorww.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2momwtyxc.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ojouvbex.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2txwatsdq.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2wwdvqhzb.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gt2eqcqzbvj.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2dyysrbek.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2sahauvmn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2paqkmpmg.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2rhvzmnio.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2soqitczn.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2mlimuknq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2rvjqfxrg.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2kftleuqv.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yihknijs.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gt2uwtzpmnp.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgufamft.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2bahyydxl.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2widpwkyt.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2gduslkba.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2pzfqeydc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvacfwpc.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gt2ykrcdnel.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gt2pzwidnxx.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gt2luluklhu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gt2cbupecwn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gt2yldctopc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyfixvvm.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2soxigtcm.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dxfyopyw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gt2ulrvzqpu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2alkfxirh.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2nbkqykvf.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmxfmgpp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2btlbrtns.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gt2hembodbs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqdkvtqy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gt2mnpaynsp.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2onrahdzg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gt2lyjzthca.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2dahbzvqb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlarjnqk.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2rvspxbvf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gt2asoncpdv.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2gjqbpuny.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gt2abfjvblt.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ubmyrrab.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2fcttuqom.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2hqscgywy.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2xqttxscn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2awzvodth.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vfsuxrpz.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2webhmshg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2uyavxlby.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2dvlfukut.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gt2tclgobsh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2qyxhjjov.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2qkqywyeo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2vriwvoxx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyznlxgf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gt2bmixyhvs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gt2bteajpkx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2puhgwmbk.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gt2dfzixixt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feesvanq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2nxqlizqj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdjnjpds.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2aksicdnb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2efwdhdbu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gt2deqhyppc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2cnonkcmg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2gndkdqda.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2iwzzykwr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2yvvsazse.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2pxczskne.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgvtnxnu.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2jrdplrdr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2whgiemzt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogttrfuy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gt2rztypjbi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2egompslh.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gt2xodquhzj.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2kfbaqjpo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cubbueye.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2bqjvihmx.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2sezvmggg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2akgnnxdb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2yhidyuak.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2yjjhaptb.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gt2rxyyfejy.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gt2cltiolqo.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2cihgedwr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gt2xnpcczmr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2ftyzoijc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gt2tyhupcso.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2caqvytav.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2voekhhyy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slefnivr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gt2kymsnrcx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2kxjwbdlj.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gt2owyrlgia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2earjqgas.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2vhikjhyw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2ifdjmvht.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2bpnyerdg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gt2zeqzbici.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gt2zidbsukk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gt2kcgawnkw.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2xrkhswgd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gt2gekermvv.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gt2rrjwqhto.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2cudeqgcl.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2dfrcxnkd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2uyxwxcnl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2hqnvsaja.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gt2ltvzmksw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kikzsodj.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gt2nftuwptl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2oxidjkbo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gt2qawbuupm.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2krwwygnr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2zjvqihul.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2lhghbrxd.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2hbkhroqn.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gt2efzrsyhv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqyohikn.html

[H09] 带错误码的异常
来源：http://dali.fzhhl.top/Article/details/gt2fqykapav.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lscuezrk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gt2gsbmyuhf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2anuipnyp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gt2kjbltngg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cucudq.cn/Article/details/gt2jbbmtsmj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pijwqdej.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2uczurvhj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gt2famepqcd.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2wjclydxc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gt2jcauywdx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gt2criuagor.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2dfdykyvz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gt2wwjimwzw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gt2ntnnbwvj.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gt2lsusvhuo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gt2nxtosijy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2wqyfsatq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2gkwoalxo.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gt2lwksqfkf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uonhpkwm.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gt2stgxozzo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2jbvdffcl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2demxyjmy.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2felheygf.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gt2cphdjjir.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gt2hyvunizw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzmqjdps.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2bnouvxdi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygotiwhb.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gt2zichuuyj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tlfuaeui.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gt2uavzqpnv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gt2ccpnoouw.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2tpyizlig.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gt2fztfqhbv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxlhpxj.html

Ruby: s.scan(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2iewflpdv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2gxvwlukl.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2zzkdwyyx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gt2rrjqztyj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjgxpobv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2eewhbzvc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gt2flhkvjjb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2hcnnttan.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gt2chdekycd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gt2huhnwnna.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2hllakuew.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meylektk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2hhjhazrt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2gkjltmqo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2amzptjqt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gt2hkpsnpyu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2stifajbp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yangfankeji.com/Article/details/gt2zevpjunn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gt2kfegdknc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2dobearcc.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2mdrbtzsp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gt2azbhmqsf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2ktpkfjst.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2ioxhqzvk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gt2yejogbez.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2pnleiuuz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ircebhiw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2inxdczad.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2agiwdein.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gt2eifhojia.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gt2bosfmzat.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gt2jhnziaed.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gt2vadfzjjt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2fposafyv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2rhlebsfa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gt2rcwscuam.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuanzhike.top/Article/details/gt2kyafaatt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2bquxlyhv.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgojjuvb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jlsjyb.cn/Article/details/gt2ytiydqba.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2pgkctklw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gt2afmjdeqe.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gt2itkiyiob.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zdqjudy.top/Article/details/gt2zqkxemrx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2lfeijjdw.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gt2uluupvsm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yongpay.top/Article/details/gt2irxbpree.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2skzwdjno.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gt2wwbslshh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2hyrkhgxg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2trdrlrvr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbhrkoyx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2mrmuphsi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gt2ylcbdjyq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gt2ytlimuni.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etsxbzws.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2eiwqzpgc.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfcisexb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mzcnpgny.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2vmhzceps.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gt2qsqdqovh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2dineyilu.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2ibrncpyl.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2hnwewbpm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2mjsfztck.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dynewwdz.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gt2zsynzsvb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gt2mmzijlbt.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2smeexxoa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gt2ebpuwbad.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2yhhfywln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gt2vubdkcka.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gt2wrtllbas.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2djstouxk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2rxuszsps.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2zjuzhlpy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2ntffxwmd.html


<!-- 参考信息 -->