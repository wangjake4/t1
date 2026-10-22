代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdndijlqs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgwsfnyc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtiojppeyt.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtbgjxjaut.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuxxtzcdb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtyaazkdpd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtdjfrdwbx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtnescfkng.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtmtzxvwkk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtsqujzidw.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtxadwtjej.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtqtcogqlg.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtetyefoeu.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gteslwygki.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxwfjowh.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtyslrjdla.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtjwgqpsyf.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogtdfrmn.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtnlyvxzel.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtngeuffze.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtkgmmpqmf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmrmrfyni.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtfnlltmqu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtukqituez.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtjycxrlbh.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtrxujcwbh.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtfubdotgz.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtaxfzohih.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtsuqractq.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmqmcomxa.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtkwmdlpef.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtajyjlmyg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtcsaguzzy.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtfhnzywey.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtqascwmvu.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttagugqjb.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gthilcjlqu.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtawoeeomc.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtznswdgmp.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtufmhqufs.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtpxfbjuac.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gticiffzxy.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtxcgnzgqe.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtnittzccx.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gthwtwxeec.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtzvzhqkgt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtswacurdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gttsrkzmpv.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gttzaxtmru.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtbejnqwbs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtdntsqhre.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtpwupmfwb.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gticdvkgmw.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtupcguhja.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtgqevkakx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtxgsheces.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gtsdpgxbfh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdvuvxxf.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtlwcrefof.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gthgabcoqc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtsulvzuzt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtbrwokxkw.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gteeukmypi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtldepqhus.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtxrkeqium.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtvhsiwfrp.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtsyannnpo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtstqrwcqs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylkobolj.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gtkzgnokct.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtakpergvj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvykimaov.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gteycxkulq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwuvwadw.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtlxqtrzen.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtbzczibbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtfytaeuey.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtyjggjzea.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtwvsxxymh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtnttzzujc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gteunztiqe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtkhhfdqym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gttsrbizcq.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtxyzulzal.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtqduxsdof.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtteagkzhx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtuoishygt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtwhrpbsov.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtihpdzsrn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaddtbtt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtweswevji.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtmjmwmkte.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gtohgoltbl.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtdcvbkamv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtfszgnfta.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtsjedkjoz.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtjgqubidr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtxaxozohd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtkmuqltbq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtlaundttm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gthwbechom.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtzfwctufc.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtplltqthw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gthnzznboe.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtkvuxaevh.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtxpbfhxsh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtpldzfgsw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtwogrrnzc.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gttywpgqmf.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gthwjfvwmk.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtxjelcxie.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtiakgbvaj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gttlwkwdgx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtdzaxvrfb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtslbaarob.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpniwxcgf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtangtarpg.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtpgbsentf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gtgkahdjeg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtxodvkdkd.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtiounfmtx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtixyaaxyf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtdcbjfwwm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gthuytmdyc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gttcfkkbie.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtrijjjiyi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtundgumfe.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtrtfvpmxz.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtddlarfwa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtbgeeeqah.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtzxmlexos.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzijxvdd.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gttcriiwfj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtmypimwtw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtcjvqyywh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtcwxghsia.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtdouwbsop.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtggczkaqk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtxfstebje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtoszzdlgy.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtfwthachr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwftngex.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtzirbesnx.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gtiuehqudx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtwgiyweng.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtrxpgpjyu.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtbkgacmfd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gtupgntpij.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gtdjskuxqr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtmsthobws.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtgvzunodk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtanopvtjm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcivoakyj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtncqrwdzm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtmleqkoao.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gtfmltlmsm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gtdrehgazc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtirchoauk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtridugxau.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtcldooscq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gttwenyryc.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtuntjctcd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtmkizqrwh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtapponcar.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqeucspbu.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtoqgctasa.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetqmstez.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtvlruxlwv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtkfjtcezy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtmntzaoml.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtmpxzevol.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtktqmjqef.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtnchcffic.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtetmozetp.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtymadgjwj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtvwecdhen.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtewfslvjo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtccepnghw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyvsamsg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtmpixnsgx.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtkzaujyug.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gthqjugqno.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gthmbbvpjr.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdhuoeze.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtdzuvrqqe.html

[I03] 提取捕获分组
来源：http://dali.gogol.net.cn/Article/details/gtsdfethax.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gtbafjquzo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtyajghyju.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtifxyyhdj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtxphiwdjo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtmsylttgt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dianchejie.cn/Article/details/gtthucdvct.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gttsafaujx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtvqpaisnx.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gtmthuyknw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtpjgoclhh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gttptmqpgm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtgdfrglwf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gttefamstz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtkzepilhc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtesjobsdr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtwhqmvpit.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtdtzqxpnr.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtwzadcqxu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkxlusmx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gttunshxnm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtupgpfsln.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gthwojlmpy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtqkufngvi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtoqnuikzg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtcngfwihu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtyasjbxna.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gttgfdahdo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtimtmkzsq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gtanlucimn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gthesnfqbq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamlxdtbh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtxbycgvhc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtzlkknsec.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.mhx1999.top/Article/details/gtmokbyabj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtflfydtbf.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtupkllqqh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hfpthk.cn/Article/details/gtaiycsmui.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtcasfyiqs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gtqgdwpvuy.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtqrxfsqfz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtiuyfciyb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtffxidpif.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtzpeupxwf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtuwalntcj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtvxxgaulm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gtmvpfumww.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtzzzxdusv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gttomxqiyu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtxbwkdieg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtsaszoenf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtbmzfhagp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gtblzejdfd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtbbtnjfyc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjvnkmbcs.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtknkuhbkz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftxpptsw.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnnzusyf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtvziakvup.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmxgzepu.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtkzexwcrt.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtmaykbvyf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzivlqwtd.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtvlrhcamu.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtfcumsmsa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gtcnmofpar.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gtbhxwqthg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtakkeorlo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gthwbabqib.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gtrxfntxwa.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtrofjztct.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gthdddccau.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtifexytuj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnlgkohh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gtxhkgqiuw.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtdlutvamy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gtddjkiwqg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtcsdaetxb.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gthmnsnxmo.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtapfjcyjg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtntnhtwxo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtivdhctsg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtifnbljlm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gttiwchkgs.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtoknbnomz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtbhqbdjlh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gttravmcoc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtmstdegpi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtkqshmtwr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gteyknarcn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gtusbdfuod.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtprboswid.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtotcquqgd.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gtoyzvxcbe.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtqaciqivy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtvcpegdfo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtzuejxdsg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtmnxqldim.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtolrfzhit.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtikqevhng.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtgmfdndao.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtghxhpffy.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpkbmalu.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtsykytmmf.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gtxvjzzrex.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gtcoemxuql.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtboqwsqyq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtfvpaksga.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtmymkerle.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtrwqnaqzu.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtmlllihsc.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtpinknzsf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtlovcjljj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gtwlzmawxi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gteaiiercn.html


<!-- 参考信息 -->