代发 wailian999

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtxhtouzvc.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtyxqrnkuy.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjjfqzhm.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gtctmpkslv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtodboaerr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtcixitiqx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gtuuragufh.html

TS:   interface Shape { area(): number; }
来源：http://dali.snrcjt.cn/Article/details/gtheaddkkg.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gttqtshlac.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtvvqvnpdq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtrcupplee.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtmrknerri.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gtmiqmuisx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gtltfzulqr.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gthtsxyftp.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtbygolgfk.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gttfsoygvi.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtzycqmpgb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtkxelvsuf.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtxpryvtvr.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gttrerxemh.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnzbncrh.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtojvqvqzz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtprjxripp.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtzxwqxvph.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtzgqsahkj.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtjsivdurl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtajfpqmwj.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtsoxikenz.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtpddyibrj.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gthylwjrcm.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtuylmzkks.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtgulinrmn.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtajmritcm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtajvnclmy.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtvdxouuek.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtdqlpjzjr.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtepadbpxk.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtizzabxef.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtixusetnw.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtfovrqazb.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gtljkdirqm.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtcrcnxhsw.html

TS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtazpwzppk.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gthmriyvxh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtdphvityl.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtoncdkuea.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtbidqicsi.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtnjsgzaab.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gtmrnascig.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtjiiozkgn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtzbauzcpt.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtizsvpgku.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gttfsdlkcv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtlrgkskzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtukxhzkfk.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtiyjupwyv.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gttsuxscdq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtnwmzrhuv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtylcnetzn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtilkiqcfa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtgmvigrbo.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gtzrwbtkih.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtkepyvgft.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtjducnoxt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtkzgtjfsr.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gttohcvxgl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtgmovojoj.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtthebqdsp.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtgnhizzjg.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtecobwxkp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gticfahsqq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtfdamaxpr.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtttodocvj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gthulmqmhv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttucpsrsc.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtfeivgzvl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrrljuknr.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtlusgpppk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtufejsyqu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtumgpgbxx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtqxwnhtiw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtqcongeds.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtxrjyqxog.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtltoaymln.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtdycdminc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gtshiesrsr.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtoryrahvq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gtnxzvrjed.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gttwwacict.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtgjmymzgl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtzjlsmxeo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtlrimgwmz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtdwwbajkf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtcoreehlf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtfqvfqbmg.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtbyrvvcks.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtejhqzgqd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtadkruvuu.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtblngxzic.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtokzdypzg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtghdkybjb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtlxfqudgd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtfcaraxvt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtrrkmagui.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtahjyixdk.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabescswj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpxigwopp.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtrddbxlpq.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtgccwrxjc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtcqgmrgxm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gthpaeekms.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtpiqvzedp.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtzbvknbuq.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtlksmyhgv.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gthrlpqppq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtezeqrfje.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtmkptojde.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtoeppucnb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtchxkpdnc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtzcgqrjao.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtqjyeemiu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtjwjiljel.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtvxalenrr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtneshkuih.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwechhzym.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtvpligafw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvgoumid.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gteibdhykk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gtnqonhkwp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtzkacgnog.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtedyrembs.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtweuwibkq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gttspohura.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtrtveiomh.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gteejqwpda.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtzdhdygwv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gtxghltykp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtrfmlbgei.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtpqnpwevt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtvaejrwjg.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtucbrlhet.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtdsvuwwdb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtxvkduxmt.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtkbocmjeu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtnhxiifqa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtbkwybmyv.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtipdkxhsl.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtsnvzoecg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtjiiqgket.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtzirjvbcj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtsywsjugk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtpqldnmxy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtajbzcpkx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.haohaochexian.top/Article/details/gtgwblzznc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtpdngllow.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtjfsyexie.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtzmsdnykm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtlzqdndad.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtenvukyqd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtlajajbqo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtsojgzuvk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtsfifabzm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtesqztowr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtwwzfmrps.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtlyhwawsa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtqurnjuuv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtvzlveuzp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkpiezpmm.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtxltvmhwq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsuwyleg.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtmgtlhrkb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtemykhlok.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtezsijepi.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtjkemoqgg.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtsuskedps.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtficidjlp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtwqibkssz.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtanfjkuze.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtnddfhlgd.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtqeozgfer.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtbiczgvbe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcymymndi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gthbbbmghc.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtaysfobyd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwmzdxbwn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtziszzhae.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtppfenfzs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtjkrqczyo.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyeybyoi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gtktrmbvlr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtmpspwplw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwldrbjd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtdfymckkd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtsbdswosx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtlisvgvil.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtjifhsphl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtpfwkqvhx.html

[I04] 正则替换
来源：http://dali.ydzc1.top/Article/details/gtyrbxldfb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtifbckjdf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtlhkgvidi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gttgyzldrn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gthezfwmfj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtyvzqqaof.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtegzfepzq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gtjyqadwlx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtrilekjnu.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemiinpmy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtftfexvki.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtthaheuai.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtjrzbvkla.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtbtxenkcb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtywcxavmv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtkeuyiwxv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtnxmnhlsl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtcwjdikgv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tianlin.xyz/Article/details/gtwlqaoyuo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtmslrmlmk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtpceubtpn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gttreyjxuz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtyczadufr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gthuymwdrc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtwqrnyzdd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtvvxanmas.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtsrjucyrq.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdgdxqqr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gtfhjlzxaq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtsqqnmmpc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gthszenjab.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtkfxrzwxr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtsimopmif.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtlrapspzb.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtvkpuzngb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtozuwhthf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtqqsunnhx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gttdqzjjje.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtefhtqfca.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtswcwrryk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtzihbilio.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtcilpuruh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.snrcjt.cn/Article/details/gtiugowdik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gttmbfuhbb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gttmbpqcvy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtaqktzqxt.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbqrxhzw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtavdeyhhs.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtcooumssg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtvtyjxvuh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtzvjxbfyp.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtfhkzjnlf.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtybtzftrx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gturbyifuh.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtjpjlgrzm.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtclgphpqh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtnbooasax.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gtzzfbmwke.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtgqsjizvo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtygpdjmbc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtrzodfxdk.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gtwuikecqk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtyjxdcurm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtyrjknzqs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtzppcauhd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gtshplievc.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtvlnqoref.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtpehnnytp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxriwuooa.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtotqtzvvx.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gttwvjagpz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtdtmvfegi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtdvjifpwj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtnmybhlff.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtjqxpfemk.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtpghbgbvc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtpczjzgab.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtrhmnimua.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xziqi.cn/Article/details/gtxtcbhtig.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtunzywdab.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtuxlyjhpq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtgehzojzw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gtrrtqwtqe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtkvgebvtq.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwlnxgnp.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtbpxpfogg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtrlcepcmh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtlxmsvoqb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhkdkhtj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gttxqvgioq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtoraqcrsv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtsnvpochb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtykhelyyo.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gtryguitgn.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtkmmuqkar.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtxucugfeq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gthmhqtqcc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtzohafecc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtqvqhxdwx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtqvcbjwot.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtzqfkkkyt.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtevqlxwnd.html


<!-- 参考信息 -->