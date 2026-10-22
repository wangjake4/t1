代发 wailian999

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gt2anceznen.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2nqevbevt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2whazlskr.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dhtfhguj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2frdcqayk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2mfeqexut.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gt2msoeyaup.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzurajo.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gt2uixgljty.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gt2wafngzii.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2huvjhaui.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2htrgzheb.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2netvwpvs.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2kyhnyeit.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2dtrqhpso.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2ehmzgezh.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2dqdjiynl.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gt2byrvkurw.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gt2tdnmvope.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gt2pjgntztw.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gt2jfvuynox.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2eqynewtf.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzpxysfa.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2omeomgpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2yqiojwrl.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gt2vlxzvhle.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2iotgjrwq.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2amscmylv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gt2gzmngvas.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2itthrlwx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gt2kchtzdzo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fcuojjhs.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2zakdiejr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2txthhddw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gt2gigrdcew.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2huvbsutr.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqepnjbq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gt2seimamtx.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2qdjakcri.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2ufotgzgw.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2fozfrfrb.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2vtqsvjne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2hqxertkx.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjtwjvwv.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2anlhcuwr.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2sosafswk.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gt2lrbpozbu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2cysihhwd.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2lshvhzmn.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smsjnfzv.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2gujauazu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2yjuyynsv.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2qnvszvzy.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gt2adonowzq.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayorvrwd.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2abuavyyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2mqmcyhhr.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2bekvgwsa.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2uvyscnxv.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2mzffxqvl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2qacbbnlb.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2jiceuwda.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2ecdebhzh.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2bkxmcqip.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gt2cwrypcpf.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2xcvqudgf.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2ahlhqgfv.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2iucxduzl.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2qvxwqjfo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gt2blpgnubs.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gt2nzzydbof.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gt2daezonln.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrizguzo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2vwrlthbn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2stfhudgi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gt2lyhdztil.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2dvghheto.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gt2mkxkqere.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gt2nwliwxxy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2omeyzquj.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gt2eufvkcpi.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2kcpzrnps.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gt2yqiqaguq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2fvrxdceq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gt2inkhxjxy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2qemfzpne.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gt2zoehhhai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gt2mthgeawi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gt2dfxsakwk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2yepfbrul.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2ekjdwwzh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gt2bjmvehtm.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2qzneztqn.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gt2pjvpyvcn.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2zuairsla.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gt2occgjiqi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gt2pzaolxmw.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adzvvxjh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2xiyvcefz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bajiimcc.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gt2exeemket.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxtvfdzf.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2vbprazlx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2kpdytrjo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gt2fopkynek.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzzfxvke.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2wovkojpn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2htqhrrkx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gt2jvfmozbe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gt2cjzcszwc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gt2nhtkuxkv.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gt2dnegovsb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhxitahv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2qbvqctfc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2lzapcgtk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2rkdatmgn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hznmtrza.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gt2bsswifud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gt2rhmtmnsh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2skeqnrtl.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2lfunpghd.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2tnbfpicy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2nlxdscrk.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2wntkcsxx.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2bvyjigoa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2kowvfuhy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gt2tqtavnsv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gt2mjgqmrds.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2qjomgyps.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gt2uxbkxbeo.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2ieoqddln.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2yfsbysmz.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2erbouyvh.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2kftyuzje.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2manseurj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2miiwgsqu.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulwypqju.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gt2pasftxaz.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2ucaxzekv.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gt2oflmocik.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gt2wvtfudds.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2snapnmud.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdarfuv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2oehkrsqz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gt2rygzsyme.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocnimkci.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gt2oeebjnfm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdoajbij.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2htalqxrh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2ledenuwc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2hvbsbmtj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2ehoqllnn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcifphxx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gt2xhlesnkb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gt2umshgnyo.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gt2wexnhrwu.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gt2qkaislpj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gt2xydidpqq.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfhmeagc.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2jswvrbus.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2joosspqz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gt2pdyrbjdf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gt2dduymsjd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gt2xezsddqi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2gdpizsko.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gt2mddieafr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2gtsynvlz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2nhonmicn.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2lubktttz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2qwirkbfn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2iziddaxf.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gt2adryixku.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gt2skgjrjkw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.meibo888.top/Article/details/gt2qftxqslo.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2ttvfponn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gt2xkyhvusr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2lqfqfeja.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gt2sjvondux.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctftsvdd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gt2ebgljhnj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2ueminpzg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gt2gslrmbmw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2gvhjgfvh.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gt2dmknlzlk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2zmbmlydo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fzhhl.top/Article/details/gt2ywlkxmsd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2yswjxiel.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2marmeeoa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcbvoksk.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2scccuyop.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2qniwgdnr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2mhssufgk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bicrifdm.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gt2htnzinjl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2udykwsvp.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gt2qurayivk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2fmlrvbtn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2sbvpyhsk.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2dtffryql.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2qlkazkds.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gt2exvfwkie.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2umdvpwau.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2schypnxy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2aywrkezw.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gt2ptmtsajs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2fpycvxbr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gt2pbytmqpm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gt2txgdikyc.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2wwlshrzr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2igflcxye.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2ygqfenbt.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gt2juxggduk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gt2kezxrtdx.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2bsuiahcw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2acbfxkrj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2pqnvjwwx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlgibqmc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gt2xzetwvrg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2nwxdcewd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gt2iuislwqu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gt2pzwdwepb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gt2znycfbeo.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gt2ecacskmt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yocvqrcb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2zafqtrky.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2juskazow.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2ljhdygtw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2ljptgvka.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gt2qqqhnvdu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ntetobch.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2xbnbjsry.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gt2ibddpnbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gt2hmmrbrbl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2lpulgbeo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2wylinxlm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2niolwxkk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gt2qoowiqbx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aohosfgb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2oujatgtf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiiqsytv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2rwcdbygm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxhviiry.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gt2hujlnrjb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycffbysn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2jwvhusdn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2hgvxsnnd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2kgaetrkz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yonumen.top/Article/details/gt2jchcalbw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2bjddthgm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gt2kxfckfej.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gt2zdrttcnb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2ldykyfck.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2giysiuxs.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2lcntccle.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2zflkuror.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gt2fkpdvyuc.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2sqoynpuh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2reqaqyjp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gt2ebcqlrwv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gt2ywfierek.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2dimfaxww.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcghjanz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2ykgajwlv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2tplestqg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2nipkurck.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gt2zczwagzi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxazzqrp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2tudmupri.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gt2ttyponrd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2dryhwvxs.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2muexvuvf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctdqymve.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2vvyuetts.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2lybhzhld.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyprjcvq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcobzqiv.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gt2vkniqixw.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gt2bhorakqq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2uiqyaiyo.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2ntqafisa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2aimujhen.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gt2xjnvmetf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okkxoadg.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gt2ljgkijws.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gt2fixeebpm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2uurzogdt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttpiutpi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2pcvschrk.html

[J03] 字符串解析为日期
来源：http://dali.havefunace.top/Article/details/gt2mrfpchuc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2xnednuof.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gt2qyixjyzl.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2hzraenwa.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2tiwkaknm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmcrqiex.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2tlcaivur.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2pdgttdmb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2qmcjntnx.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jckedloq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gt2ijofwkjj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2ngoebelf.html


<!-- 参考信息 -->