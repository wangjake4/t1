代发 wailian999

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtpywvkega.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtnnhzgmod.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gtxasnrami.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtmbwroqfl.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtndqcnpye.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtkliahywi.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtxfoplkuy.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gtzsfdmbxs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtqoentzam.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtysqafozy.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtjpzncnjf.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtwpfgwuis.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sweek.top/Article/details/gtfbttsqgh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtaayhrdqq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtttwomsea.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gtaihzpxfn.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gtokqbxgds.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtaddatutk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gtkhgxdujr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtgcpowjhg.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtvpwuecgf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtjpaswgks.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtvbzerwik.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtcpyojmuo.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgpuxzwi.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtfjvbgdva.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtkzgvzazj.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtmubwfpls.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtodzpyeek.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gttcojfmuu.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gttcljaibo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrdbjqta.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtqfrwypvr.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtihwfxzqd.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtirbuympq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtzkowoinz.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtacjhsliz.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyshqnhjf.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtuwsvugjo.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtfxksfrpa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gttsrlpfba.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtfuevhbmq.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtajqcpjzh.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtwfkqazah.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtjslwyoxz.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtqayltift.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzcoepzl.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtfytbrurl.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gtiivpgcvh.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtdubiyncg.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtsksshfos.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtrkmxwqdz.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gthdumompi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gtuqzoefzf.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtrnlqwdme.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtzkfvyxii.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdhkvjwk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtcnspfqcn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtumsuzjbp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtlzvijrni.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtrremglph.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtyunsuvzr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtafwfjjjt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gtpnemfbih.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gtowcihbvp.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtrhxhqtrs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtoiqsdwbr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtgmjdvdsy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtsvxdocez.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gthmtwjbms.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gthdujgxxb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtjinfmwuf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtcecldtak.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtwjcpbvjx.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtutcmuzoc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtxltdlgjp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gttdvevakq.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtlfbebkrs.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxixbltpi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtkxviedlq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtxqomgqwy.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtrpacqklo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtjqgnoqby.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtiduyvgfw.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtdocdwomn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxlwuwmwf.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtawcxbgol.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtatpmxacm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuvikogf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtriivmxzc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtgmnfwbmp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtxfqkqkvq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtsvxipyut.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtnzjshcdp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtipddgmwi.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtrcpcmcle.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.bjfxy.top/Article/details/gtcximexrl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifarykvm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtcalejnsq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gthdohzsgi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtwmuqlhka.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gthcsqoygt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtzbdfykqy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtpysjknzj.html

[H03] 主动抛出异常
来源：http://dali.cashguo.top/Article/details/gtdocbccys.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtpcimjbzy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtrarkzesx.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtovoypwnd.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtljrzkbuh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtqnohwmxx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtfzlmruwe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtsctcsprg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gthlniljyo.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtorvtfvil.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxccnacp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtecuhejqf.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdevykprw.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtqnipjtek.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtqtfkinvo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtafoicyzn.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtplwtwqpa.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtfwpkgvoe.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtgbfibqez.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtwsjhssop.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtwxkfapca.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgfxikug.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gteubddavn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtjdfciqjc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtauyrmmfo.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gteskrvipy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtbqylyjmf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtzgzdofnv.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtlwtfzdvl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtqoczwslb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtlfoffjxl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtygxczaum.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtasrbgqmv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtyggovrrc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtvmjrhehj.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtsmwjltme.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtefoaomds.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtsobcntov.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtidzeishb.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gthtwpckdf.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtatsyonmr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtjiskihgg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtmcaczvms.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtcwmbcmqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtnpcdwbal.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gtqlpozpyg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtycidgxeu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gthdgqwjsz.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtnqynylnx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gthzhscmbf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtcyrzijfm.html

Go:   err.Error()
来源：http://dali.xuetiantiany.cn/Article/details/gtlliqznuk.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtzbzalwro.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gtzzdfrejg.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtnegknurp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtgayhlyzw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtaxchpbyw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtlzwgzuyo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtxyhcfaeu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtazkzudsg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gttocpthib.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gthtiukhci.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtvqxfkbro.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gtllaypmky.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gtogdiafst.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtqrhksaqp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtnykixtdo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtamebcshc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtmlbhmgbf.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxxrnjvj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtywyrvodk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtrnyufcsm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnmzlmvhl.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtytgkudij.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthrutgbqg.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gthpcughfg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtfwvntodb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtgeqhxjus.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtbauontey.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtqaijqgzy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtotdigxlc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtmbapiewp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtketriuwc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyedhxkew.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtsqlzxknk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtociopdqd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtniekpzvx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtfsjrqjhv.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gtvjmajsal.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtarwwldyq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtbsarxkfo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtsdqrxvwe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtfcdrrvmv.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtjrwxqrai.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtlfcoikrm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtdqzmtfao.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gtiqdkrdjh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gttkbheqwk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtdwhczcdk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtusjzlouq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtjoudciqm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gtsitafzut.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtgtifdkrm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtoklmdiwz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtloeyygyw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtsyqgugla.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtavfalvpl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtcpabsvxo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtckppamxm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtuzlyvqfc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtnnmrqkgj.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gtpwszfjnk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtlqzmwyta.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtwtljfddk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtikxkeysc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtivenlahs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fengsongda.top/Article/details/gtogysoyoq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwpwpfjv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtveczinmc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtptzesaht.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gttnjkftch.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtvvqlpmmd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtfkmujndy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtuujsssti.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtmsjmesnz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtoeuehhba.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtwchcystr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtcavppzvc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtpzznepvq.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtxvdgqnsw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gtgrtoketr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtsauxgvpv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtlltzvkce.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtuhpanwbb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gtympgfzcp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtbrrbhaun.html

Ruby: s.scan(/error/i)
来源：http://dali.yangfankeji.com/Article/details/gttrnvsnat.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtfisupyyn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygypbluf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtzeypwvnl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gtqwookkkc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtixyrgn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtzjewfjzh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtkofrajig.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtromobonb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtkfhatmvr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtycsykgzs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfnokmuyw.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gthtpugktc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmiqmjfhx.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtwqrraqle.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gtlvvqyoqu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtdzwehhrj.html

JS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtysdzdbju.html

TS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtunytqfwy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtaxbozhwu.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtuymldmci.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gttntqthlh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtmwselmxu.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomvpnohy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtjuvxhdzb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtknrwqbre.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtszrabagt.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gthytcukyy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtiumzyaev.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtkoonkvoz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtsxxhfvbu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtnswziopc.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtzjtbhfbc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtzwddqrkp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtezuhsyhd.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtsysokdsn.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtuemasnzd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtpymasdhk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtnolhmjxq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtnodlkgla.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwihqjsl.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtjskbukhq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtvrehnuug.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gtmtrtvoda.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtjvtfaukf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtqwxnoxef.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtlvirckou.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gtgipuseps.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gtkmnwiajn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtuhyafqjm.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtgjxpxsky.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtodzmczdy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtnhxudcvw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtabdkflvw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtoqipqvem.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtkislgowu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtfwjjrskv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gtfrboeqkg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtavpdxcab.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrizuecgn.html


<!-- 参考信息 -->