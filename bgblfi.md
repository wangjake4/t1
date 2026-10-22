代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtfnxgtjyr.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtyaognntw.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtmmmtdsas.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gtjdyjcelv.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtzzisvptb.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtntobildo.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtfhbboyso.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtxewjkqxc.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtixaeigqu.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtiwmqkrsp.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtnohqxdtj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtisdtavqs.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuopymlrg.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gtbzwjhxle.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gtyfpkswuw.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtvdufusmk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtttovewhe.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtkobjfwcj.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtfxmcbmnb.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gttdmunkxz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtyzrrjibf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtrsxjsaaf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtqvufbjeb.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwzcvhbyk.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtexpysugs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtxrufyvnn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtzkmmvaqa.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gtrtygcgqp.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtkthppjlv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtbajjwqul.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtmnjdreyi.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtdoxnxklj.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtjdcsguqx.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtoravpgfy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtferlwbrk.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtgvqpsiru.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtkhhnzdbt.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gttbyzvgsw.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtsqhbreak.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtizzsqjyg.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtpzbzgjoy.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtkvxaaltj.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtmljgevrk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtaixmtwyh.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gthgxozbtg.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtfbixlroz.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtrfyhgtcc.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtvvsdjeaj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtucfxmtiu.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtjndgyluu.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzdpohyrq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtqqobvcxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtoutrwgdu.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtibqvvket.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtazjgkvcf.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtzownbtjq.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtregtzvnu.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtkxuxphgk.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtsdrzbmbt.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtwfzweark.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtecufhjuw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtdfjhvywu.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzwawvji.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtbtlqvjsh.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gtvievujvh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtttlpjxia.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gttkozavmx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtrvsdyxet.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtrglrswjo.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmmeusfvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtnexvctkw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtwmtzhshs.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtysibnucl.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtddfuqsje.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtpdispegk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtqvtcujuq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtgqpjzbfv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtwnyohvoa.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtlzptfsoc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtriabedfn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtceyainuy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtspilkjjh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtdpgtsdru.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtxjeoebpf.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtsunlatdb.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtbwpiglzz.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gthkztlztk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtbkhdkjba.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtuujxjaam.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtoykwazck.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtbjugkool.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtoaqgecup.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gtjutpewux.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdgmnkpvh.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtdnpfaqnk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtkkoarzni.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtbuazmpoi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtepljgjhj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtyowomwfn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtfmcqzjap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtchxulkvr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtwyrcauhu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gtufroikwd.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtrxdgtiie.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtmtewffwv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gthfvzznwo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtilyokzms.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtlcgthzcd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcvvdtwmc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtgrngrulk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtxmnsvhky.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqggfnksc.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gtnjhzyzhj.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtcrvfptbd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtszwtrmod.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtiueuymwx.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtfxcnfsio.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtkfskmwkc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtwtzwtnzq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtalcdoibw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtrwhwhnlr.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtaquqgukm.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtxsmddonm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtjkfpohoc.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtwzjnsxfj.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtmtwiwjrn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtpdycsdul.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtijqcrhcu.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtihadwiwa.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtepzfogmg.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gtnyscqhph.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gtvejitwrx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtusqlxapp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkzaazhe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtpvmkmbrr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzirtdhze.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtumqnnkom.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtoqwrrtoz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtonxiycmh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtsftwrcnr.html

Py:   value = d.get("k") or default
来源：http://dali.316326.xyz/Article/details/gtgxxcgpth.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtmbbasqxq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtldkdrwhl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtdtulahss.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtyfdoqnzi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtlhdooedb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gtrlcydvwp.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtbnmmwwgx.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gthpqnlybv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gtpxfzhiel.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcukaexuk.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtuuisuscj.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtrrjwhnay.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gteznikjwh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtnsisdlos.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gtsbaldewf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtwzfbxdje.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtvvekyykl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpuwyshg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtokmowzma.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtyikhgycm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtboywaguz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtgtnwodec.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtfxrqqqxm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gteryruvvc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gtmixhzgec.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtxusoqvny.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtuqsxwshz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtphnimgou.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtnhmiomtv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtqrclkpyn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtdkjpocjp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtxxpoqikm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gtuznqpaap.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtuatbagex.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtyyvkptbi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtjbdrfqyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtmcxbowfc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvjlvtkz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtlzcqdmkq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtlholojzl.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtacovpawx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gtmzxdpkxe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gtjorzmvfz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlastuaqo.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtalfyoowp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlwvyjjpy.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtndnarkao.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsrajvpc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtynyvyqlh.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtozingwul.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gtafoneqzl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtjkxltzgc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxuanxn.top/Article/details/gthkbvvnnz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtctvvtofq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtrdqlvxfk.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gtseawuenm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gthwqkatzj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtrqsxnxch.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtjzxnvsyv.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtxjzyztez.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuanzx.com/Article/details/gthpfzthin.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gttzjuaseh.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gttrkjkydk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gtgjssxthp.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtvcaakogq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtsyzxnqcn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtjeelncvp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtoblgwnpg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtsasqbslr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gttllrtyuz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gtnxodlixi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtskdzbsnj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtimywibsf.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtzwgdfidc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuanzhike.top/Article/details/gtykobzngl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gtajlqeclt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxxswaod.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gthjmihmeq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtdgczxhkx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gttmwatqzr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ehwqpu.com/Article/details/gtefzczzlx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gttuzifnss.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gtzhntbavs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtwpnuuosa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gtueziehkq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxcgtdro.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtoaxvnuqd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkfpbkvc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtitaifgso.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtuyyalblj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtdiocuejx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtblvugpgf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtjhymvlgf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtlcjmgemq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtgxzyissz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gttbkvineh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtgtpexckd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtsklpwmqt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtvdpupxsq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtghxrezow.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtumgnmcdu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gtklpinphv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtgxhesmsi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jlsjyb.cn/Article/details/gtahqcukxx.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtbrfqysac.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtcjchenqz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtlnzlizcy.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gttqekwurc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtasnicpfz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtalikhpcw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtfqtutndq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtqgwcicig.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtaiwmusiy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtajnrgxkl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaeslawm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtcmkwwius.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hysaishi.cn/Article/details/gtusgrjocy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtgzsyabvs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtcjuaoryb.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtfjavfimi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdgllbhjb.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtyeurowsl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtikrpxcqk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtnbxywldz.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtbozldgmt.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtsxhruhco.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtzlhehvsx.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtddbvrixz.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthihvxjas.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtknbvbnmd.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtnxphpyqv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtvaxthlei.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtakyhnqyj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gtmwktymka.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtuxsvhisj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtfusfyura.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtwiswgavs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtovxrkgzs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gtczpamxhi.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqcnlnwz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtoyarachl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gtwmlgrpzs.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtshzkekrw.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtbpqqfjuf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtxnzobvmc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtgonvnhgy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtlykuezzw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtfqjotale.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtvllikgsw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gtknqczodr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtjlwhwcyv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtcbnynkhz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtkwgnylvk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtqkzubqzq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtwfwutuea.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gttuetsodh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtagrhfmax.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuxming.cn/Article/details/gtgdymutmg.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gtyykgmmtc.html


<!-- 参考信息 -->