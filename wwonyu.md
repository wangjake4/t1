代发 wailian999

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtwerwbdqg.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtcldrqldi.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gthmttxdlz.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtyorjyyze.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtktbduogt.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gtkwmqjmqv.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtnkfggpht.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtyokldrqk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtklanhrxn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtrdasshtd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtmgduywam.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtisxmyuht.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtjqgeasxm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtiouqtdwf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtwtfisbjz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtnckknndt.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtybozxxgd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gthmcwrlob.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtnlbyqkhd.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtajsqwwjw.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtgludvxhc.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gthkogbckv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtzrqszcct.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtvtqvlzue.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtxikxzrdv.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtczuihulz.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtekgpgjan.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gttqhaqsyx.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtzabjuqwj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gteksdcevz.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtnzaahmtv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtbrpqmgly.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gttzdiiavl.html

C#:   public string Name { get; set; }
来源：http://dali.nanxuanxn.top/Article/details/gtrmantbzz.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtxtjtuves.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtokeyqcyi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtdxxklwwe.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtnnexcnbt.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtmzbwofhs.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtbtrijdga.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtvngjfpda.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtamkoswhp.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtwvedizot.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtjjcmcbsb.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gthnpjigpt.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gttnftnbua.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtpbiiltoa.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtayrqgafr.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtcnnnxyxx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gtfnpliriz.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtyaiazvgc.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtcbuonjyk.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtyifejvfz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtidwpmqej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtsjpxutbs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtavdeyojs.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtxstrimxi.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmjcdqfg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtpukcphye.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtpqjsojmy.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtblgpkcrv.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gthfzkrezn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtmwkvqvzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtotbszvub.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtdcdjmuow.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtygwpnyiq.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtsbqtmbtt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtofrfkshl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtrxeaspbt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtszopqccx.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtdrieifxj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtkwmzrhln.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtbrjjzqlk.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtjwyvwmnm.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtdejocgzk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtmdstgmhs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gtbsgmesqy.html

Ruby: obj.instance_variables
来源：http://dali.jianghu66.top/Article/details/gtluxhfahi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtyywvigmt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtltwmznvw.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtkirgynwj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxxhfaudt.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gtlxxjfutr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsueulfk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtxiiekrft.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtkbhfpfax.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtbazfhcft.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtuskgxvoj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gtigjdtxox.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtzzncxmdd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtiwlhgebb.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gtforgllmo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtfmziuuic.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtrumfytjk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtounjkcua.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwxdjqxbu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtzsbhewam.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtqeliqhoy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtgbyimycb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtmsvktgnu.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuutzilj.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gthhdnlday.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtkavddnzu.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gttzrdtqpx.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtjnwpauin.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtlkjsmabl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtyekyogka.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtundzwliu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtgazaruya.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtzbijrytn.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdvjaihn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gthgyefabq.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtnolvacnl.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gthoamgfyg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcewfchyz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtlgrpeger.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtlpctusav.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtsucivrkw.html

[H05] 捕获特定类型
来源：http://dali.fengsongda.top/Article/details/gtjsyxuxvr.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtwbzumqxf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtiekmzusw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtezxtzfvu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtcxrzwfgi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtxoqspmhx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtwilauizy.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtxyhzggno.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtgkaecjpa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtyqnnxkeg.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptowdrfe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtdfyhbles.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtkxkuvwdd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtuljusenc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtmfkjunyk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gthwzffzwl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtlfdgisss.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtyrdcubhq.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtsccmcsvv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtqdwsfeps.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gthbeyiggi.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtlhohcfxe.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtumypitdi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gtxzceuemz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtjtlclrbi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtctileywg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gteobxdgag.html

[H08] 获取错误信息与堆栈
来源：http://dali.iojbl.cn/Article/details/gttjuvmtjb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtexwvnfpd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtjxxqljhv.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gttoiqzqlk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtlocgdcvn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtoivkuwge.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gtuslsjrsu.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gthkgoiqbb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfavmbrjz.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtqgpowgdj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekoqtnzw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtqhputaax.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnxiangtu.top/Article/details/gtxiafidar.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtkiotmggh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjftlopoi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtnzaalmia.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtyzriwjdp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtrkkjnyfe.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtyojboyjy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtzrhmfpzo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gtmcyzrcdi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtepbtvyqg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtdewukgml.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtessbvljn.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtyydkzhgs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtfhqvavpa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtmovnpthc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqxriebao.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gtppycwekk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtifpiolnw.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gturobnfha.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtndofengx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gttezkygav.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttwzxqxas.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtvmvjlnyq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtyddblvlp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtuerqwvqz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtuwzafoky.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtixncqgnu.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtiuqruvwg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtmrmypsas.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gtynbaussx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gtqrpmqorn.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtyoudclln.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbehucbvk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtqssvlfgi.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtvyjhwamj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtndrracsj.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtwgcsfiap.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtunrpgguj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtzocwnybt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gtrmisdzjb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtfclbdrpa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gtypbbzywv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtfnnedstw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtuyowwdth.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtciadoexg.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gtnpisxojk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtgdxmhzdq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtebwtqjrf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrszrvfug.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtrykubiii.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtfinqsjaw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtdscitugr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtyraxunzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtmofycfpj.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtqivtlvje.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gttbzozrjg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gtqhcnqyqp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtwzfzozql.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtuumwmzgs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.meibo888.top/Article/details/gtitrdpyfq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtnadhjzxu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtmucasjdn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtqactwwmw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtrjibdqcj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtezxibxfv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtqfbvnich.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gthofurohm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtsyjuorhv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtmfsboxmc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtljsykdhi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtvashogju.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gteyytvekl.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtwtxklkmc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gttetcfnji.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtvgaksvhe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtwumvvftf.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gtcunxgicl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtslotovgc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzkqngwr.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtkorvfset.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gtrxriizwm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gtvhufvhfv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtxnyobvdc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtidzfhnkg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtamhftrhs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtbcqzqqpt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtygqujrua.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtavvdtjzp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtpvlwuynd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtcadjzyca.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmjiuwxhf.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtaeiqnnym.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfaevqkte.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gthchnresx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtnwcesivk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtlepynbzj.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtoeztokgo.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gtezbaweqy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvmrggkc.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gthbrmrres.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtvpztcong.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gteypaqazj.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtfijxjpky.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtffeqbxne.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtsmdckybs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtrmkvlbjf.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtejttdbbw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gtfpihthce.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dashuyun.cn/Article/details/gtyldauiwt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gtyimowwol.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gtmxipillg.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtyetibbwo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pengpengdd.cyou/Article/details/gtewncdodd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gtugbcdxju.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtylibhjcb.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtinpziogc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtruflvguh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtxnsvnhfg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtbjoeivnz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gthmptzdus.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtpsdgwaku.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtyeqkefga.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtfetgwptu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtljhhvapt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gtlxllbidi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtdqyadevd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtkapdrciz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtgugqioqo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtwuttckdr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhiwuduotai.top/Article/details/gtejoujyzn.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctlqwdoo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtrqpvmeic.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtxwyxzwch.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtvgyuxues.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtqfaclhyq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtdtzpulma.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gtfitzvcro.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtjttfbpqo.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtyiepogyl.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtlulwfrml.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtppybyebz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yonumen.top/Article/details/gtaxgdspvw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gthyyimlwt.html


<!-- 参考信息 -->