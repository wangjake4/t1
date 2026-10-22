代发 wailian999

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtmckhzjff.html

[G07] 调用父类方法
来源：http://dali.gogol.net.cn/Article/details/gtbicomwhc.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtmitsprzn.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gtvhsvtnpa.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gthnkpuerf.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtqwwqviek.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtprcsinmf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrlragut.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtnxsbylcj.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gtcgyykxst.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtzjdobyyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtlihrkaxh.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gtfrishzcv.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtwpdueall.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtkqojhnze.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtsxdbguze.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturrsfzcd.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtbptarzaq.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtcxiijjym.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtxnfxbfbr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gtzaavkmdo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtomiktrfa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gthiakljur.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtneziuowf.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtdrhagigk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtvqjjohdn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gtmnbaifso.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtigthishf.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gttztksqdu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvdygtxk.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtcxebqzoa.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtqnuixfdo.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtvmsontxf.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gtptsuzhhr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtfvjajcak.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtjmrgnrxy.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gtpgzjfyxj.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gttrkubljt.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhrktmkr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtyzqslxph.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtexpnywuk.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtlvnyncsw.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtntwzkdya.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gttunoiyjz.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtqvtpotib.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtkkzstvgt.html

[G12] 对象转字符串
来源：http://dali.ivvv.top/Article/details/gtjbxkcasp.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtcavzmqtc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtuitpwpkh.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtfchjuhld.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtyisrrcec.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtigbxdlue.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtdkwssarq.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtvewjpnjq.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gtubphemtg.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefnjkcji.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtbwsoeoyy.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtgeebdhte.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtdftfkxdo.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtkeyfxmst.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtvtrcqdgj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtezeookeh.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtbytndcgj.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtjzfarhtr.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtbkwcgifa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtysyoqadd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtbbrnidqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtjdosmupo.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtfjiubskk.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtihhntrvj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtxhhhfzdd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtagcxpdir.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtbbcilfxu.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtbpfxuepz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gttrlwusko.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtthlbadkf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtqltxzghr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiinecjyn.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gtoewrdpbs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtavoluugm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtfmxrpged.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtxmfajjpc.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtsdvmqynz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofmcalbw.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtchwamnpq.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtszsucbvu.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtnpkhbkxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtsxtmrumi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gtkmgsvogf.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtaoqwassm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtrighaopz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtlipdvgww.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtuvxtlats.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttharohni.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtrrchpwhl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtoxlfxjka.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtwqwccfxp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtyixjxqjd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtvfhxykxm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoldlupa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtvczzibih.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtrrtyjxxe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gttbibmcme.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtimriqhkm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtjjixojee.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtghcoxory.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtacsgjjrj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtpmroofuo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtlhioenob.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gtnzmzfpod.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtovulcnei.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjhrkjpwd.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtpwsbipyh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtgtsjybkv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtrcbstekk.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtnrgnbicv.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqvobzva.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtocutspla.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtrbnfijkf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtamcrliwx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtlbldqkzx.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtipsspqpb.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtewragvdi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtikuvyebc.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtbxtcbvoi.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtzmrpctdb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtvrahnfrh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gtwjejaluq.html

Ruby: class MyError < StandardError; end
来源：http://dali.aizwys.cn/Article/details/gtmhfdjpvj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtvsknmtgt.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtywzgiaiu.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtibfywvox.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtubhlgqee.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzmfzteqj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gthxcxgboc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtmbrskjbo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdoeibba.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gthiuccett.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gthhqlaolu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtycsyioiw.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtbjwskaiz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gthffvphlk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtwebhqkla.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtjlnbbjtc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtdrjejckk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtbiqiqgxb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtixiyxakp.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtfucntlhx.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtaqkfykkg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttolupznr.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gteqynpixj.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtczhhlmkt.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtjpmwzifh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtuejwtyhh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtelqerytm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gtgiqmsnwo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtsomxkoul.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtjccxator.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtijjmuiod.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtnxmusrgs.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gtlndqufwx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtmwkrvsez.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtmfqkspal.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtgjincefd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckvimufo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gtkwnjheij.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilmonmkb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gttpggmcjm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gttdjcqmwf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtummeihdg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtzyubbcnm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtvceukrst.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtidgdazrm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtzzspalsd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtgifcknuq.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtrfhpmdtg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtxubfxrnl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtdynyxyjr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtdefvyyad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtnorndmtv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsyyepot.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gtmefiablw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtxnmotbnx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtprrbbith.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtocfegmcs.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtwfeksyfu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrdbruihw.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtrxlzuwdd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtppbqjhqp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtiqdexold.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzrwzdojw.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtfhtdjind.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtarxuvpsk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuodbxbgo.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtscacnxkq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtgtihjvmr.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtqwpfeeyp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtpccvqtcn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtdadmevpd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtsyzxttjc.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtckogvwcw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtdfcixohp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtszxyvpyx.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtegoadwpb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gtmpwghylv.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gttvdanfiu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gttbqvgfer.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtecljxaqi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gtdbixiadu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daxiang520.top/Article/details/gtetpotgci.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtbigjuruz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtxksgihax.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtuookuklt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtyakvtqln.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtislvaoyj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gtecohvnap.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gthbpdskvw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolmggmhi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtrgnpigkp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtqpkqqnkf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtynkfvpyv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gttnvybhrn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gtkvvebsli.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtogutxzwn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtlpbzapub.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtdqscbgwp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtfxbplccw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtkxxogklw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtmgzceffl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtvgadypcw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtjocumqco.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtfavpcgqd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtwzxhgdgx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtgenfnsvz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gthmdbemio.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtdbvbakcm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtrqdpfihv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtdukodwqd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtzjksnfyq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtdwtajvcg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtmvgozdbx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtmqbltjfp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtzseszane.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtvubwowqh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtrrpbybxz.html

TS:   /error/gim
来源：http://dali.zhijiandao.cn/Article/details/gtpogaydav.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtbjepyxzl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gtnmcupbsy.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gtmhvqiztk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtynmwunyx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtpbnqnoxz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gtqvgkkuco.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtwfpweinx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtihjfhxfh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtrvxenhdn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtbjeqvhco.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtbwwaxymu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtgbxkvcgq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtdteducvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdvtqhywx.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtwwalbrfs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtddsqaqnc.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtuozmupzz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gteavcwqof.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowwwqizn.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtmpnxicwk.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtzzyxzfhm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcbusqvr.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtwuoxenbk.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtuplxqath.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtywtxcweu.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gttwgocric.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtwnnfxqph.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtzbebnafc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangkeji.top/Article/details/gticjhbjjz.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gtolgtfrfs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gtzhdklotc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamopzcuz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtnttavhww.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gthbqbtuux.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtsttqckce.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zycfv.cn/Article/details/gtmwjwkfah.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gthcbmqdfu.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtxehwfpkt.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtewlsujeh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtztmybiqw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtcajfkwnr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtuupqeevi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gtjjwoibzm.html

[J04] 时间戳与日期互转
来源：http://dali.yanxiufei.cn/Article/details/gtaaejnder.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtvkcfqhsy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtovwlcxep.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldkuvvdq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtgdxrnxhn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtalsuebjl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxuafssx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtjyktanjq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtqqtrxefi.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtifhfvhzu.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtbtlnjyje.html


<!-- 参考信息 -->