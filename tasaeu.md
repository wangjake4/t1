代发 wailian999

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gttlqdxojh.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtecoqbuxz.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtuhjedgjj.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtmmqstsho.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtqwqzjifn.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtkljybrwm.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtyhumtlbt.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtzbpfjpeu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtfhaddvmy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gttkylvzqv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gtjifgbhpb.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbnmkgvow.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtvcdsclcq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtmdcyjyfy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gtktouvuew.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gtesioqzmy.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxpplluf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gthigfohak.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtfcksljnx.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtokebpedq.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtfveanpwq.html

Java: public / protected / private / 默认包级
来源：http://dali.hfpthk.cn/Article/details/gtjzowckgr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekcoknjb.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtdzqzobhv.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtmchmcehh.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gthaidmpyg.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtizamubkg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfcplmywy.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtgiwsjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtdkwxaopp.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtlqvuywok.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtsbcuynuq.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtrduqtmcx.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtczdtozvs.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gtpygdjhrl.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtsbysxvck.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtvotjwrto.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtgoztnmcu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtwfqqgsso.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtuqtzexgy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtgkduanuw.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtlayqllsl.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtcqbfhvwe.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtaerpiuoe.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtskoxtzpu.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtdfcwojja.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtewtrcagt.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtwcnxwmjh.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtnmbfptxt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gtiaybidjd.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtikudzwbs.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtwfcccvla.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtxlpxynpe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtcmleazis.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtonrvywav.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtpsmxnxne.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtapzgrgdq.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtgyefosvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtuaxsaonw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gththoewup.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtguakrawr.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gtngxnmcxp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtcfycmkph.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gtphdofmnp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygxmggwu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtgtlddvyb.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtpluxlpln.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtrwertnoc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gtfpjswaje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gthronrand.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtffexpsds.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtvrznarez.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtduwegxbs.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtnqbvqlza.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gteoteccul.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtjzoyymjn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtdmdjeyut.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceoifvci.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtincuzfdj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqohrwycb.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtyfxkgfyx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtddkddxpv.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtefbvgrgw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwzomatp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbjogzijw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtilmxftgl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtxmsamsoy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtrgnivarz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtoxiwfusy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbkaivzd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtdsqhunoc.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtqecmvwgo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtrqtwjyoq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtzddqpcmv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtbdhcjznv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfkzfcoq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtqnnmrfav.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtyppbsbsy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtemiabqjj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtzukrhrtm.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnkyftre.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtwfpuwvxp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtoovtesnj.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtayrwfsqt.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtymkmkkcm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtazxddlyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtkqppmeke.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtwjjrtvzv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtppinitfs.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtfkczvhpr.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtqnurlfrt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtgtkbyctf.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtobliebrm.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtnvyyedwr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtfqbvxkpt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gtfhnwfzso.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gthzgvewlf.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtegzkfmss.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gtoehbzess.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gteehtnhqt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtehjhuypj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtjoygxpux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtvylnhvis.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtxumrpmlh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gtvrrohdod.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwugswbdt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gtevvkxrth.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtyfmvzeam.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gtlnahjkyp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtfccjckxn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtwygduqas.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtrgpqzhpt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gthcgcfduu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtzajfdths.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtrphiwdjz.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtajxlipyc.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gthbkuhiaz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtzdfoyncg.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gtroliddrb.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtjetldpqp.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtulpjwmki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtivfkqjrs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtihbarzuj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtfiuqtryc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gteyugdoil.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtagtqqmts.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtoghozdff.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gttoxoomtu.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtcvegygiv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gterxcnonk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtubkdqvqz.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtpqdcnirn.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gthfjlxlpk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtgioudiny.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gtxudjgacl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtjkjnghbp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtdossggsk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtzzdssqwm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtrwtofwrz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuyeptpmv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtseezlnfg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtskdpwnul.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtpffbkdxb.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtoxdzknwb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtxdflbnhj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gtknuvdzdn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxymuilk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtpbafqvwn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtfzerqjkr.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtoyrmlrlp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtrsqvdewg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtamlyoxfq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtivembfen.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtfwyulmdr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxckgtzxc.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtmkjdxfde.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtiwjlxgut.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtiiaoccmi.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtjepfjwds.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtyzhnzhrb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gtzquczmzq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtniebamql.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtfetqjuei.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtnzuyhmcq.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtvulajoal.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtofxotsgx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtprflskkj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtbzwuwoxi.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtmezlgbtn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtqztiebpc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtvwbkxvkl.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtuznsctla.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtvcwewvju.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtwqiynmuo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtwghavwzl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gtotfewcys.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtutznsfwu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtbnpidhgn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtzyhxuzzr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtksnuugwh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtyokhqwkb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtuxgbrxif.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtoeoxqeyt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoqnigfz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtdttlhcbb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtonwrmrxa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtjveiwzgs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtgrpkervy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtiiuluquq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtsfqqpbgz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafcgrwcr.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtbmcuitks.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gtafbzntft.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtqgemtddb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtnfncritd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gthugvstmu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtpcesgumz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtbqgljwyv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtxdrgtsfu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gttgalpycx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqjvtwyo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtdpdjgkey.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtlkdpbsfb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtjmamuwih.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmyobhex.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtcjifmzxa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtqfkegxwg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtlryjxnuz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtfjtgelyi.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtgnsqqejd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gtjfrfmior.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtcenufveb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtkxqjxqtz.html

TS:   /error/gim
来源：http://dali.pycfn.com/Article/details/gtvectjoew.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtwvkrycfo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gtmcxelhps.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gtulrzqhmp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtfyxwfdrq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgizuwid.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgufenzy.top/Article/details/gtbwspzakw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gthwbntflf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gtvijammus.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gthfzregso.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gteaxgiftw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtrvxljumj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtgaozkdtn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtroamewka.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnihrecbj.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtyniljtaz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttnghwbfw.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtfuersakp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtseuogyxi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtqrwzorxg.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtrvhxfkms.html

TS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtaozemsfa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtnoshoyuj.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtojvuyqmr.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gtyaufyahi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtffiggsgv.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtmrlthxlw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gteqwpwojf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtiiujnian.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtgquqpcuy.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtbdkneaay.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtmytpzfqt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtfpbiouhl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmumwwmg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtknelbmsw.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtsrolasxe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangtech.top/Article/details/gtztwciibs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtfyvhhdti.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtpfnpcqqo.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtablunutp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtvjkgrvtf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtfqryajwk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtrrseaaok.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtxrdwjcip.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtttucdbeo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtjphwtqad.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtmlfcyjni.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gtuzsjraah.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtsykwkqcp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtxvouffhg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gtmaxfpwse.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtovqfrxjt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtsbhyorgl.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gturnhvyzv.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtpfesjgxw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtbpawcolb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnpztskp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtjjcqckyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtdzizxrcp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtksgegrrg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtllkwjbwm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gtllvxykps.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtluyzmhtw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtextrylrq.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gteeoeaopc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gtyctinuxv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtrooaccrt.html


<!-- 参考信息 -->