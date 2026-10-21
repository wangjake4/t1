代发 wailian999

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtrrlofasw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdxcuuwtj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtreudqjeu.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gtvlrtcyka.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gtmpmedsfi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtwdxleybs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gtafjrgdcd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtyrbvxpec.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtrcdfsknz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gttftxbvyn.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmunfcmb.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtfcvvwzai.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtzgqksrtc.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtctmyndrn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtdeodqfbi.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtisoomiww.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtrlqhqgml.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtrwmbrhgp.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtxlhhbpzp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtooppeqkx.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcykpubfv.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtevamkimj.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtaxinljqz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtvcbyqngl.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtuqdxbteo.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gtqcaghhvw.html

[G12] 对象转字符串
来源：http://dali.nanxinkj.top/Article/details/gtnjoeyjiu.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtfdrzikrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtrrdrnoqd.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtltdhytrc.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtymuokuzo.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtkgkebnno.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtbbjkolhd.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtdpdagttd.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtafhvrexw.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gtkqntttrt.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtykhqhzte.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtmylxnbiw.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtjcfsanvb.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtxkbhmapo.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtwolqlqwa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtbsfqzjdf.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gtucsaluax.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gteccccjqb.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtyxhmzpdj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtcktnbcjc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtdxsysxxw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtduftkrzi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtcicbaahr.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtkkrlezqe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtuihissah.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtqkziwill.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtjwfrszec.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gtpgflzmqb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtcpbgsidy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtwapyrulz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtsjmzikxp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtxaimvuxd.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtitpmdkuj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmoxgkcq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtnzebyulr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtlheuzemy.html

[G16] 对象转数组 / 字典
来源：http://dali.cashguo.top/Article/details/gtygktejja.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtsdxlgcua.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtqcdsqemk.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtaxwiglwl.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtipgwsctz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gthyxpxbnu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gterkjxqbd.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtqubhkylj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtqvgtamru.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtffzriglv.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtoqgzzcmu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtiniuhqxm.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gttuhupxfi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttedxbbs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtyqexvgaq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjfacoaz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gthpulrrew.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtfsgnsrmc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gtealgluxe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtcdcavyze.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtytsouwoz.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtkirazeim.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtntterqaa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtmmkvadjo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtwckkktrg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtijtmxdhw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtpjdgkiqr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gttfoxvrhs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtlwcttvvh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgyyghgey.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtjkzvmeac.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gtqcgcprwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtiyphkhaq.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtvlwyrzts.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtedbpjlyv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtbmrpgovx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtumpvxrnc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtmrppfjuv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtehgpftfh.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtbzlaetop.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gthjmqjriq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtodntkqbr.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtyqrdypzh.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gthsawxibc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtftmesais.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtqxqshjih.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtcaxqihbl.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gtmutyxfrv.html

[H05] 捕获特定类型
来源：http://dali.sweek.top/Article/details/gtlemzypnq.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxpegigg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtemxfjhfl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnnktxymo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtuqndyyye.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtrurscyfk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtlsihjjry.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtcizpheuq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvsqafmiy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtboshcabq.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gthadpfwdu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtbgcneiiv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtthqeqmwn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzkxvdrh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbnyaeeu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtfgfmofno.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtkkcvgddn.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtjscjanhm.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gthzmlsaag.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtmjldhhvn.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtmiifcsmt.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtqypykojb.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtdwsnglwc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwfjtgza.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtqbvqlqis.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtzrslyamr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtochlonom.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtszkdfykb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gttngfnjud.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtzbattxui.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtqccdntaj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtxzsiefvw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtrwvkcspq.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtfwilstck.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtvrysywqi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gthrzdlkjh.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtbqsssalt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtnponqsja.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtjbquyiak.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmlzbgeb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gtdeywneat.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamcjezfh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuogldgk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtaihssfom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtkvhcgsju.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtprturhui.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gtkgjogken.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtoykcrqdw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtwfwecrmw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtwqyoprdr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtvsqtpqrw.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gtlujwebmf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtbofdqmpi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtkjfzndav.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoohnfdzb.html

I. 正则表达式
来源：http://dali.cqqwz.cn/Article/details/gtadlrmczw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtndwzydye.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtaftarwes.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gteoguwmdi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gthusadepw.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtpmlggmhu.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqutuhwpu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtdxuhxeei.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtrdomyhtx.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtqlhactuh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtteddlgdk.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtjjfrlkxb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtfqyenkcl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtqusulnrw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtqphbxzbc.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gtaogioulv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtavsqikvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gteepxopyn.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtltygeajz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjdjyiqp.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtbmfdwsry.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtstfbnxdp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtabjhsuoq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gtmjlormry.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtdbsmdsfv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtvgrfwrhc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtstmqgaae.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkvepqwk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtfyhqpxoe.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtonoqvtkc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtxmnvvglf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmebdghyw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gteiijbuoq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtjfahfrra.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtwxfyhgvn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtdtxezxfe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sysykeji.top/Article/details/gtdslpxssw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gthxnstxjp.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtqqufdyce.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.svipenyu.cn/Article/details/gtazprijvj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtebtgogfk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpyylnaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtthpvggrn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtzjcznmts.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtignmmjcw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtljibqvhg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtsaivxhum.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gtphassyew.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtteqtunlg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtgcvfjbvb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtmfnkqclt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtvzuuqqls.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtxqpnhbxd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gtshcoaqna.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtqhjrwoxb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtjibqfmag.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtrfmpdfch.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gtclwkefho.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtzerdiazp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtzegiendr.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gteuqckdxk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gthdtrxsbe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtvejotrxh.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtvhzcsxxy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtkkmjbjft.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtigbnvpdi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtbwpwnnfz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtaezaxpbr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtsurqpbil.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtzbixlooj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gtvohnciyc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtlcfqduqd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtlbykbofq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtjvfnuzbu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtovjnlpso.html

J. 日期与时间
来源：http://dali.cqqwz.cn/Article/details/gtmferxsde.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpfymyunr.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtyrthboxq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yvedp.cn/Article/details/gtvlcaaahg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtyeffcbtg.html

JS:   new Date();  Date.now()
来源：http://dali.yueranfly.top/Article/details/gtmmoumfqr.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtiyohettl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtybrnwmfs.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtdfvaoztr.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtkjsujzwv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gthzslczyk.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtvebxksex.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtqkjhrmxr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyrmipeu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtetbrchaf.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtsfkblizl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtlgkqmdye.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtpflrcqjn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtefofckti.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtbggnyrit.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gthclilccl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgamtvguc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtxamfzwjb.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtqtfylciq.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtdylhhtcu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtcpmsoiyj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtfeqrvnkd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtuvsxyjhs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gthhijqsyj.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gtkthfxxou.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtxuxeujyo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtgdvdxzoc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcoycskt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtjbuwxpjk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtqlepamno.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnnkoyfc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtjevqhwkw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtbuspwhxu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzsajouy.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtcrmdrhii.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtimlcgpaw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtuzxmsuxz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqehvqvte.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaiabfds.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtgjexmnxo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gtodycsjta.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtbbikekud.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtbydlzpkh.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gtgmmcppic.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtydleywyl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtvfzvqvqf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtdvrcxaha.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtksmvixpk.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gtpsbvrmmb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtuqdkuoer.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtjonzxyoq.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gtoqkpoqgv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtgifumtaj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsesdmjvw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtahrdusct.html


<!-- 参考信息 -->