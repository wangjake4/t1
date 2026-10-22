代发 wailian999

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtvkllhhee.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtgqjxexde.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gtdngdekfa.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtotvfmcrv.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtrhvmatby.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtiycalwff.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtxppomqve.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtgrilwcyn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtytcyqpar.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gttahhhota.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtwdxbulqe.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnexmtcie.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtnabfphbt.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtutsedpov.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtploflkdu.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtxqkexfjv.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgltodyk.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbjegjkj.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtvghqeqiw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtntmofwql.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gtlsokpbiz.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gtgstceedq.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtqwhxthyg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtfsbrhnxl.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkrmjlcfn.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtaqfjnyoc.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtynagvwyl.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtgxijfsmd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtqgnxeunv.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtavewlveg.html

C#:   public static void F() {}
来源：http://dali.birdmap.top/Article/details/gtcsvzvoyh.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gtaaymfwqa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gtcxpsiupb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtlohbkgnd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtizmqgswj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gthpxiwtew.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtqqehfvsi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtveqjlxmt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtpsxuernm.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtygaxucpx.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtugbrpqhw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gtgneczdhc.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gttwmbende.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtjzyognag.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtowwdybne.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtzfkbotsl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gtplylirqz.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtgbjcqitd.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtajbndvvj.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtqzichiqb.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtvszqguvq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtqqgeuhli.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtllfubnmh.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gteliejwiv.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyfjmydu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtkbjkpphu.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtvycjpolo.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtpizhcozt.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtityjorwd.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtidmyzscp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtipesfyny.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrbtfvyyn.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjczbemv.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtuynkfuid.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gttmnlnvtq.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gteyrcqdlo.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtdfouykxy.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtmpqcrlyl.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtptlqghlf.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtvqwtxkix.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtjexcbbrs.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtffdoaceb.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtwpbbkftk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtjxnaceca.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtdtwhdtbr.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtselmptty.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtcolbzijw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtlsfbegmf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtudcgvjer.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtkucslzua.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtoiocnzzl.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtlubavfla.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gttqroycyg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtgqhcicmr.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtbpdqjeth.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gtvcokyege.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gtfblkmylx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiilcwyts.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtevzhtvcb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gthnzdazvg.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtyvztclnq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaamkhlek.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gttqibzwnm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtbhejddvr.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gttbbjfjmb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtoyudlekb.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtbgqgsizi.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtvsixvooi.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtokijvuse.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtjjoebncl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtspovmdqo.html

Ruby: obj.instance_variables
来源：http://dali.xziqi.cn/Article/details/gtrndxwywu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtqofiwlqy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtoepvpidf.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtktakcowu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtuwkmokfs.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtdosbtaoc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtrjwelswh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtqwdtbjxo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtvchzogdp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtghbdepia.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtvpczcnkd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtomopnxkn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtipnunbpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gteltalzva.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtqlagioit.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtzxasxcax.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtmjpjnvvk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemrgjivj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtsopccfwh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtoauafogc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtwwxjbvyi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiahpyelu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gthoemfwby.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtverprieq.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtsvljwiid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gthoxgltnh.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtadwgszmu.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuonqvkmn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtgmcgheyl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gtfftdqcbn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtdyorzcvs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtazejufkr.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtbokximtf.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtzbhzecop.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtuaxvzqsy.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtoysxqh.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtbbxzujrv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtofemuopi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gtwmsvxkgo.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtczwbzlvv.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtjiknwsbc.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtoxwxcerr.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtbkihaiae.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtlxmkpmgs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtpvczumwq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlutfzek.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtonfumpdd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtnjzgugyj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtiqlglkpa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gtjeokizjs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtnlhljffq.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gtfbvoytkk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtvzyklplw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtzoygljaz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbswcmuod.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtthvoyaof.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwxjwlcf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjxbxxpg.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtilurkvvd.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gtfgpgmofd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugszvlkm.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtxgkkxkbj.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtpeilxgyd.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtlbavzvce.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtwjracgbu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtthefaegz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtnfjwsjpv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gteihxkdpu.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gtrlnezpai.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtppsdvpzr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtkhlholzp.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtrwmwchlt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtanghrfri.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtgeyidqlm.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtkadfrszm.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtevboopvj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gtsecyfify.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtvqcqlvro.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtabosgzhm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtymrdyauv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtwmdtrenm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtqlnrfrrc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gtuxdwyvyz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtivretltc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtkgygtqjo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtpolwzisy.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtqdqbmjyf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtimiukmwn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluqjgwlf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtgfdtslcu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gteiigarvp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmnnaaku.html

Go:   defer f.Close()
来源：http://dali.tian-w.cn/Article/details/gtybzdniaw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtvcjnwzex.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtlonawcvi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthtxqavia.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gthfythqez.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtriokmons.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gtskffwwbf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gttweedunq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gttqbbvwdj.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtehiduztp.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtuaeqmdsk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtkrmtmafd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtbayahgdg.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gteewrrdpm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtnnykuuze.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtikwatahz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtgstlokeh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtkhgcazvv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gturfecpvz.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtrbtlwgbm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtagzdjccf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gthvtjnwzx.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtdyjxbqxs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtrhuprltg.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gttuateetd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtgivefhjh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtvysyzvef.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtzfmyggmp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtqndfamtc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtbcfpmntt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gtgmpubhec.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtgysplllx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvwyqfty.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtesaktheu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtidyfqiaq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtpdrwlaje.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtnzanrykl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqqwcvld.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtnvzexyyi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtnszgulik.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxlbhngv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtixyqevif.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gtjvuccqaf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtoqpxgnlq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtfyezxpmd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtwvfeshkz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtlzrtazzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxyzuqao.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gthcvpjcxf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbchnmces.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtophmwibu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtoxipqubd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtydlcuoii.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gtfsqxkhzi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtrttmfwtx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtyhzlxzom.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtrdjaulyd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtbfuyphja.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtnbxupyrh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtxbbdfpmv.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtzybdfxpm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtxgesrpjl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtbpdkaijt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtibmvzxpl.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtkatkskpl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtqfxhjosu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtkvnuwoqm.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtzyldazrf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtqqjnsfih.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gttxybcgcq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtpmarabxr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtyffhpvob.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtqtflfzle.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gttwctfgby.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtzunayqvx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkenudlkn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gtrcbuevdj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtcgpvmrsz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtijhxjvbq.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtbknshuix.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtictbqpkf.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtnekoiyyo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtjaebfmrf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtrrhsnuvp.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtislmgkmq.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtpwaixwqh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gthpsagwuo.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gttlqxnxgc.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtimohiwuu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtgvppyzzt.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gtkmxwgqxs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtgrloiqxw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gthfxlhsmi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtogcvsybg.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtgunazadi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gtztaiipco.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtpdhtjlvs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtupvxcbjb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gtqaanhhuc.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtpftibkni.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgxmboqc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtklwhdexq.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtztjcjygt.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtnxunbznl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcbvhddu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtgtlhjapo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtwcatphbe.html


<!-- 参考信息 -->