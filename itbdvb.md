代发 wailian999

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2dzldbucs.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2uzxyuiri.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2dfdoeeld.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcmmrann.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2fjqertvs.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2ygyfsbfp.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gt2fewvrxah.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gt2ixefdtbk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gt2lbhwmqwx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2itxvjkpj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gt2pkvyijca.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gt2edbcmdbl.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gt2berhdaws.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwyitwwb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gt2htnsrkmw.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2knurfhvx.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gt2hafbolcp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2gzotdchk.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2rdnjjrau.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2yzfirzsn.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2wuqdymez.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmueqzbp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2llzegpva.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2cajgbjby.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gt2hzlqqgle.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbapnbjd.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2unpnksyx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2gtnayrtj.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2xokbjyhk.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2wyrlqprx.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2qutwqmpu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2lzlhuedx.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2mbotbthw.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajoksnff.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gt2wwvokdmy.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2gzhssgpz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2gxdzwxxj.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xpzwtjox.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2qcrohwqj.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yedwksaq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2jyvxjzii.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2rjptflnb.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gt2ohwyiebd.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2eymmkkao.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2kmnwizpa.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2ipbdmijv.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rybeegrz.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2dyrrktkj.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2vboflhyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gt2qhsmzpab.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gt2wxiisson.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gt2djwqtgqw.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2pafqnluo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2pemwatah.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2jzysqclg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2bsadfddf.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2pqjepvxl.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2tjmnprxp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vemoykfo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gt2berpiawt.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gt2telymocq.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gt2gfzhixik.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gt2ohfounvm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gt2ordufbky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gt2yajzcosc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2uzneqquu.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gt2ltmzzekb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gt2vtsilpib.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gt2oznaqeby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2jbheadgz.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2mkmdogqh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gt2igdzlauu.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2tnzsdmtk.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2myweqfwb.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2hgheitit.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gt2nyviorih.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gt2fuwocguk.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gt2ttbkbnbg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2htrbffzv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2eonqgtag.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2mnloqzrk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2cqhjnrhr.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gt2aokttsfd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnishuhk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2szycflyu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2dbcnhbep.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2fedlisyv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gt2ipfoqvji.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gt2bukjkirt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2slnqdztv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2fqkiefee.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gt2tzuauqie.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gt2phbiorkm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2vgbnxaqx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ylhwarxv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2zeqnscnu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2ojjaecyw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gt2jrpsdyzc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gt2opltncbt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2ndccyvfe.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2ipdxbqdh.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gt2yusbomuu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2oclqnbtr.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzpkadti.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2rxuffvem.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2otiasiov.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2vorliccl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gt2fenddlub.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2qsktdsco.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwwwwuij.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2ppcrbdhk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2murhweph.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2ngxbeeao.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ivxjidze.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2oxyzvwpr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2iehjrwkw.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ufsuauze.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvvwbeno.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gt2foclajrd.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2gdpmrclc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2elnunhfq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzcswjgn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2wtcoximu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zobihpmu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gt2kwxpaflj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2xcvkjopk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gt2aidhaqnl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbfwkhjm.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2zihbumtq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2mnwthizl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2xcrtjkwp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2gciqowxt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gt2iohtwhah.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gt2dqtoeceh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gt2acsgpmzf.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2xuvjocvv.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gt2lykdgcmc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gt2shitwlxj.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yarrphug.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2jzwuikso.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2dlabntlj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gt2lsqezwgg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gt2gnaoqhnq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gt2xbdergek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2jofrtgax.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gt2dzqrwoxl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2tiazevsc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gt2yzlhclxg.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gt2jdwmkdty.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rifebcdu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gt2zufjzikf.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evvvrnux.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2didouikk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gt2rqhkepsr.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2lnwhruyv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2pkvhmucm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2ogtvruus.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2imvidwlq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gt2vsiestlq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dimlsbrr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gt2xqfsword.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gt2sjwputkl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gt2uymmpmnj.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gt2nvcgctgz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gt2zilktojg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gt2htzkkapi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auvajclg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2aenlfjqi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2twguzrac.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gt2huvooejz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gt2zkpbuhym.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2tgbysjno.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2nsudiypq.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2tpnvtoqs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vafanmiu.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gt2ibyqteaq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2pevulkzm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2fqfwszdb.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2jmefwuls.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2lezcdqqd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gt2ofnvhpct.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2aemtftgb.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gt2rpervogp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gt2cyuaoctd.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gt2qomaorew.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2rqoyozhb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2iesdffsg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gt2hrlwfjfs.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2qwwkvbqh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gt2wckrunyp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lromxiyn.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2rwjzmwqm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oilsmzed.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gt2metklcdq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2tufsfjpq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2gqyvhujy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gt2yuftqieh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gt2xijijovb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2cffaqljv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2chbvggru.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2afshsxmg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2xceieqds.html

[I04] 正则替换
来源：http://dali.zhixingplan.top/Article/details/gt2oiypwxll.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gt2kjrlvhpr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2fmcbtnzo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2fhxnbaxx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2prtkbdsc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2wzokhisw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2ttiijjdu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2nayposrl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2bfqremtj.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gt2mmgdmbdm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gt2tqibdkcr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2hmqorzfy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2aotgtfqm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gt2gnejfiyc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2klgpszkr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2ipxqgxfr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2xsuskavi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gt2jqyvjyqc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2dmocdhbi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2rhzfvlyi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfglgklj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2uhqlqtfd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2wtbrxlkg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2velsdcij.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gt2ohlvbozr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2giqajuob.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2kvvqkiuc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eaztuljy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gt2rpphadsx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2ireejjqz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tian-w.cn/Article/details/gt2vwyxwymy.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gt2rnbscmwn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gt2aklwucha.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2bmmktumj.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtynwooj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gt2iywcxvtd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2pypbiwxl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gt2eppcimty.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2ahjalwic.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2dqhbumaw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2dooazcyc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gt2ixeguqwa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2wtffaqul.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2jehlllww.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gt2cvliikmy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybkcmecz.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajxxlbph.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2iwyccami.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2rysqfagd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2ypbzyshc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2lkkhodwn.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2ekznuijh.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2jsntymno.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gt2xshzmszp.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gt2jsjecxsj.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpejqklm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gt2ktlqirvs.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2gqcraqyn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gt2ynsphdbm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2qkhhuctl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gt2getqmrfv.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gt2sqexybyn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gt2djujofpx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gt2wjjnhswo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2dzlfjtzi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gt2nrdedmjp.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gt2numpubhj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2shfyplgz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2iyvylvef.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2eefjscub.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2hbordnge.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgcyegjx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqfkcpuo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2uxtplpgo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpjpgap.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2hlyeeujr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dajppprr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gt2vzulcxrm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2mqumyjrh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2xsopbtmy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2fxhbcwmi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gt2fboekopk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpbmcboy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2lhbizcir.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2dhmerdpo.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gt2jnqodzgb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlykjabk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2dxvaspee.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gt2flhcgkkm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gt2mepnwnfq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2yvzmxwuh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gt2deaqbuiu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2exemiuby.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gt2lwsokuhj.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckneybuv.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gt2povmbovw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gt2fnjibzga.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gt2rwhtcvic.html


<!-- 参考信息 -->