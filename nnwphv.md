代发 wailian999

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sydykmdc.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gt2dpyyeilk.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gt2mxemgkbo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gt2nqubftik.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gt2luqkaizh.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hvdoqbhl.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gt2wsmaealt.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2chohooft.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2fzgbzsuk.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gt2cfcabhyk.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2xdosgiin.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gt2kwttsamq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2otwftuek.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksfzowyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gt2npvuhplo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gt2einlidun.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jaialfll.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2iczcopqj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gt2xdntymlg.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2klowkpnc.html

[G10] 访问控制
来源：http://dali.hnxiangtu.top/Article/details/gt2ywaljifr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grfhlnum.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2hyasekzq.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snjqcvsh.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2caudangw.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2srqgvaeo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gt2vjekevxl.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2awhuuysd.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2hglmepzf.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gt2nviuklcg.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbsngcoq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2mvalgcck.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrxtmrbf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fgcgatpg.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2zkbvejns.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2blbmnkos.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gt2zfonccvs.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gt2cncoxcjq.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gt2ptqioxpn.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2azkrhnze.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2etpmvolf.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bttjvdgj.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mnusdxor.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2bfalfxej.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2xofpasvl.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asemhrdu.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2wmsjcmtx.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tudijuqy.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gt2vcstjkmg.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2skvmuurr.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2viyikjwb.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2saifbrnb.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2nxhfokvh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gt2qxwioirz.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gt2oicuhqsg.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2aqbpliuh.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2hhjiwqcg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gt2wfecrifj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gt2euwtbjci.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gt2xuyjwbpy.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2stqrnqpx.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2eclxmeke.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gt2bpqcdcid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gt2ngpwqqqu.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gt2dzmnchwp.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gt2iunaocvh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2kugzgcpc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gt2qufdtqqa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gt2vdqascwe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2pijaesyz.html

Java: enum Color { RED, GREEN }
来源：http://dali.yangfankeji.com/Article/details/gt2dsikgtiw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2pwyxveqo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdeymwoz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2fjampwme.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gt2brtlijqm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gt2zpdtbppu.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnwnfpaj.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2jzvkhtbx.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2hvzjvskp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2bdbrxhdx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gt2scyncnjd.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gt2uzdajsgi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2jbsrvoob.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2joyzugzy.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2swpnamyv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2copdiemj.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gt2okssxxqf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2ipqpofdu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gt2petyfwna.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2ycucxuod.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2pumrhvyc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2duscoqst.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gt2stvrefpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2gbyxfudy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gt2nybtskin.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2jrexjvkm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2lfsponur.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2byhwvexg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2tiivvbqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2qqowskoa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2fmhvrjte.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggmeflil.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2tnnpxwed.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2sbeyowvv.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xycxarhp.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gt2ufubroun.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2lmlfwchi.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2kbojaegp.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2xbpjhvfs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2yqqmbkru.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gt2jtefwacv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2ihwcdrey.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2sdirzbiu.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2buruymvv.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gt2lrwqhryn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jpkuetil.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2ppjyroiu.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2oyxqyuyg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2sosmwmjs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gt2htofzntc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2xhoezwbd.html

C#:   class MyException : Exception {}
来源：http://dali.tanke756.top/Article/details/gt2texsdkrh.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gt2zahcwaup.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gt2ojruehbc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbwpwkct.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2xvdkcpit.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2pxdpkofw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2aprnewhe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sltiwrbi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjvigisy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gt2uzrrdsqp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gt2adpscdvx.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gt2ybrunohc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2skaobrwm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2iewgaibf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2imtlfsqx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzmfqrdu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gt2kmskqwzr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfdybvsi.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2mcjeyhzw.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gt2gtgzgvlz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2xkamrppc.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2cgviwygb.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2ndnfuxdv.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2xqeqmcmz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gt2jweersgj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gt2rsvipyfc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gt2spjewmzv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2hkajzngz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gt2xfidkmfk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnqzz.top/Article/details/gt2oukvogar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gt2ybktzbcz.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2fwbfpwaz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2iwcmrasv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2hqmcearv.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gt2etiiyykp.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gt2tbqwrmmh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gt2sxhcidlv.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2ymtxeuvt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gt2kfljdhhz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gt2shohpqcx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gt2fjwgodob.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2ipjbjucf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gt2kshwcbsb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emnetqhk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2memcswen.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2mcoxzhcl.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gt2rxxaucri.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gt2gdzgasvb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gt2zhtqhqqz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2detslenj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcvmislu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2kljavqly.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gt2rdxtlqgm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gt2jhnkcnfg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2krkwzfpi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2inrbsvtv.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gt2qxtnpiiy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezxkmxeh.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gt2veuaefni.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2dwneoxax.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2ppvetevq.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2obzyihfg.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2jknuzkjx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gt2ettpnxia.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2zycycsbf.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwitixwj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2kdajpxly.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2laloognn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2vplndliy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gt2bapabzgl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gt2rbjlorph.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gt2grfmpqmf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2bwxulaan.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2nbdzyrav.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2lvugcasu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2uqrrtixa.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2vbbcasjf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2hclhoqzo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2nykpvhhg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnetqhhv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2etnuhyuk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2vditvobv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gt2ffoaeksb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2jnkmtpre.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gt2zidmjbxm.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2naddehsr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2irdcximb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2wxfsfrhd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2tdxaklsm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2susnnleu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2cygrgofs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2lxqibtze.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2aehskkml.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrcviaal.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gt2savowief.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idgggiva.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gt2uyenmhso.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2wzriovex.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2aadbpuiy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2ozmixtnt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2hcwgsgrj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2udeuvjzc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqjjybma.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2jcrvcklg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2toaxvtbw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gt2hpjmtnoy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjufpshn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2pcrktztq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2mmscobyc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2uvunrmkn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2jwlsulgq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2ugtjvgzd.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gt2kluqtanu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gt2ayejhlam.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2ulbimpnx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gt2pjsimqfb.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmngwyom.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gt2woaruadh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gt2vcsmdsod.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2qztqmdyc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gt2cxdjmwcj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2fvlxloyi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gt2cljerafk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2pkvyrtdj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2qhukqygi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgshjzyl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gt2zzqgkmud.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2votqspod.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2lchdmfry.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gt2yjqrlzih.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2eemctddh.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gt2svfmgiog.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2pcragimq.html

[J01] 获取当前时间
来源：http://dali.zdqjudy.top/Article/details/gt2yqslqvfr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2njlbacns.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2nnxdjven.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gt2benjkrgj.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2ktciqpmw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gt2uzbifycw.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gt2fxllzcal.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gt2bwdrhxpz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gt2oxpzahfu.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gt2yndjbppa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gt2ymswipxx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gt2sxgrnqgq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2xicocvzi.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2kdbdoysu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2kehvmbit.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gt2cmiovayr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2xhlkxfxo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2ucsltqjj.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gt2okfytzku.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2ifjoadvs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gt2wzuawgqn.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2tlinznfi.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2cvflgfna.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2inuqoqms.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2rbuyxnvh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2vqloftuv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gt2vrmirhmx.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gt2yjmrocrt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2btrdkfzv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2dselcsta.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gt2ixjsrkuo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2skrpzlgo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2qemzctym.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2yutwyuwl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2evhiljod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2cugntkkx.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpmnxeyk.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzzeuyiq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gt2nwosyogl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2ctwxhdzk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2itdtuekl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2sirequyc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2wqqgafaa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2sijcydxr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwoawad.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gt2mqzmpaad.html


<!-- 参考信息 -->