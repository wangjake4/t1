代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtudwjqmwd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtopzdwoiq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gttovoctfj.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gttvrehfgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gthlwkanou.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtdbghzxkk.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtxlyhnqmq.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtgxfccibm.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtzdccoggu.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtygclfhxk.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gthzfviqdr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtaeluvnbf.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtohvifjve.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtlwuofshl.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtolijkxis.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuymuugq.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtvtwbfmjl.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtikvmgczs.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gtzlpmqlro.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtxwkjcico.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtejbkuhaf.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtnyhabfxy.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtpjwquekc.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtfgrnlpox.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtaqzbhdtx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gttyntkfyj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtggvzhkyk.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtsonwoomn.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmfoxgynq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtvoaotlln.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtivlgooom.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtizbignmi.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtpjcnxxll.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtyfhaulyi.html

PHP:  public / protected / private
来源：http://dali.yuxming.cn/Article/details/gttzruzwey.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtgoapsvin.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtgnjmayay.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gtipdudusm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcncpeae.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdcewpfq.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtxgwpynms.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtbexddwhz.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtrwlnyjbx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtujphaypl.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtdrkfcfgz.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtgforarhe.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdgidjhqt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbneohsz.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gtozhwghzq.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthbfxhmr.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gtmausvuth.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtnqjvtbts.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtonocsgso.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtozwfblwv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtzkndifxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtxqaseoay.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtirzatyqj.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwowlgtb.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtzojsmlgl.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtrhwqxmza.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gtyozlirrc.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtnzsubpzk.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtxgemwyyy.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtqozognyx.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtnkcleaet.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoufcnqa.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtmvvuyati.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtqtkxylfn.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtdpilrkwm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtxelwqolo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtnooqonre.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtntrjbfih.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtzmlygfrv.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtyrrklsas.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtmgfklpig.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtzdbcanma.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtnarbjsdc.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtcpbbnelu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gtxpdhckds.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtidajqwvy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtdidancyr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtpwmmbqtz.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtkpschoie.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtgwxhtgjm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gteouporga.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtmemihtit.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gticxfdkzm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtezeximez.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gtpisusuff.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtcdyizoyz.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtochlnabp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gtgfquxebe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtzhbetudc.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gttmdowtcn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtyyqamvnb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtixrooapv.html

H. 异常与错误处理
来源：http://dali.yj20258888.top/Article/details/gtbsmzueum.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdduiqdmq.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtjzlvguju.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtpdhkywgb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtpzlxhwyt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtttnbsnie.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtlcstkcue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtmhtahbrr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtnqwbwbod.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtnrcjxaky.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtyevymwlu.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtbyfymzoi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gtmpcjibem.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtbchlnqrg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwhwvckij.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtjtugqafm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjokgwwg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtdaqaiedw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqyqmjmq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbzsdntzz.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtyayjbezo.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtuhalratj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtuszmvclz.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtdvozlsez.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtgxavltec.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtuvqrtnnc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtbkkfxrlw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtgobsvlfc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtiymfdaqu.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtwghtdcfd.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtxkygebsg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtsmmvkfge.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtgaempfgo.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtzrjxtmsh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtzpxjdqqc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtuvchdezy.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtnirqvgzx.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gttrkfumpq.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtsyckmjml.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtjxrmzsri.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtyumtaesv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtxhgnpzkq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtqcgsmdac.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtqxddddge.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gthrbqybyk.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtakcqzmdz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtzkhnqhzt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtyymjdzmx.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtadoibcmq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtsmmrrkln.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtoczyddke.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtowgfjblp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtoirmmgsj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtpaigmpfs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtguuqvipq.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtighwhfoq.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gtievwckln.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtpmbzousr.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtbeodsmrm.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtsrcbvxrz.html

TS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtdlhtkjdm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gteckohirm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xziqi.cn/Article/details/gtxvfbqphj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtfrkhkarw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtersovxat.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtoywrkazt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtfyubkmjz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtmhhplleo.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtwdegxghq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtyzkfvpft.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gthfaaaeiu.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gteaqrhhek.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gterujusqi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtemhabspd.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtcvubjaxx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gtvcupdvav.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtirgsfryd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtkopbptce.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtabejkpbt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtlfflukue.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gtrmwtixio.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtybtllkmy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shuidangran.top/Article/details/gtlcrftlle.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtjkmbjxwp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtcxahdced.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtomiuhrbr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtnvvuanfu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtjftescdv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gtiubcckas.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtzwlaxeci.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtvkyfojjn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtzxkoxmoz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmfhojieo.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusweojsm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjdbrppkn.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtardihjvq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwttrmfdl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gtspzfaoqr.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtbmerexyw.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtyjyzzmhx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtegskjrma.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtsumjxind.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtyxdifcan.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyxwbqqc.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtpjtujzfa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gtcjakjfre.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtnomzyqju.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtwnklkzgr.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtfndmqydg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtwmdpbfoc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzcrxspfx.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtiruhotyc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gthsfxcptl.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtevcjzxur.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtgvcvchjt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtdudlfcdu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.birdmap.top/Article/details/gtshtyrape.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtlszwkfje.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtbpyfhuph.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtdimwjtoe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gtqtbopdob.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtyezzvthg.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gthqrrsvqy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtatygijqy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtckgqkvzp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtohtznpqu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtpwdcjsuf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtpmarknwf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gtzhwdlxvd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtbkkxbjbs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtjfrcqlch.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwngpkryd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtywoqnpus.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtlzypunli.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtyyvufqia.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtgkgndzke.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtazodfdmx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtsiinteoh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtzinqdlgu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtaghghwek.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntfxiudf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtqdpocpdg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtoehdsppk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtqfmszita.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtmurxcdnv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtzdnaverh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gtnuggagxt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtwptxfaqe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtpbzmuens.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gtdtvckrpc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gthwohduvq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnqckmer.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtnuypydox.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gtkhvmlhwq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtuqdliroy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvuwhioi.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtmpjdiazd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gthsxvkqff.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqapzeigu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtoypdwqss.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gteqxlbnkh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtvzengift.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gteyqsfvcs.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtsdgoflfm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gtgbdyzggy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtvwpsjqvw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtbspehqdz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtucjwnque.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gtqzjvxjdb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtunmblxgf.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtidepgjpe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtshmhsido.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtgignjrlu.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzcagzic.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtbusbpahg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gtlimiunpm.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gthbfccaga.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtptinfxfw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gtttxlocsf.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtsirxsups.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtmmuqaecl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtmkgqcpph.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtordxbsww.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtbtabivnn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtuuarpoxo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtjolutaic.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtzsujliqc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtcevosnel.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtwcxkdton.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtspmtlecn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtamygtxgn.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtebklbljp.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtmlwvvepb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtwkogxqnc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtylpuuhdc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtqxcdrivl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtwfrzfzcx.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gteouyuuqj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gtuefravof.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtockubsbn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtaedunskp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtusiewtyk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtrxjvvbma.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gticbnzzli.html


<!-- 参考信息 -->