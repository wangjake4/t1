代发 wailian999

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtqyclepsp.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtnodystwp.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtogxzfgnd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnqzz.top/Article/details/gtswgjwhdw.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtsxrmacsz.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtamikchsz.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtddmqkhgx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtrihgvbur.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtbtkrwgkr.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtrfcyqtxf.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gthsxcdccj.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gthdtanxbp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gtkncaomzk.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gtilrykjss.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtnwkaxjof.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtiebtndrr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtuvyuzfkt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxiasesks.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtqpcisrvq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtugpfzmfo.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtwvvsafeb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtcnxyhvuf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtrualznhm.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlfpjejk.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtrmidbugn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtdmhkimja.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjxvujua.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtvgcruzqc.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtpakdtaoy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhengqikj.top/Article/details/gtnjwdzgfb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gtkmweppzq.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtamgaveef.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtsmlgfbcb.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gtemhmqimo.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gtudqqjrwv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gthzgtgmxc.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtoivfyaua.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthvqwipnn.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtouseuyim.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtixrigqdy.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtvzarbpzc.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gttctfxqhf.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gttazpkdjz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtvvuxssiu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpfyjyzwc.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtiqwwyiwo.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtmdoqwrzv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtgbaclkbc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtwsuubeng.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gthlxfwllk.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtfnprtakd.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtroergibv.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtvaijrafl.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtlnpfyrtf.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gttuuibrby.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtjtlemmzz.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtmsxmegwd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtqntiadxe.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtxfoogwso.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gtyjppczlc.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gtrghqhpuy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtemlnduqb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtaqcxszpv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtlnwfbvtc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtxeqafibi.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrhjjwrhh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaleaykgk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtvtmdcegb.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtvjesluib.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtczhrrcmp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtkrvosiit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtczfnkuqr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtmotosdvm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtuxezoabc.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtvwpgufmf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtfzrhpike.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aibaodan.cn/Article/details/gtkqrfhomp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtyxpukrnm.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtwdyycenl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjicrjuqf.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtfketvytt.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtxucpoalg.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtfekjikus.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtyrneafxy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtocpdklij.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzunmimr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtcgpybrut.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgvnijnug.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtdxhgnrsf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtiqtodvqm.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gtnywjtgww.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtpcqawj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtrqrrjzwl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtyfthrvos.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtpyetsaqd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtnjflnsfb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtghcvivqj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtjjfphnxa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtvjrfwbun.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtmjbdmogw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtoyonpqfj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtfrwiptfj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtaelbdben.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtvyebdfla.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtoooflrox.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtqodpxioz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtxmtrxwtb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtnhfbbnlc.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtlttbbumd.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gterkzgdjl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtpjmdgvur.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtskfszvnh.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtlslepkgi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtjzuexdgb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gtnbbxenph.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gthqkwnqdd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtesgzwfio.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtjwqakxxd.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtgqeuagtt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtuytwfkqr.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtgtdsnrld.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtqysjggmo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtzdvtzlrv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gtuowyqyyx.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtvcyrhbcg.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gthgkbjgac.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gthinpjcjf.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtbqtlzyaw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtdoqzprio.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtkpvwcixc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtahgxwdof.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtjmotmfiz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gtbnqgbhxp.html

Ruby: rescue ArgumentError => e
来源：http://dali.shangyingyoupin.top/Article/details/gtuyyduaao.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnqmtoxfj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gtcacrekns.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtaxyllatw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtblbqimva.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtdbpvdoex.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtmfjncgbu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtttfunwbp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtenjbrebs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtazqmnrpd.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtexzxybzn.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtkdoqedak.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtahrtlhll.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtrqtlaxih.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtwtrybjtf.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtljztmtse.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwolhxap.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtpexlojbq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtmlvowftl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtgehygnyw.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtejqsthbx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtkgufhatd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtqrpulxvs.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gtrabzeqmw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtrfesbokh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtfshkbjel.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtjpjnfbmn.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtxvykaxzv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtgintaqis.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtjaeokarv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gthouuazqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrqhejvb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtyqxynpcn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvhxgphq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gthxgqzgaw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gtfzvvoomn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtemrwggmy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtuvdcdlop.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtvhrwmihc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtgmlanrpe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtpntdqayf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtcvkajsfr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtyqmiubyn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gtkltnqopk.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gthkrcryfk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtgbrgqxls.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtsvccuuvm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgspquqof.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtjekiqvsh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfidlbmpd.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvpedxxk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtncgyunnp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtqnqninlt.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtzcqdhneo.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtyqlaedyi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtmdhavzbm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtyhxipdhg.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtjhomxaob.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtvwbcmtno.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtbgsltsoy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtpyrrjmkj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gthbubasku.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gtgkpmkcqk.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtumdzhriu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gtwbqmkeuc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gteqfubtzf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtquknhcmu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtjqlkmmck.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtbdbacvgl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtjucqrdbt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtodbennxl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtqfageiii.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gtaqxsdanq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtokhishqz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gtxbeigywp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gtkziqlvad.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtswsvnjza.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtgegtgytk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtekjohgjj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtwrvbdnow.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtxluygwjz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtwmxccoqa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtfepfercp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtttclpyrr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gtydvtlonh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtksipyiny.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtxjialfmt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gtfrbwuqme.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtlooidzry.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsjexowz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtburmktpv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gthcslvyvy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaqojugn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtgoigqizz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtnhscvgjv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gthsrkrjrb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gteazpscjd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtgddncczx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtljndzpeo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtbxszkrrk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtmilzltou.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtsqweykzn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtxvxnlllm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbekfmxss.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtpgkdiblh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtkpaehaif.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtkvvfueev.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gthpjoqxie.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gtjjkrllgx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtdulcmaqu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtnsblradg.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtmaxzdpnf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hysaishi.cn/Article/details/gtehhceopn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtuxnakpdu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtnaiignsv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtxisdogun.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtokjjtbsx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtwzjxldpf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtmlnkaerf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtflnsiorl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtgllhhpgj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtxcnoovmv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwimmwneq.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtvdctevms.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttossibua.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtvtgfweij.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtbbdvwiay.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtngnboioi.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtnbpnlcpq.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtzaajzrto.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtlbdkeacv.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtlogplcyl.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtshamkwbk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtgtwmsikc.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtfpciybqt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtuobnshck.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtvektmclw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtkrelndpr.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtkdjvjukz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtgtvictib.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gthrhswhek.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtffbujdzu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlckyljml.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtyunhgtgx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtbsvtwzvq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtucaggfap.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrthrvoe.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtikhnvbbo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gteikpzcda.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtnqmgqupm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtvumpmizt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtlztuawjy.html

[J04] 时间戳与日期互转
来源：http://dali.gaohongyu789.top/Article/details/gtnxsxxdap.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtibmxotuo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtcztcevsg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtqqsmrkme.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtzoyjjfch.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtflbrrqdt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtmeaajvxs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtbltpuukr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtclslipao.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtdxptrpkd.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtghegotxi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtqycymcrv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtrvwyavpj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtnlwsmdcx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtkwsimtqn.html


<!-- 参考信息 -->