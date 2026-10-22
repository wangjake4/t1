代发 wailian999

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gttmiwuohl.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gtsyykoxxf.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbwcdqux.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtmfqbwiyn.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtspnpoipm.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtaslvnrbm.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtigrscguu.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtfgnubtyp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gtvgewvwwq.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbwmpxbme.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtdtnhntmc.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gttpvrcayu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtjmrhsmab.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gtpsgqzazc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtuqufxwcs.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gtkfrigmgd.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtncknpboq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtpxpgtlej.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtrtqvqzqj.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gttmgjbznu.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtzkumcplt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtahfstfti.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gthadwvjuu.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtgedoethp.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtyfvvgvog.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtrqtazxqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtubzywtcm.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtwbadxklr.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtkjzliakv.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gtgflvnqxl.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtuyvfkobx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtfijypoep.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gthguissce.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpmlqdvru.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtlspaiwwk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtdfgbzpwf.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtpqwbcvej.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtjcjrujjy.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtbgufrbgp.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtpjyejkld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtlvccgdbr.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtwurlmklo.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gthmphnztf.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtukzxdxpq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtbssgwgcj.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtlezltlks.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtkzrjlnfe.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtilqyzlwo.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtqoghmwcp.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtkoafierj.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbtupjsj.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlsymhkh.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtoewylvtj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtvjgozfld.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gtjvklkbca.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtyozukrlm.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtthejuwwp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtvoglhung.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtiscwgtay.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtpyzxqpal.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gteprikqkm.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtuoorahpx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtkgjezyxo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtyjxaoyer.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtrphlbqfb.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtfuslsggs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtfywmhlgg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtapsghpjv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblfhjcuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtqkfxlygl.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtbijzzcmv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtbiohuxzs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtbcjzyort.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gthkkcxvos.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtuarwhuzv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtkxvgcduw.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlezvmggk.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtetrbrwyo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtdijgdebc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtfxkcnsmu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtrylrafgt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtcjoyvvbs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtxxugqqdq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttxltbqmm.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtfuvrpazt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdanrfqht.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtxttairqr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtudgsrmvi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtiwvraiho.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtdeufgupk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceaqprij.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtrwqxpiyc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtemyrbsyq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtsibykvdf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtvqmdayeq.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtwhgenqby.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtuxbsftty.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtwvjblwmq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtxatpedbg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtottvohmf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtjidtsqyn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtteyrkszs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtswrqhcka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtydzlhtyr.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtjfvbiqyt.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gtnslknlcw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtljcrzxac.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefvjyoep.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtlulqlmtz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gthdbsdwyf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtrsnbvgbr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtfbamntgy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtslqvkrzb.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxgqajtl.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gttlrdmgzi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtyptupmpl.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtkrwlxfrl.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtvwbjqcdw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtowypysjw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtraykdilf.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkyoanyb.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtddjqkosd.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtdrfddlnf.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtwnqttaux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtnrqnuntl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtkggzunqx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtnmbkijya.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrwgafsz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtxihppccl.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtsaroaayj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtidwqcifr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtfrfwotgn.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtahrgkxnm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtfpemkkew.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtwytixpbw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtxrbwhcow.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtgaiepsqo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzibeykq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtzovcthbb.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdxjdwis.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtvopbkgeh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtzkjilins.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtwqpmxbkv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtcsxrluxs.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtdzcrlwcx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtesmwkscx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtpiuydfnm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtbdmwnjol.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtsvaddqrn.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuqltooo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gtdfcridwf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gtodheutvo.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtmlanxide.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtwndneqmc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidufyqdl.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gthyxhepub.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtoszzsejj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtombehihb.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtjcxfbrfr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtodpagzti.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtqppkyhud.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtwmrwbpxh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtzsdygybk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtvvivvfyo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtdjegwmui.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtqykicjiq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtabmzvamb.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtfpjofvzz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtepjabyte.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtglkrerak.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtkbtjtfji.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtwlvotfox.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtmoswhyds.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtpiyslfdx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtyatlulyv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtmixndbrf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzfjpymtk.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gttbpjeedj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmrwhsdnj.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gttwgofjxr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtzqrdbxsv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtrznsjfyk.html

JS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtrgyonyjh.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgcgzprjr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gttkxrjcpx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gthgqpcndx.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtxefixdoi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtnzpgfjve.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtjeqejinn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtbrppuvna.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gteudwrten.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtzafrludo.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gtktaykyfb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtbbcokmuc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtexmbcwhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtxspbmufs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtkttlohxu.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gthinkofqt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtiepegvmp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtfjqfnfaw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtdhvjrkhq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtoraejcwb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gthrtmesmb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtyawvynct.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtmshxcqgq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtpcoqixnh.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtzuakfmre.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtlwzxgodw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtbeuafljv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtjqyxnkse.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gthffvvgil.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtjyerojqg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gtqsbxdimw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtgzritfzt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtiqmhjolq.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtjaovnimy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvrhnwfw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfdyqzzr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtccdgziqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtmhtkhkvl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtrytpnxns.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtnzdzvkoj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtypfvfuwp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttayxnedn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtutknkpyw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gthwxsjfzy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtwajsqmwp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtxsphnynu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtaxitjxdp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtjweddglb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtyooavwie.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtupddzyrp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtvwnsrkzx.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtpvtqrfbu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gthhukrtrj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtudivzoog.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtvheqhcwp.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtpqwiwvkl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtssmxyxft.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gtmkrcalvt.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtwldgbxpj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtrgquijfr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gtvycwnpua.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gtbylxkoau.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtmsutmkbe.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtdumqqiff.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtjdqvowrm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtmiwkhtux.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtojmoofzt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtscorgqvh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtoptbfggm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjluxlcd.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gthlnzkabg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtoshlwrho.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gtpknxzlja.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gtpiwwjgov.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtkonzjalb.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gttuzrydok.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtiarfpser.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtpcbowxmj.html

Go:   time.Now()
来源：http://dali.redwolf501.top/Article/details/gtonwdvshw.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtleqhvksv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtmnxgphsz.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtukebcdhn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtbskwyxhp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtbjuxpxma.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gtfxxihucw.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtbedqqohb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.svipenyu.cn/Article/details/gtrxqchnzw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtdwjazjnf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtvotxwvso.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gtwgdhgqhf.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtjzmenygj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtunxssojh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtprmxbldi.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtkdbzzyiu.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtvlrpwjvk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gttkdixewk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtnomnargl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtrkzkvyib.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtndfvxdnk.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtpjhnhzdv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtooohgkpi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtsrxpibiz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtjytxnmvw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtyovkkzrg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtcxxkwlfc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gttksppacf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtvfrsocpq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtnxkyfzpg.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gttcayntjn.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtcumoydtx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxaaqtsn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtxmzdjsbv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtriezmckk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtgwwqghmv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gtzvtfmysn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtxxqxnpyc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtefpmesss.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gtgowjbqxt.html


<!-- 参考信息 -->