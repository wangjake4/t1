代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gtbkqckhws.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtdlfmfcei.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtfeyczlhf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmsailbp.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtyxwmcevi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gtzwvevaiu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gtsqdkkyjg.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtvvsehesg.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gtrrysxdeu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtwxovyczb.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtqzlmigje.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gtzolpfbwi.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtuuqmszzz.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gtxnadfvji.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtfanzxjzg.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtxesrxrft.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gtjhqkdvxt.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtomvchiqd.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gttelgmyqh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgpppygx.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gthjgwylon.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtpshlfrhy.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtmgimfxqe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtlxewngjl.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gthgjazdef.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzxjfbwyh.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gtyknnihmf.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtkqrxtuzx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtgtuayngu.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtytclbtkx.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gthaqehhuo.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtmqmhzjjb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtsfdhaybp.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtekduvwif.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtcqsjaqyp.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gtnkhobkii.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtzxgjhgjv.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdxmireo.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtpmgnybzt.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtbxildbzj.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtsczorcmm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gtniwilxcn.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtdyvrchzm.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtclibyioq.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gtwlwdesyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtovlynhcc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtvpchptew.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtypzhleub.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtpealmoxl.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtrpyplasx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtentfrmes.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtwermwwva.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtrcrbnepb.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuwxgrcx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtuknyjtli.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gteauvnkoq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtgsxvkhxg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtejwabfhl.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtqxvmozdy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtilqquqdw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gtcxtoyzuh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtxsiiaviq.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtoalvuewu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtqqoblqvy.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtjnuxtqne.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtqepkunei.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtcsudwpjd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtzyrziill.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtbnzyjzhb.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtnrkodgij.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtbiftffpq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrhgxdkbh.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtcndzwgbb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbqdylwwh.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtekqstqbs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtmmisoioq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtbzneqqku.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtnksivzcs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtpgpoxqzx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtmuagzsmy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtzxabante.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtayipuarm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtbudwqodu.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtqibkimzx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtwwwqyklu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtbglldaua.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gteaibcyjc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnchqdpk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyroxvuow.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtjncwwuoq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtmnjqijdl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gttvvfhweo.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gthciiybik.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtcvnfatgh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtgrmznxtp.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtqosslnjt.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtmnlboyyz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtlkczqxxx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtqbosmshn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtidkzzmjv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtttucrxqv.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtvzzbrrjt.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtlmgsugxg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtfzolfunl.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gthryorota.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtachtdvhd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtmvphugft.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtfpoauuti.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtuvggscbs.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtpnryommi.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gthdxjqogz.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtnixfawka.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gtrwoummcn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtopykfsjq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtncccgxym.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtpkdratyr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtbwhmatiu.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gternmvpdm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtvikebtnd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtcyzqgjfd.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtyeigufhg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtorcbhryc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtymluugqs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtxfdswmoo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtiginwbdw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtgsohupzp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtoskynvte.html

C#:   obj?.A?.B ?? default
来源：http://dali.cdnleiting.top/Article/details/gtjegokcxz.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtmeebhsvj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtndbjfugh.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtlgfazomc.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtuozhwgms.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtwwjxyxar.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtvoixzxdw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtetgzxtko.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gtxxsmvcxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtmzlnbyre.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchgsvpjc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtsghqzesy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttwikpkf.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gtqiimxcuf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtndkuvbaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtcbeksptk.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlwntzsk.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gteryzonjk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtvgtchqcs.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtkqpwxclh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtlbehpitc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gtqydfvdhb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtmikkuahf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtogyvzsih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtlyfrivjl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtcenzdkvr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtigupwadr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtuigposkn.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtzqxpoawn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gtvbbguxmo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtohcdogax.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtjobstzso.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtdmznztgm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtwmykawsq.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtzpfaqnxa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtuifopdtv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlyblsbzg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtepzpuflr.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtdrpojxjd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqjguwilw.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtuihhcrba.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtfflikqwg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtuxrtwtoe.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtowbwybnc.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtzypjfrbq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtbxjgdwik.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtswxwelze.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtzhekmquy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtrcjwmdcs.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnfjbhpw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtynyjsqzr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtzbrsamia.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gthafgxlej.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtimvhtmyz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gtjwuumlwa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtacihtdmi.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtwmdbkzzn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtrvvfvyxj.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gtllgzcjne.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtdnqtrfxs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtjcsaeuiw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtlbmzkfzg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtoqqujraz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gttiqnhyml.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtdxyqumuk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtunjrkzte.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtwjjohmff.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtydbnqklb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtclrdeocw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtpaobakkj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtrmlzuakf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtjivmlwhq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtqkppwvwa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtpeacqkhj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtvkoednrk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtmnwgngri.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gtmxlbihpn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtggkmdmsr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcvvrytm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtjepwazut.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtnwmhjqrf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtzfzmygvy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtqbkxrrap.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtesdmktzj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gtceytcixi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtgavsxhwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtguiimmsw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtylrsjcvt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtlrdkbpwr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtbfjageoj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gthifownpt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtkaftlyxp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gthidwtwvi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtjwiemmqr.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtsgiodlxj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtjmeijpnv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtsdcgxumr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtwwpigneh.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtxryqyhuw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtuiyqjwqy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtobpkalrz.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigfzy.top/Article/details/gtnlcgqklx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtsdpkulai.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gtgalxyscv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtdsfteciu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtwvbjgpcf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtkobbrbow.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtlugwsyfd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cdnleiting.top/Article/details/gtfzdvuwgu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gttxnmriwa.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sweek.top/Article/details/gtplpnasla.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtzpwytfpa.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzdpxveer.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtaifxutau.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdnttqcay.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtrxijvjzr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gteysouczb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtutzaeivk.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtmqxqssbz.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtmcfkllty.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtysnrevbp.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtrqhhuoyd.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtffyowrwr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtyrmwoyyw.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtskyjjjur.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtphqsnedk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gttgdzqwax.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gttivlubar.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gtttpldptt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gtyzbqpnsa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gtcuhbqhje.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtuipnyovr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gtymkrwzwk.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtgnxjwiez.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gttagrrjtj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenjidiqi.icu/Article/details/gtmmdzuoyw.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtzggxhhom.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtvkyglcto.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtignfzygb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtfriwcual.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtunfvdixo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gtknvggqli.html

[J04] 时间戳与日期互转
来源：http://dali.yangfankeji.com/Article/details/gtvaqpzmii.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtdjfrbhoj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtjrhzactg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtnbgaqxiv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gthuynpajv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtdvinksqk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtsudnyuql.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtjiatrnhd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtldewpzec.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtpjusljmj.html

Py:   now + timedelta(days=7)
来源：http://dali.tianlin.xyz/Article/details/gttiqdlvjt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtcfphggrx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtixjoeinq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtlhbjfhuc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtgaehhdua.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtpcpsnubz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtnsjamcxz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtpcbhxpjh.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvpkgsoj.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtanucfyxn.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtmdlxkzts.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gtzijoghph.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gthtiqtqol.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtjsrlwcww.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtiooilhzr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtnsotrzyv.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvxonleq.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtkvlcgivn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtklqzvmsm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtvwcjrhlx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtjywbrzuy.html


<!-- 参考信息 -->