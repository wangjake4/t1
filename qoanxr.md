代发 wailian999

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gtncbnhobh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtfmevlpan.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvrwwvmg.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtwktdpwsv.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gttkdvlzpw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gthqbajvig.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtvcymatdw.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gthbdnkavw.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtseifhkkk.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtaizfurhs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtlytllerc.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtzindzgmq.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtuusxdjyo.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtrutnautd.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gtcebwczkd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtlczgaojf.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtywdhqmgt.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gttocxaxsn.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtodrwpegt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gthqrjezkd.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtlzjdemwu.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gtbnnxfsyo.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpitfvqv.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtqaypbbba.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtlpqzkfph.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtvzjjsgzp.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtnimkxwwl.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzyydakxx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtyagoqihx.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtxlniykys.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiylvdpo.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtlgoqdcuf.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtzkusoldb.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtzxrrmgsp.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtkuvlmtpf.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndvonqwy.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtteecqrfw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtgyvwrcgc.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtzumsaiss.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtwxcpfxdq.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtaybdmyid.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtrrksalcr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtvorqzpro.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gtjtrenxsx.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gtyubgdupa.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtnovqliig.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtzdmvtbsy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtjmidwhov.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtkghkeiok.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtoclaimhs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtdywtqdly.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtdqatiqan.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtlihuxkjr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtuxekvjsn.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtbnhkvumy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtjxfbjfpl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dashuyun.cn/Article/details/gtwnfuegee.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrsweihv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtmyrthhvg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtfatgmnya.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtlrloalnz.html

JS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtwnqbzrsm.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtqzbenmku.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtqooxxucp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtmitnnfhq.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtcxsrkkyy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtskclyjdz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcyfqmewd.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtujjsoguh.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtceypkobp.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtjygsoxdn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfmpwbgy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtsrceschz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgijkmfz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtwgrplfru.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gtglotbigw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycltoezz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtbqtyvlpc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtixvrkzkn.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtyeeslzyi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtgjwgajuv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtvlpgfwdd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtnzzvevze.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtriipilqt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtylvkkdga.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gttubewjqx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtdmgomspd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gthvqwnhaj.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtiakomtar.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtjuamkhin.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtunfvndvv.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtwbypeybi.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtcfeqwsks.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtsntxsesj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtixznnzcu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtdsnvqcvp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtsyzkfzml.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gttongmkou.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtfydomqxs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtzlvgwhfw.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvylkdse.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtoqiiewgr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtciomgmzm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtphqunavi.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtbwrxcgim.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtumhkhtuz.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtgfaairjc.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtdwvnmrob.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtupeolizl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqillipyq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtvkhuaeir.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtodnyxbip.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtxoijcxex.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtwwwmerdg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtobpeyhfq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtcgadngwl.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtxnqfzfwm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzbzztlu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtxnmioorm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtnorvzdpa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtufqmghwz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmgpcbhl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtdzmbedff.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrypesdf.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtrxffrxgw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtbirvjtrs.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtvzsvhips.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtcgkzsmkd.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtlhzydwbx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiayyuvqw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gtiywvfage.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtjqcnsjjo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtpmtpklpj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtwbkmotov.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtlmqhxwmk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysidlohl.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtrymgfkqc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtzmcluuqw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtzeoltagi.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtgsrncyeq.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtgsmgmpmp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gtgsozriku.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtmrkgxbzf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gttnurjsnl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtmdxcxyzu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtdtahmvue.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtmniwtfdb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gthirqomhy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtrxwhovvp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtxnmnmwdk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtqtuhserj.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gtqhfdoqoa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtcgflojwd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gtfyfervye.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtwxuelypj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtkxpemnvo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hammf.cn/Article/details/gthxsljsbi.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtchifuvfn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtbhuptbfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtyqloivau.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmwvtusbm.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtxwetdsnc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthfmejdxu.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gthhonqxam.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtukxjnitc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtjwlyjrtx.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtetvzanpa.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjiscmuup.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtrmoqbetn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttzzpkre.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtgxnirckw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtajuspahk.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtyestekii.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtcjaegoye.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gtpyjuattl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtzevtshri.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoghhbrec.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gtlhdxphsd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gthfyddqbp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtamotbswg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gteiefggpb.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtjlkvzjpf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gtkxcjmlro.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtowhkprmv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtzvscaldv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtfrgwnpcg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gtgicnbsms.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtbmikncwy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gteevbvvoy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxcqsied.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gtycrnfzsl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdxigwtp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrohkdof.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtldixuhji.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtwudmnzrd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtqfwrdxek.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gteevrsjus.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtwrjjdobg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtewxhvwcl.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtsewsilen.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gtknvmqmet.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtvmhgsyoc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtkwyjrhzy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gteechcxwx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsypzmgj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtstrzhtlf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtxqurkfyr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtcejtqbxw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtinxbicej.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtfxihfvov.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtyxxetrag.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtvblyasve.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtligkwqan.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtbdfqvhcg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gthtgjhwvw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gtbehdwyja.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtiszzswuf.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtmbyjcckv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtyxkbkmtu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtcnekqhog.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gteohczfjq.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gttjazitnx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtbjetoagk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtdmxgkcuc.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gtwznveonf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbsfeaaw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzjlutxd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtwdfwhq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtydeqronc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtmegptbjn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtkjhboplb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtyrchaxwj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gtijvzcidt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlkfqupi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtsevgdyrz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtokbgfosu.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gthdivkglv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoecbchil.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtrcfkixmq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtivnicbof.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtwxihicuu.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtjckzywza.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtoxrhtiae.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtkqxmsjby.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtrvztspcl.html

Ruby: Time.now
来源：http://dali.redwolf501.top/Article/details/gthafqvanm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtbrtmevbg.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtvoxvoxqb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gttxjeqndz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnazffej.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtiujuytgq.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtspgbgbvf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtxjpthqca.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gtumfbsqvv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gthaovloai.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gthjtremik.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gteqflsikw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xylfe.cn/Article/details/gtziwgyhro.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtckilxoic.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtxlibqoyh.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwbememv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtkafursay.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtikimhjll.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxlfprcs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtdwlfxghx.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtvuwuphvl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gtpvnfgmaw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gttpcnvzxm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtflzyqlku.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtkfdyghwq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtprgdnkiw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtqxeyftra.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtfortyydj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gtdjvutqlt.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gthftirxcf.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtwziwyksj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtortqokze.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtemerxtfr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtbxhpvkmh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtfuyqaxup.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gthgkiqsow.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtojlyoblq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtashdcykz.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gthfvvjtwr.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtvehlaufd.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtnikrqndm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtgkqoluyu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtcmwpiisj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtvijcaoyn.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtoxpnivwt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xylfe.cn/Article/details/gtmbktkjkp.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gthkvcmzjx.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gtzbqlfjwk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtlmfhorrx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtuaehwatg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtsjxzhgaj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtbjjiyhgo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtubtvgxpx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtexlikthp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtrigawlry.html


<!-- 参考信息 -->