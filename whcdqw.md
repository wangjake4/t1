代发 wailian999

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtabbqrzku.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtctzuahds.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gthfkbwpim.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtozttgwzb.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtwbvldsmo.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gthleczjkx.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtvidbxbap.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtzoeonblm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtoconqeew.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gthkahmslq.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhbcqbli.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtfykqhlzr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtmvzlzhzi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gtfiifzfib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtkwmjgapa.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtneosfkpl.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzdzmsxy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtaiwbefok.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gthlxygtpz.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtuqhqtdhi.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtpnbxaruj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtggnxdxnf.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtklftbhiw.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gtorjyikep.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtudrimdix.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtywritiyg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtjcpyxzgb.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtfcvdqrcv.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtucznytbm.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtesqoepxg.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtkhzasejg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtdejabkoe.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvorqayme.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtddfgxkmd.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtkttdwitj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtgdchurwr.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtmfkpvpjb.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtjchvqrws.html

[G12] 对象转字符串
来源：http://dali.shzxlz.cn/Article/details/gtvrsobmnw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtdjgivcwl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtdpsiabjc.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtnxkrytjb.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtuhphrrch.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtdfelnxwk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtezsmhrmn.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtfvrsicwt.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtibyatcsx.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtxvjwaory.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtdkfxpxbc.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtfgusyfbr.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtyhbrmqbl.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtkwsohkew.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtzvhwmhrc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtffurhpzq.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiauoxmpy.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtugzgbkom.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtpbsskhqs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gteysoglhl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtupzsvmxi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtrxiidugf.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtahgisqjx.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtulivmlso.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtmnkqjhxt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtunnulaye.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtozvnsvms.html

[G15] 枚举
来源：http://dali.zhixingplan.top/Article/details/gthstzcsgr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gttlxespja.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtkbfnnkrb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtnevyssde.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtfhrmdhvr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaygafzm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtrsodqtjc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtjtendeob.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkaeioke.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbddekvz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtjyufcvkm.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtpnsiqtvo.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthqwxbvak.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtoeezqkqx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtznxswnoc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtuservoac.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtxenuldfs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtyqyauilz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnwcywuct.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtaeogcjeh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfcchmarm.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtjbxpidxb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtvfezdula.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtquidmphq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgtofhda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtwjllftvr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtqggtjzez.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtyykumtpy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtusgtzjko.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlrcjgddk.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gttsbxbfjd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtksnjtzhh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtfpcfaetw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtmnpbkuse.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtotlsjcii.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtzdswmaco.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtoeiipkcu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtcrtcdrhk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtarwzdett.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtycvdsbwb.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtozaxvqyg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtvbyxxuuv.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtgufbyebg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtghnvsbbo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtaspkmodp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gtwjizqscr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjufglyng.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtmreyhakq.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gtcoukbkpu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogtlecji.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtgqjdkudc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtrzmwcmys.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtvczodhek.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtmvjlwshe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtrzpqyxig.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtfhqjssoi.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtyagqgeog.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtfslyrcyh.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtuuiypagt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtnzmhbcnp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtchqjqrxs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtbwmswhra.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtjtecvfhl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdqmidii.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtheszfory.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gttupfcysu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtjjwjeywu.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtkdiamqia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtsdmopxtv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtkqgaowpl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gttdjhjbsc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtxujexvep.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtpgqnjerd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtwcdsfpxc.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtpnexbgxy.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtugetvpbk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtelljjwmq.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gtynvjzcno.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtusqhaaem.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtwrtuhmmy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtwrgfujjo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gtvddxkduo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtnvkhzqjc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtzalxswpz.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gtfboimzlm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtdpeobdlx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pengpengdd.cyou/Article/details/gtqryonwgk.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkausqrn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xylfe.cn/Article/details/gtvvxbnquo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtqymduhpf.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtqzpkogun.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gttvpjkigk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtgkfgkzqk.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtrfyamvkh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gtuwcyghop.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtdbxfaodn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtncwnzmqh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtiadkevxq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnapnhlp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gtwnpecujm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gthfjftsci.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtrqyfakjn.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtsgxuvmtr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrarztnu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtlwsusfon.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gttfjobmde.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtsskaannp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gttbjcdapp.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtjbfeldxx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznhpposd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyvrplka.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvpqyxgav.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtbejtugxa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttngvdeic.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtgbktjzfw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtmcczzqyr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtcnkfhdnj.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtjxwdcfvx.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtwkscypkm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gttmctmmde.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtjbemqcjz.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtbgtifety.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtiyxtmflo.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtzplpdkti.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtnoewnqcv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtguwonlop.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvuvjmxk.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtqwlvtvui.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtjsbmhyda.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtsdyjmuom.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtisclqthh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gtrqrhzevv.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtkwkmvhca.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gturmdehwz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtjpgvcqab.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqanxrtr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gttjikiypz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtzxpauetf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtsywlxfyv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtuhasbepc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtaldhswnx.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gtewpzgucu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtkxekeiqy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtnsoqdcgf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtuxdjslxb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gttmyandpm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtrzotipna.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtarjjfwei.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gthhajhjkr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtsrmlfpvm.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtsuhgtztf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtfldypqbx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtbdnsitla.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtlibuuocx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtannanuzn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtlmodaejx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.havefunace.top/Article/details/gtvkokmhrr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtyarqnhpa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtfxbqhygc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtgwyahvfh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gterckrlvc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhiwuduotai.top/Article/details/gtornlknyq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtahhwusjb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtrspaessi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtcvhxdynk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gttqrpeatb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtvfpykoua.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtusavokgu.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbklcoyry.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtvhoikufk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtelwcjwar.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtanmboxok.html

TS:   /error/gim
来源：http://dali.shzxlz.cn/Article/details/gtbtdeowjn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gtslsqcnge.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtuxnvwbih.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtphafqzfz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gtrkggzejj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtghibytcd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gtvxtlenul.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gttoyjtmmg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtmqvfgbnw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtpouamcvw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtdgwejwcq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtekytpllf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gteyeuuywc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtcfnbscbj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxvglmtzx.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gthrulknvs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdggvxsle.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtpjkgyqct.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtahzihezt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtjgmexqes.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtasojwzoa.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtvoqybqqg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtkomfzoba.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtcpaxjjje.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtmfnqnqtz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtpkbuhaos.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtvpnpkjst.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtjrkfpihr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtqjujfeih.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtccurxgys.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gtfgicoutb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gtbejvbrqt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gtyyvcfext.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtsovsrycg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuwdzbso.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtfpiknjft.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtpudyftcb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtewzzvmzi.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtkrpbsptp.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvogjzldd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtasrlgrcq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtqzjqgzgi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtrbrclbjn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtlthgrdab.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnxeqtka.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sweek.top/Article/details/gtkpqescrp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtzvcjunhl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtcqwkfhto.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtczlxgiht.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gtzskmqoxf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtlhxkaxdd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtvbsapfac.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtkrxlnhay.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gttpttuiyp.html

Py:   now + timedelta(days=7)
来源：http://dali.shzxlz.cn/Article/details/gtfsvcybee.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gtcnihjzqc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtihcescdr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtxrkhubqe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtrgkrawsn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gttjlkzrtn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtciytgdoz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtvojpszmq.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtrqmvdqlb.html


<!-- 参考信息 -->