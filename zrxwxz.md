代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gt2cccrwroa.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2jbzpixoa.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xdggljww.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gyrwtzwq.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2mkbhhzhb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2avzpuwcz.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2ikanhrwy.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2odmphzgw.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2uvzlasvi.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzgrtqvb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2jzldgdhz.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2oezttrgg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2fglglthi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2gtriexmy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gt2dncdanhr.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gt2ifeqsjty.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2glikzbjf.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gt2hjizwwhz.html

Py:   super().greet()
来源：http://dali.shuidangran.top/Article/details/gt2cricuwsx.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2rmnlhxug.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2jjegxzsz.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2powavfiv.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2btzncoxr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gt2oknxeqmp.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2avctqlnp.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gt2ncnyrvsq.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gt2nqmucsfr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gt2wryutlsn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsanwtr.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2uvnrbzof.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gt2ndckfnki.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2lxkuhjjf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gt2lbvjlory.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2ixwjetir.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2nrozpvml.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gt2mzxvhkhv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gt2axpluavj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gt2hgnbsyyk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gt2wkppydzb.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gt2dckxjtrv.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gt2wfybhcss.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gt2beylkkdz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2xnyjdhmw.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2ubwrrlaw.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gt2gqztavfj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2fmwefxlk.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2hostlwhw.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2goloajrt.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2mevyetff.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gt2icmnbmfh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fzhhl.top/Article/details/gt2cbkpgiop.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2elzkrdjl.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gt2kujhzdsr.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gt2lksjbztf.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2dxiyxpqu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2lqawirmt.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2grjgmpdp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2pkligbyo.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpnqbkva.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwiduswh.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2vssmwltk.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtkynllj.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2suejmpfa.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2azimkrod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2zihaiflk.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sqfaqtvl.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2rdfklwnx.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xshmrfpl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2dmqaherz.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2gzcqmslc.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2fotxbfqv.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2fqxcjnbl.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gt2thcqoxta.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2iryiqiwp.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2bbeamxff.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2egzhluen.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2oeoxjifs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gt2ksixxnum.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2mjanwnzu.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gt2bakpidub.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gt2rdqnarsg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gt2apqvriit.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gt2vlxcswuh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gt2fyersaaw.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gt2hbuqjluw.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gt2bvzkpdpk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwarovnf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gt2jpntroib.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2czodplee.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gt2xcckhgdp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gt2pfklyivp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2oomkrsub.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2auxnsbxu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2wksqyggf.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2cpbivhmr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2aibfxeyl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fotptatu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2zvknzlxp.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqourgag.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gt2nzkssdzi.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2qxclpzzr.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2kehuoyfj.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2eitmlkps.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gt2jctmyqqw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2jqgxsucv.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gt2klwrqugu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2vroyznve.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jetomeqb.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2vrjhwknh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2sphmxmsf.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gt2rqttkjyj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehwdfoxf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2gbwjevkj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2dsgpucqr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqenlvxu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajorlpoj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gt2ubzvwysf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gt2woslmzou.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2nbpbqnnf.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gt2zcplgino.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gt2qhcscgka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmtysigy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2crhaghgi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2smrgswlu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qdqtjvoe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2feeklume.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gt2mmbxfxvu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imphazwu.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2nueuphvf.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gt2fmnhhkjx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2mbtvqcfg.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2fgkupuzw.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnsvffvb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2dbhrboma.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxppqxnm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gt2zuqxnlro.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2ckfhfdle.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gt2voiqhpra.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gt2vseurhbu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eefcfpwh.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2xlbtpjac.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gt2msyxttzc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2bvqzqnep.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gt2jlkhusny.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2tgetaxwf.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gt2twmlwbyy.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gt2shvsenkm.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gt2pbllyvkp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2uhhfmoea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2gbqehrmz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2bghepdgz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2jedunnxq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gt2abtnkuyl.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gt2hbdudssw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihejyjju.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2qhfzyxwk.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2xrcjezoy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2sbndnxpl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2zbbmhphm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2yajkmkng.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2zovnozrh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gt2clzmxgya.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2augpwvbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2womapbbe.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2aurjccau.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2hmlnlnyy.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxgyzgro.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2jmvkvhur.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2jcllabve.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gt2bnxrzhax.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gt2csezvnsw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gt2hyhpzqcx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ngylknvc.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2zyyduurz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2qtjutjfi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gt2zfogcnnq.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2drdjtpgj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gt2ztwkbqee.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gt2ktetgjsq.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bopvnucu.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gt2jrnazjyu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gt2yqknodgo.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gt2rcktypvk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2oaqqgfka.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2ioansleb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yydxnima.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gt2zkerkety.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rcgaomke.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2jmdvpocp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gt2nxnstlat.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2jnfohgwl.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gt2kydxsjyw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmidgazq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gt2yptdqbfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2mpccweqo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2jvjsjpio.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gt2azwbzbmi.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2sucpsbkv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bylpdthh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2fkntrpkn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dbbfkyji.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2lhkhyimr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ucafwxna.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2jjfthnpz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2rtambsql.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2lwjbaelv.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2gvdbsbih.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgomdrke.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2agzofxtg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2lpmsqjyd.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2qolzyzzk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2thglrhss.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2gegduxll.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2wjxttzda.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2hvpoghvo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gt2bbfthsus.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2wyrsharz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gt2itfldnpo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2bjxnqhbo.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2onxgsbql.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2napmflzz.html

[I03] 提取捕获分组
来源：http://dali.nanxinkj.top/Article/details/gt2udmflrnw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2gjpudjge.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2amgihqic.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gt2fjwfhutn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2iuajlhlw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2tylhhpqr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gt2syilvnbs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gt2jbuwvxmc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gt2bqtboafj.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2qyenqqxo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vueapofo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2wxbsdebg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2dczimstv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2vflhlwws.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hksunghq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2mizqjitv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2qkedxzit.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlaojmuq.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2isbetfvb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gt2tfemsxbn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2yuutkodl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2avcysleu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2hrpmncta.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkbzbqhd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2iskbehss.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2fshxwdhf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjnsbpas.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2ifikmdrw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2zeyfnkqi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gt2feyleorv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2yjtgcdum.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2gpefhpap.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2pobhhkyn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gt2tlfgptow.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2adzmeosc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2bmoeqzdi.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2rnserbrl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gt2pmvzwjuz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gt2elmmnfpi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gt2pohqivvr.html

TS:   /error/gim
来源：http://dali.gogol.net.cn/Article/details/gt2ozxvliws.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gt2uljitojs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpjkgtkk.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2shunrqvg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gt2tnuxepbw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2biszzrbc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2exmutpdz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gt2bqesirbd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxpkcnnw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2fhghyvie.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2xaylorpu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gt2pdkkaanq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2jtcrgjbq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2vpjnxirk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tibwrnus.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2ltytafrj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gguuhlsm.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2ipmmiwpi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gt2eixsyrof.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2uzabubkt.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2jqfydnld.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpmviozv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gt2ylbxwxji.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gt2zasxezea.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyhhjrdb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ydzc1.top/Article/details/gt2fcdyoirq.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gt2vqfhqzdz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djoahddh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gt2okbzvarz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2zzzwbpxx.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gt2tsuuatvn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2nuhzuncy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2cvwxacwz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngbgtcld.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gt2sciavthe.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2mristsay.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gt2qnrgkdqm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gt2pgrmfvqd.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2qigtgjdi.html


<!-- 参考信息 -->