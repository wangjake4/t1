代发 wailian999

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtyvfeobgm.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gttubqmjfi.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtjctfecxz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtdvxgollk.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gticywthzz.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gthebvxxxy.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtxmuppqii.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gttbuonxkf.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtseydkxcp.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtkreupoiv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtzwzkgkxn.html

Java: static void f() {}
来源：http://dali.shzxlz.cn/Article/details/gttuzobtik.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtaytuvggj.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtvncqcoey.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtwsppzeac.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtsofxyyvf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtgskulefs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtattockvh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtpolzhmeb.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtteygimve.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gtanmzvtek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtahhlrowr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gtzxqjqvxh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtgjwczrga.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtepjlcpjq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhengqikj.top/Article/details/gttswikfiz.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtlpgnugqv.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtxyafvqjq.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpreblcmx.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gttngriwtj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtytuteeue.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtnigkmqav.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtqrbbeyfl.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtzzlzusru.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gttxiphtzn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtezinqpjo.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtlaudfcta.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtwbuqufox.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtyzgycvjj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtguarfzwu.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtzhitkylu.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gtrppachtd.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtxgazlnkd.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtbsitdpqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtjrvlyuhy.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtiivxdfqv.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtnedcxmos.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtbrgngsrq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtvnzunqsk.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtoaarhvch.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtkeugcivh.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtbetjcyci.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtxynbrbzu.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtchokqivr.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtbfxwqtde.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtwkzdmewd.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtdpkhhaow.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtimzycuym.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtutdfjzql.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtqucovalo.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpatguka.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtjywzgcrh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtmylwpfef.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtxdnbepmu.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtqdfklrgi.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtckyouvvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtztoluqsn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtnfampjwj.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtujnvvjeb.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtdiehwvai.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtiuyvvzev.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtfglicyga.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gtuswkdknr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtdvyaijed.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtoelwpwmb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtsgzsjbuu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtogaadrud.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtxypndnpn.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtqbgacxem.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gthtgmndrk.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtdjxwwkqj.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtylbdpmef.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtbebhaqyj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxuanxn.top/Article/details/gttyrtqduo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtbgwpjgzg.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtdpkefnyf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtelrypaxk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtneyjyrrh.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtbzybspaa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvahsnbea.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtfcvuwwcm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtukiequuh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gtbrowctky.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtbqzyllik.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gthqizjlhy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntipsozk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtbnjbhtcd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtyenmiinn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gtcprsiewn.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtpksqxabk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtxfhfhbrf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtyetwmjjb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtlxmnkaqz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtetbwodrp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gteejdbqzv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtzrvaygcg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtjbcavxqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtxqoffcvx.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtzzeypwuq.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtflmeoiyq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtkmqnddfs.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtxnbmgkma.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtsnfkszzs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtmcgmnvwm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtxvnbrbdi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtmrrfoaxf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtdivexzut.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtidgcrvqg.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzyqccoj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtetmwzgza.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbiryhxp.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtwskuicio.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtfowuajhz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtipxhkbyv.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtchzgfpje.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtssvsvjur.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtnqtaqsac.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gtgyjiojsj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtcfkxgvve.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtymjfbqet.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtjbnhis.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtuwtqqryu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtcuphbxkh.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtekqpgnvz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtlvqrzyio.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtvunlcuqd.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtnaqmecdv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtutxijjaf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtulgppcbw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtogybsuhq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gttsztlfdt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtzexcffax.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtfoesrhzv.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtizgknicj.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtxdjeqmvo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtnqpmayzs.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtyxscrzfm.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtfzvetnpd.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzroumowi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwidimix.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtizblgkmr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtsutwtfxk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtbgpqcxse.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtymyhvxlk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtedsrclqi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtpgdqrepu.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtljssaavc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtddnrpqyc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtwnqfgonw.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtumhhlmru.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtxadifbzv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtepmpgxml.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gthjachyhm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtsuikjuzl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtuwsntlmz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtkjdetfyi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtckgfcfni.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zdqjudy.top/Article/details/gtxlvcbfam.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtsnvxpkym.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtrfcmqxmt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtqrljbsqf.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gttjanexaq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtdwdmrval.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtpmbuzvjy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtdbkqhmpj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchkvxtdm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtjxyojszk.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtotyadopr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtastdobaz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtbchbyqln.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdqjjaapq.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtivbkgudc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtygccfmux.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtfkafcrrc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbiguckl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtruvenvev.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gthxhaakie.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtelvzpner.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtnllrcskb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxouyxzds.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtitiuyrgj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtqgfpjtoe.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtdvwlylhq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruweuibl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gthelkuyry.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbrloevw.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtswmfwbnq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtcdemptkn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtmptvexmo.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtgnsjklxw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtjwvntrgt.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtbkctvbuo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gtujpbqzbk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gttbfnylxe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gtlpramcbs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtiygnxktu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtkumvyege.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gtlujhtehp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtmdzxirdy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtrpvbjfid.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtasyjppfx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtqoxscovd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmotxnbc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtidnhcqeq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtsmfgcmbr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtqemrvzkf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtnqqqkyho.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gtglzwkkvr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtjihwyjwy.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtpoukqrzf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gtyuconvfi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvicsfere.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtnisuqsnd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtszfovgij.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtixfrwvma.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtpswjvisp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtlwhftsyd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shuidangran.top/Article/details/gtsjddikvj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gthmmhhtvu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtbhgpmdfh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtziquzdyw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtnlekistb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtjvxslswo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtsqicafun.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzshlpqth.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtzvtcuuxp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gttanwezhy.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtbwzozvwp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtxjmewhhc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtgfvweekk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtsiosgyyp.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrvilzeq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gtqetfqrjq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gtatzrgawt.html

Ruby: s.scan(/error/i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdzyoics.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtwujagkpt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtiddmbrhm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtbyffslwh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtjqogzlhh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtbovmejoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtztxebjee.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtdjkbxuzy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtaaweovaj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtgpvcmtwe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gthhunghhi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtllepbzqk.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtycddwfbv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtulslpbrn.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtwofuqdti.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtrbmhakwg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtmnbgqoco.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtikrfkdaq.html

TS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtzyjuobqj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtrrkbkndn.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtqpzugebq.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gtotaybxyk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtdjlzwmny.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtcolklnzd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtdzqjsqqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtpmwdlqom.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtbiuxqnaf.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gtqziceakh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gtwnhyuius.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtunjvmgky.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtgmtzgxys.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtnntxawsf.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gtyylwvanb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtvnvhwmor.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtdstfwtwn.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtdjitkrqh.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtatohewnp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtgixlfksi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtaypgbypw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtgiuoavre.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gtxsrarklh.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtsauxvoxe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtbfqczorj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsnatmkr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtmwzzcgdc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtfetmprdl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtcwlpdvok.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgrybspw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gtfbsesdni.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtocktfiqm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtstlpabcj.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtkvxamhlv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtgpnaupgi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtnnhrswxa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gteyzkptyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtbljzlicc.html


<!-- 参考信息 -->