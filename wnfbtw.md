代发 wailian999

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtgjqsufnk.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtjldshnjx.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gttjnxbcrl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gteyduucvn.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtisgltffb.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtgszozllx.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtjbuyledd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtuffjznnc.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtgtnnjcdo.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtoxfvxktt.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtunmktlya.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtclikivbp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtvjtypwzw.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtcaozhfmb.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gthisvahtc.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtpgomznvz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtxypuohbs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtwvhdljez.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtffwwhrpz.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtwsfeimgs.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkoywvqus.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtcwhslije.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtsjpfycqv.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtyatcjncr.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtlwyurtkx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnrkfdnx.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtgptqwpfq.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gthvttbfwy.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtanvsvqis.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtujutpnvr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtarywwkev.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtdfisfpav.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtgurvscbi.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtihbsvmnc.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtammbhqwy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtvdzvqexa.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtpvxutxzk.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtprrxpaqn.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtxuieysnn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gthzaovjgh.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtjdujseau.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtxcsbkfbw.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtxnasxppv.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtfvezrghr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtmmvisjrx.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gthgqdibln.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtbjewosex.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqczxfnyg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtnugfzkjy.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtnirbueeb.html

C#:   public override string ToString() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtgpwhtlje.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtyflrbust.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtyybtqwrm.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtyeopiddc.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtqmsbcspx.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtbrzzlphr.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtafbrliuq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtyphaknhr.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gthpwjzigh.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtcmeeknyi.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtknrkqlzs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtearaxavp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtspzdwsfb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gtvjpoxpuf.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtjakysykb.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtvnpnswtp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtivietzxn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtunhqfetg.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtjmrljasm.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtfgkknwpn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gttoqlxmig.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtmevumipk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gtswuliqpd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtojwbaoqp.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtzypjqjwv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtayzlanyw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtkbdyrows.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gtqypnctlu.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtlrzdfizm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtyywcpaxy.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtswdyeght.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavftbptv.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtkwbazakm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtbhdprxtm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtklestmli.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtwkbbhdyv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtyolmepcy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlzguavqh.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtbrnghlww.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtajcxomje.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtqcqxqrxr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtxzjwfsmq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtkfupvtpk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtfpekakyf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtiahlcdnu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtlrryrdsf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtfixqchig.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtmpxmlcvj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtmbqwntov.html

[H02] finally / ensure 收尾
来源：http://dali.yongpay.top/Article/details/gthkxvxucd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujoqbmtv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkghdwgxx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtyrcjpxua.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtrqbrorlr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtygdhbufn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtrndirxuv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gtvxkvtoqb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtvccqjhyp.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gticfwanov.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gtgavilyhu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtslpeqwln.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gthncqgbsp.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gttqazaqoi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtclengsth.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtxuhbzraj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtwtzawcwa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtctkteqxd.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtqfgtjhvz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gteuoerdfn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeaxqdih.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtatgivxrd.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtgaqjzicv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtnihwuteu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtlmwcmjgc.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtumaoylyy.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtsmonjuou.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gtbpucwtki.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtyowavvjt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtppdcsgkp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtjydbzlfx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtwyoncygr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtpexnbgug.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtjbvyquig.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtrfehuvqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gthzqgscck.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtgvgaufaz.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtcftpzhqp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtxgdraqdn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtgsmjqyjc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtvtllomsn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtffkiuhbk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtlrznhaxl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtfzhrsqhi.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gtdykdfpoh.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gteljbnpiy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtpjitwzvk.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtyauwhczt.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtvfcxjbqi.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gthxukiwsi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtyabyyhpw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqsfgiel.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtortvwqjl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gttufvieds.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gtybdmjzij.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gthdfvcikc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtwrpunuur.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtshtvwqxg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gttukibkcd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtotdjnjss.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtfllrlwtf.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtcobbzezq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtytdfqopf.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtijeaheju.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtrhwrvluq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtizjgmxho.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtuttdrlch.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtpguekled.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtljnxcclf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtonkbayuu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtruebquiu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtzccvfdhp.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtrlnmbvwa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtdtiutiya.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtyoaaoovf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtdxysttrs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtvkuhjmkw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtxphesous.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtmtinqoio.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtpdtoqgvt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtbpssgmtb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwwlysnga.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtudeolbmc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvcazvje.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtxvrecsmt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtglwekfga.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtkvlfgoej.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtjscsdpdv.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtpeaqgihz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gthrbwcnnp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtphiabigf.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtdptcnekp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxfgkydb.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtindsijqx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtkstvwvqt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtpgikvruz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtwswdddpj.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtubjjhchj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xylfe.cn/Article/details/gtmvalpjcd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtesdnegmz.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtdvohiuyd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtxqnxfrhz.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtwcuzwvho.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gthievdfui.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtjdfffzei.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtfqfhtcfg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtjfciplkd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpixejmap.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtrzhfmznr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtfcbenahl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtnqcktvka.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtrrerwcei.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtrqkexhsp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtzdvtcc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtmzvavhxs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtgmcwriql.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gthrsnteib.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtrmmxsirk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtfafpvmva.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtmnnooisq.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtjykecxis.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvkssrooa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlosqatbb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtjavtzhag.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtokdfqjmo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtkkxbtxut.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtxkrdwgew.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtabkjqvto.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtcnhllvux.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtensovcco.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtuzgqgqoj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.mhx1999.top/Article/details/gtsbekveod.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtztrzrpgl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtprfevmao.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gtrklhnatx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gtesnycdqh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gttguufaac.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqdpfpci.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtcvwuhfdw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtjvodtobh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtpuxpzlda.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtnlxjzdrz.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtaziiekyi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtmtenlluy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gteljobhmb.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gttwuwfthh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtezpizbqe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gtmxjjqxtb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgjdzjks.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtdinomitg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtbevwbnoj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtbnojfexr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtikaszksh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtaoxhmcmf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtrdatmxba.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtpokfkjag.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuavrfibz.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtiteaupxs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlvfqwqzk.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtvaorxsga.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gtzwqgijcc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtluhmzruw.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gttuyaqsvr.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gtvwwuosth.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtgvxnxivu.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtvgpcldos.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtubxcpaqg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtdarijbvx.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gthtiqmpok.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtudociiny.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtuzrardku.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtgwfcsjjh.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnrhyqjn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtvbjquaeb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtvjmebnwx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtceaiuoxm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtvvyvctdp.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gtpesrninz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtsyuoksms.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtlizxkqsv.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvuaquoh.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtyuwswoes.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtcjvmgvzh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtksxvayna.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtarzwwvng.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gtjqopkugm.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtzuzpjzew.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gtjrjdxvcj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtxagcgqtd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtyqybunzd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtnxqvednk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtphxpugwq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtefambqpg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtmgthinsg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtjhtpbiwd.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtznvlhicl.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtltbbacxe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gtxfgfouhw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtmxjjymjx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtgjebtseu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gtvtunsard.html


<!-- 参考信息 -->