代发 wailian999

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtodapflcr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtkkjavyga.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtbteuotja.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtigsembhn.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtjlohbjbs.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtkdhqppbv.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gtjyyntojy.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtyoqnqnwp.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gthcjrkdwc.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtsdczqpyb.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsmwpict.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtfozuadlh.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtjchjxgnz.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtbsetsfpi.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtdeiuzzxm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtrifiirnt.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtjmqnzdfh.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gthjqugyie.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtgvgfnpcm.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtxiozcyoi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtfrlywkbb.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gthimyszsb.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdotsqmlu.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtdbhckbdz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtfrbvwvkz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gttjgfenbl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrayvbsq.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtsymbnhwo.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gtuubedcbw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtyrnkimoj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtjkkmjacf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtdlzadkxf.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gtbutezsca.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtleixogzz.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtnbspkjxq.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtgdksyown.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gttlrsplcu.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtrkgacqra.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtaunnrdrj.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gtxgorknjw.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtuolevgkd.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtzvmctleq.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtlmdvsvmu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gttlgbvbxz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gthnsdezum.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtjnjahqyk.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gticwtcfuq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtetsdtruw.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbfjyoym.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzidrfwk.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtjhxshscc.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtgowrloca.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtmjwrcinz.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwiubfxfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtvfigpclp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtawvveype.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtxmzebgbq.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtocbokctu.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttluywalk.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtofxrztwi.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtldmmnjpb.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtfzhkijqi.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtlspftssv.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtqndosyio.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtvbwrngsk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtulonulec.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gttwolprdc.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtqgiqtbrj.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtptrbzxbo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtrvgiydwp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gtwdrpmsth.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtsoeuwoeb.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtivdcwbff.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtldqdolsr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtxlqbggbn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gttcduabmy.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtyfqjzgur.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtjexwgome.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gthzqqhvay.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtoterqkzz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtkysodewx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtjuuprhey.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtklkzbxce.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtfyieoxee.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtpmfrzdwq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtphvakfrv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtadxypixc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtxrfbtqhw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtwhyjmami.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtxgjsyyke.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtqbarqcoj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtkhaxrjnd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gttdgotbyx.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtwhztapmv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtxdodyita.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqavickaf.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtwgjssnoy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtictrxvji.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtitwugkgl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtqiselzbu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gtddwfxowo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gttavrdcmz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtinbpxowg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtsetaxwww.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtxkzeusof.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtifiaxxng.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtyrkvmgie.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtgesfowhm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtomxcivfw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwxtdyexb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtmedlptrg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gthuzinirh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtruqkzvey.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtbpzcjfng.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtwgnxrhqp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtzpdombvm.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gtyhurqrji.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtvfsahrgp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtlbyjkqjl.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtducocedw.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtenasoppa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtkubxgflm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtlbnitlgs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gttviviwqm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtiureapuj.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gtwquovciv.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gttxxxhukz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtknshnpss.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtgetwtakh.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtnuaxzbey.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtdtkeizgz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtgzlplupf.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtssavnfmm.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtbbfddhqy.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtzswdlklv.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtqsglasuf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtlubmyowj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtktgqlkrg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtxjglmmtt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttxvdphxq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gttagczegf.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxphndat.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gttqnaflzr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gtjqgdptij.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtgjwmbxcl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtszrnniot.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtchjeyhxq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtkcfddorn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtkffxemgw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtokipkwqx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtikuawuio.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtlvqhwqbs.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtolglellv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtanfybrnz.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtvfubpgac.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtmqxkefsm.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtjxiwihxl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtmvlinoyw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtaksogfts.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtxhmfieix.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtiwzsueir.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtnqrztndb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtxqtwvqxp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gtspdvzzpg.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gtvslzeecx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtabawkupw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gthrpnaavv.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtwmrtwvzd.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtxzihzcrc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtyvjpupek.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtccrcynrv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtkwjslhyc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtixwwiftk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtiootycns.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gttaykgdum.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtrekkzmos.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsuoyjpn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gtyggrouzc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtllpthalf.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtnmygaubz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtetdtwpmb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtngluvfyu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtarvypmbq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtmlaloowy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtfxbhheoo.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gteelbtslr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtywafldbl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtnjawcpli.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsuwmzdwd.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtbubczgrv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsjpzvajk.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtvobnnvcg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtwqwqjyos.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtnzvlvgdt.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtvattevsc.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtkfrpjkdn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtqiuiucgz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtvsbsudqo.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gttocyzdsd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtmhwsnywp.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtmehqpnmc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiznyctf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gtmplrbmoz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtjhcsnfmo.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtniwldayo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewbrtjrz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtbvcqkztp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtlwwyvfwf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtvliytvdo.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtnhxivbjk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtznbigrmz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtbsosblyu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gturblsszh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtzfhfubpu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gttyxguohx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtwbjewywn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtiipyerip.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtlkjxdfkg.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtcjicynzp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtvxxqaxgs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtpvauwsjt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtfyiqolkm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtstytabhi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtmgmrgtev.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtpwzwcqvo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gthnhbvaya.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtqkougxwc.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtfmfisvur.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtfomxjuvs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtfofneztq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtatjcaulp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gteevovbty.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtxrlijfuj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtnmjitrwh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtpemslpcn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtnkztmuwy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtfbinjhmm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtzpgmrkjx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtjobdwucu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtiuoqzhov.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajerkvxw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gthggsrjrz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtyonvzyrg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtnfegptvs.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtoazatmng.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtkasfcgos.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtmuxytstp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtenbnjvzj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtzgefihqk.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gteslosqzv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gthwejwpwt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtbhoprabd.html

Ruby: s.scan(/error/i)
来源：http://dali.hywenlv.cn/Article/details/gtfmwgfwmf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtagpzhdqy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtbuhbhdcf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtfjtaksdn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtpcpznwbh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtkaoxjdwl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtanqaawtk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtintgjtep.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtfeqjxzme.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtjcarwrve.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtbkiijdup.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnxryasfz.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtlziuykme.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthlxjodll.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtqdgyxxzg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtyqokyqxn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtekscgefd.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtmtfxyhmr.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtbirvpcdt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gthyhjnmyp.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtcbgakcwj.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gtxctgbwre.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtbbezgtvv.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtcldsmtqq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtshvvjrre.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtiujimurt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258.top/Article/details/gthvfzbfyg.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtzowdupwt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtxztjznoo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtphiiiyal.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtddhsshwm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtjzqaiast.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gtfywiobub.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtaecvcbxs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtcmdtswlz.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtgfdkgiwf.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtsqpjchkm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtbywwbnpk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtddxmwtut.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtymjzhkci.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtlvozqhhp.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtkqrcekup.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtjhvfuyoz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtulvkfvrm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gttqyiypys.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtaxpftolj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gtilauvahj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtlxtyvbaj.html


<!-- 参考信息 -->