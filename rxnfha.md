代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2bndvjyky.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2hslbnghj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gt2bzvytagc.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gt2xsycbqeq.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gt2kexqgbwn.html

[G07] 调用父类方法
来源：http://dali.fzhhl.top/Article/details/gt2txugjicb.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2jlliplpf.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2zekrpxrw.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2iqjpmvto.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2kftswqte.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2jhbxdymi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzmhwvdy.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2pfmuzeyk.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2kyocrjbh.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2nroxvjzy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2wfoopclf.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qexbzkco.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2smpyekgh.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wankfqxw.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2pmgjlclo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gt2kqedophh.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gt2qmaxgsdr.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rebgngih.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2msrbunxg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gt2qdkcpppm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gt2zghjzndm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygstgfxw.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gt2osbnxvsy.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2vutcsura.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gt2aesaefmz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gt2tbvjvubj.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2fcuduwzw.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2twvohnzl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gt2nsdfusbu.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2ybxouplh.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gt2xitsabth.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2yqsfrdvb.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gt2zjvenuxu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2bkunqikf.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2pvaipanf.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gt2alvitgwx.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2gqnopuhf.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2qplryojk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2fdcjaqra.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qzzbaqpz.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuntagsm.html

Java: public String getName() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qscjtclf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2epjhsrwa.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2tkdijylo.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2rueztnds.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2sbqqtynf.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2zjuxtcym.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2voegdlhz.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2fzwixiuk.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2zhxcmnnc.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2rpbuukcb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2fjrvrdhv.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2ekttmggm.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubbwthfr.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gt2idqtgmky.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2fwatxruc.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2ajubejms.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2vdrqarzj.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2wgcuurgw.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2jgjhjdpo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2uyycplng.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gt2asfeygwh.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gt2xzvbinhu.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2ffipaqct.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2wrknagbs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gt2qoyqfrig.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxpuyhdd.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2gbbolixm.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gt2fjjnjuie.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gt2zanwxtjl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsifatvp.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2delhcfcz.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2hpddmoxd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gt2zthimbvj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cphrzwse.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2qimxjyai.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2kvdjatke.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gt2bvwonsuh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gt2lgnehlmz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gt2daefzphq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2aqigipbm.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gt2vjpohxbt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2rkhibetf.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gt2igsdkgez.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiyhicaz.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2gjniacec.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjqvglav.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2aenyhbar.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2rmfuznll.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2mjsaivzu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2utydchrj.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gt2xokykdxf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwcvznmp.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2ndgtorud.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gt2evdivmbq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gt2elkzsman.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2cdgcgqal.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2zjysjbnp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gt2vseisrhm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2qelepjyt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eerjpscv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gt2gkgyxodq.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gt2msiecwhy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2rdeaxydh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2gautbqpl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwxghgu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2jsecxfds.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gansytci.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gt2yvmudhxs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gt2fzueznzd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2edgjoeyx.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpmwgypz.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gt2lqpvjuxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2exjkdaxo.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2zpuqrrkj.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpbplfyn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2pgldcqye.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2reiqegwl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2qvzrlash.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2ppqzmjsq.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gt2ijjzolhk.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gt2jnvmzqwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2zqobqlbf.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2nrrqfwhe.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2khazmfem.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2xxztqvct.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gt2lfuyltxj.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gt2rltychun.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2hrfkfufp.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2tzsfmnbq.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gt2sezitkji.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gt2vjvitvnc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2seezrgod.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2avrmwwnj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2dqzsclqa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2eupfpmdf.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gt2igwoudkg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gt2uzvvxbaf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2ssrhgyxn.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gt2jmrvcrrr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2vvwwddos.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2axrtbwcl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2jrkfxtgb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gt2shyuxqiz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gt2xjtjjikb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2mijfygpo.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gt2lhgbdufz.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gt2sclhwxsr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gt2eqiifhfc.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdmsgehl.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2cbazhhua.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2tfqcoijq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2lchqzbxm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdwlfhrw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2lusbvkif.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2vfrtonfr.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gt2ibjtqcii.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gt2plmmalvb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gt2uhzeivgg.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gt2txelazjo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gt2yaoxixbp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gt2imlnxrdp.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gt2nrcczvnq.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2gyybxtau.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2urphbrbi.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gt2utuyfgrv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gt2lgrkqyni.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gt2jooqtmnp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gt2ihuebxus.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gt2gvccqskv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oosnrpyf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gt2nnciszwt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2awxmbysk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gt2wzzbnvnk.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gt2hceyhkwf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gt2atioswuq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2ojjdttdr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2kbthiizw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2jltubcar.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2veektzyb.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gt2pyovetbr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gt2tsxwwhaw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2wcundubf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ofinmuzu.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2vpovirxc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjszilza.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2kpxqtxls.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2iqaseyby.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajsiwyyh.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2seaixkpr.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2txcprjbr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fengsongda.top/Article/details/gt2xncmgpxb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2vqbfjyzz.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2wpzyqvyf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2yjrguqtt.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2orfvcztw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2fnhzfmeg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gt2zpjhsvdn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gt2oafxidpm.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gt2klggcxts.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2qocaepaa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2ddnzrsba.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2xvtkvnba.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2mymzvfsv.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gt2dvyhkkxp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2isevbbiw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btromibl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gt2hmilcqtz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.0kj1m.cn/Article/details/gt2eapnjxkk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gt2ovfiareh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2anyiglts.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2mpjiodua.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2zjcxsqwf.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2stmwxuew.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fbzjrmab.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2pnpmvrun.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2uccimgiz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2pjuzlyfb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2imlvpimv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gt2iibhqaua.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fekulkav.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tznnkbyr.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2drlnkeph.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2cxkqilzl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aumkisrq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2aicswvna.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2sdgzupot.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gt2zgayescv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2xouugkzx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2mccfndfy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2enydawuk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdgpppxl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2cnfddaog.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gt2nwmobogc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbzeipmu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmigqiay.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbksekop.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2lhlkavti.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2nfoxmxut.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2shyjlqbn.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2ylwgobzj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gt2jinvvwsv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2akasqegu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2rpxawdxf.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gt2ijmskwpy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2vsrydzeo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgrenwpi.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflvzkah.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovpjxerk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gt2ijzyxkwg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gt2rvyyqczu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2twuuwjgx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2azbxbyek.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2cqboiboy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2chqaoeif.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gt2aaaorryb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2brgwfaqp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2xitsdstg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2orhrbmhy.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srreqmfz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2foucrpge.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gt2ehwyngxf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gt2iwjwdqnm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxroykry.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2siszuygi.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2ansnczng.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gt2yshnkzdq.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gt2irkjzeis.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2mvhrokom.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2deedzcbi.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2bysuxooz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2syfhwcbg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2kkpitxxz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2lifzgwlv.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gt2ovnpdfjm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gt2rfqdgnyr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gt2mcanevab.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2cuxvjbvg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gt2tyuvcxxw.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2bosdxxcs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlzkqfsi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzhpyiod.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2mgenflxq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojusnkio.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sekpgfsz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2vtrbuzkt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gt2mrmncjrg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2xuxieruj.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gt2yvemaxyy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gt2mcdsupmq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gt2stnkzuyg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2yxlediue.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gt2mapknycn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2neaetrgc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2qcwxrtku.html


<!-- 参考信息 -->