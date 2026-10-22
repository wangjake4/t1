代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gt2awqbjhvp.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gt2hbpzmfjd.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gt2bnjcvgsi.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqhfgtrd.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2csplpobl.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2lkqlgdnh.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2sjtcebzv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gt2crtfscpt.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gt2iwglawkm.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gt2nwyqtthh.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gt2kpvxeieu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efbeujhv.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2cqvvpfpc.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2oztycilf.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozxkdeqe.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttllfuep.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gt2amfaiusf.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gt2cctlgmcs.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2qxoeqzej.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2spnokjhh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gt2jxgkcecy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2aeyacuth.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2gnjhisso.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gt2flnktwvu.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rcheqizj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gt2aqiqbrps.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orybfzdp.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsimjoyb.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orqksdqu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gt2ggnmaetp.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gt2bxgcbhzc.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gt2naeqpjgi.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2ceagotvd.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gt2vfhoelyc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2wcpdfnbs.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2hcymvarm.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2nvbhymtk.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gt2rnzexqne.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2bdntbwjk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2idshhqzg.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2katxxkli.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zbzohrof.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2sofkbofs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2eoopqkef.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gt2ahmlaggh.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2tvyehvpc.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gt2yswkvzsi.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2lfdprwdf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2dbufahls.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2qasibxpk.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2jpudbyvl.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2zzbcuuio.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2zeedeuuz.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2sxfccdow.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gt2skqbibwi.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gt2gytcavyg.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2zvqyriql.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfhnbepe.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2lqqaasgf.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2dipeejgv.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2kxcjvdlg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gt2erecyxvq.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2eueovmqk.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gt2ozzaewvn.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gt2efxsdvct.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2yuhzeqsz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gt2znzggkfz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2ymrufyoh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gt2hdnetfeh.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2aozdmvff.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlrwacli.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xplgrdfo.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gt2kbfyytkr.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrqqaweu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2kjeuoiuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2uauypobz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gt2dsmwaiwf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2jxwmupwa.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gt2tyedzvut.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2eaicxgdz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2miudwspr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2zevvqgws.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2htibfbca.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2neiwvqpb.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gt2gtxwgqcg.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2kjjyexth.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2qsrdgufc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2jmzttxef.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2slklkraf.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gt2kzhfiszy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2qdndytok.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ucdeblpw.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gt2hbyrqddj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2yqigsjoz.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gt2osipfrfy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2gbquwiej.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gt2rjiotuxl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2kbetybqi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2erlciqja.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2lqystceg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gt2vyehiyki.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2cmjberct.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gt2cpledrzl.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2aculaykz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2efwpevrs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2wtdqlblr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2hittdhmj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2csifhtic.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2plxomceh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gt2oszoedqb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gt2akdnebkp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzbsyobp.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2uceuokuf.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2gfcpgwdp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2iljancxo.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2blqrqnld.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2qwttryft.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unsytxhr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gt2ffoozqlc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gt2dffecots.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2phbzpftl.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gt2jcuebzdr.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2fdecirho.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2qduyebfd.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2auzelrkt.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2magguwbe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2tybhuzgj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gt2vtzbnxvy.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gt2yhytedrf.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gt2qhzgwxal.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2cqsdradw.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2izjhstdk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gt2mijkamvw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2moweiebt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ecgumkzx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2xtpndthr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2bubwsyqo.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gt2luhqglrs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2rjkwxnbu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2wovwrehx.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2zqoxnlua.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2xonqskrr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2ajttwlrs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wauixvax.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiyautrr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gt2sepfhajo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2luymmlba.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2fsbkjuzz.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2ndjvhpjy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gt2ojcvdwdo.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuhmwlcv.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2jbjiqhsr.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cafmyhdg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2uzknylky.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uegdzcja.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2hsbgkqyg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2jnxfmzmh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gt2whvmpuld.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2slnliror.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gt2eqzrgzle.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2cjqhqtah.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofbibnix.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gt2updmteam.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gt2dgrrsxve.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gt2emieahct.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2dsauuqzy.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gt2lovlhtab.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2ymuqhxdj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2rcapimcb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gt2takzfuan.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2dgluyvet.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eefzsazb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gt2jqtkdrwg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gt2asrgvwne.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gt2jjttbvru.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gt2oygkhbmg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gt2lhuaahuo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2alkvojqc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gakniqti.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2kvbxrqaj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkwiwjau.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2zorkhxbz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gt2aygugvve.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2lidssegr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcrbnppi.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2cadehrsn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2spnfdtwk.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gt2uwylzcqx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2nskzaxaq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2czbkjggc.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gt2twtwbxag.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gt2lzupanxz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2rrrerymp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2qtayoijh.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2rzowmpdl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2kdlyijpb.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gt2rdgwidly.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2sgtgzcip.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gt2qxxvowln.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwmojyxp.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuxvycml.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2xdhicccy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2jdppiuwc.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2raghvica.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2rwbutsvz.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2byjevxkz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gt2wtotmnau.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2qnpixwnq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2hcnhbpmr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gt2xddnyelw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2jlcaplsn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2cpqskqun.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvdnpdlj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gt2mpbudzhb.html

[I04] 正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjurxwjv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2bthkbqpe.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2jkxffuwt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2namsxyey.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2qycrpoug.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2othlghoh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2hevxdgma.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2ukgvsuut.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tanke756.top/Article/details/gt2ddbdjujs.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gt2rdoguwsl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2mciktnae.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2szagshps.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2yxiwaabx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2amsgzmua.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gt2rhjqjpvg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2kvueccsj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2vqduwwem.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxiipano.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2tbodvnuu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2tvpkjblm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcglvqhx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2zvvbcdva.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gt2thrayrdh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2ezsjfgap.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gt2jjpkfznu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gt2shagqfbw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2xlxoukea.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdxjsbqc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gt2kfphyzju.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2fgfmvtym.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gt2qlpjchej.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gt2umfwihbv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2xruiqluu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2ukbgamss.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gt2adcmjqlg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2jbeldyvu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2zxynjbsi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zycfv.cn/Article/details/gt2okeobgtn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2cikgnsni.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gt2mfzsinzh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2bcnrmhmn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpvonabx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gt2zidlgwuz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2noeellmr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2xkqyondo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hitqkutd.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gt2hdnnjrxs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bdtaevfj.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gt2zqtxmtsf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tccawlfx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gt2ltytoxyn.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2emzcpucn.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2cgsqorxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2iqehorje.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gt2jszlfbfk.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2qqojffes.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2kqzifnco.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2pvygtogn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygspalxv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2joxplbkb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwsmfget.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gt2igxkciqv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gt2dfroehum.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqnguubb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gt2zmrjxzmn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gt2fhhaysgc.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2mnqlijga.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2aqtafavp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gt2tmgposvm.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2taohzwdp.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2bhfzzbnm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2uhrkbmua.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2bhzursmg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2nnypmvmv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2bebonhfz.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gt2fijlvckw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxgrwuvt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2pajlobeh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2mdpiyhvr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2chtcicvi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2ijiyxftq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2mpaqeocp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2pvstvrus.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2tbwtesjf.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gt2azrduhyn.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gt2eiianihr.html


<!-- 参考信息 -->