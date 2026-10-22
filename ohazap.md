代发 wailian999

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtazmjjvkw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtnzipvtlj.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtkthqpdyq.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtildpzyyb.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtxfddhxik.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtqwyqbgks.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtgdepwfsm.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtdbamynqk.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtpltkuadd.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtxzxqizak.html

Py:   @property 与 @x.setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxddsngw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gttyszedjc.html

JS:   get name() { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzwvdxeqc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtqdqsskna.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtoejzmfuy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtwstnbtdm.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtptbddlyk.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtvyaqhprx.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gtlohwrtwz.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtbdwjrkcf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtrtahioij.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtgllxhhnq.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtwcbfvizh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtjtmgemdi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtjzqmetgk.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwybvmrax.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtemilsssl.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtolkknfiv.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzbfvxvn.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtzdmbtike.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgykpvtwm.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtczxebfmj.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtnplgdcpu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtxoryeotl.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpubiwspv.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtgjjpkhkm.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtdfmehctw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtdfdgkgdw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtzgninzow.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtvhwrxilj.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gtdybdyeod.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gtumzzxkwq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtzzrvxojz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtjqwdqilr.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtdiiraluz.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtpoyqtnve.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gturgbaowj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtcwcijmyy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtxqajbfgm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtomyevpuq.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtruyyvtuo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnzkycvf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtqcomlkcl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtprzjquye.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtrjfzhort.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtixvxqlrq.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtezdhfvsr.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtwnvdvehh.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtomtvxucv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtpnzbvqan.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtdyhpkiaw.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtfhkbsspo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndgikbgu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtleupjlbo.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtnzrdluqu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdletlyyt.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtsdemdajj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtcesbienh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtigwqlrug.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtrtbvrzdc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrrctsei.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtqzvfznoi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtznfdyybo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ydzc1.top/Article/details/gtfxerylfg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtiiddgfoc.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtcnsppihe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtwsxricif.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtxdrhzqxy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsnpmbprq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtapdsxksd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtittkgrbl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtwtjnkkxl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gtybjkypmg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtteouylvv.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtrhxqvnbk.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtahhzfefh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtznlnkpao.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtqqdtpdth.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtxlydssvv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gttqazdheh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtqffciznn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtsiepbeki.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtldlgkmyc.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtbbtrfzdj.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtaczhfjed.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtrlbmpklu.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtnlhtzyrh.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtikgzigqp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtoseuyjjz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gtofgpqcbi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtahbgofma.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gtzauczmjm.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtcwkisaat.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtmmnckbex.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtbpgcwlxu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtjxyvbpwh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtqmercgcl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtojdpspbw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtchcmsvie.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtlgfiwhtz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gttyczjano.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gtrznwsfrh.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gttvpehkem.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkzxokst.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtytfeuumc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtdhrhlpua.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guowangkeji.top/Article/details/gtczuplzoc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenlongwang.top/Article/details/gtswzmuyzr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtsdsjfzbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gtjwdhdjbr.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtsjombgsj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gteptzgbgv.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gthnecsjml.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtrvouxuws.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtowayphvl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtlyddento.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtoaiazmxw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gtvmosvhaw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtqtwmzdip.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtsxiilsoi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtmibczeju.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuhuikuj.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnvesvmf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtkwyoffot.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gtcpzdfvng.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtxdnfcbth.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtqtjirnjz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtzrosgimq.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gtblkojdgj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyvasiit.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gthpsffhks.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtukkhodhi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtoolnneus.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtpfigsjzr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtthqpldoi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtlrkhzbkc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtdwcuwnsu.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gthzwuxzpe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtcqisnkvr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfutkclxr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtyaakcifu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gteeuuowac.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xziqi.cn/Article/details/gtcrkejxwe.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gteolavlsf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqozbtxih.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtsmcchnmd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtngsajudw.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtxfccllfw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvbkorwfe.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtugccejiw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtumoboqno.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtsudqxmtp.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtrjhuvcrf.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtzhlkpdyr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtdotnwzur.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtfphzzive.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtaxfliyiu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtudjxcvbu.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtciwotxmb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtazhjylny.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtzuwlzsah.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtrdrmtfhl.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtsezqjyeo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtcbivnrrk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gtlkfkdoaj.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcspwlhw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtugjlmthm.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtmjiwljqu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtkjgtueua.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtqbvtyppt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gtaahoehqd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gtwejxfeae.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gthrndscis.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsopwmls.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtifdygicg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtgmjsijed.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtjqedxpvn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtycxxndrd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtprpxxajp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtwjkjuarp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtmfualxef.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtehzjbajw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmibdosfk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gtfeesijvy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtyszbdjyv.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gtoriioimp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tian-w.cn/Article/details/gtiojbgxfg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtahceegdj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtylutoetd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtfxabxzzz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtptdqojzm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtejeqtakt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtgdsviqwd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtfefkhgfx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtsqslaxcr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtelzjlarh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtznwzhsix.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtwazcdgzx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtjnfyrbte.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtbysogcey.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcnemege.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gttglabvun.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtogyuhnaw.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtdadppjcx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtzwxwruxg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtioqaohkc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtlgoyqzvd.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtamejwugd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gtmtfrtptl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtrenigecm.html

Ruby: s.scan(/error/i)
来源：http://dali.yj202588.top/Article/details/gtbhkjbnvo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtpwhblmcy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtgiuklnfz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gtkfvxibqb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkghyzej.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtumvcxtrg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtopbtsuhg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtqvgzjzow.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtgxwvpcff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtkcexskre.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtwjfxvhyz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdouywdmz.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtmmvnoqai.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbjkapsul.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gtxzmprmvm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtnbqpannd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtsbkzrarg.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtbdvpgxsb.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtuzmpubnj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtyqirxvcf.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gthtxsxjes.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtrggbgxek.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gtwkzqbnyw.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtggbqcncu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gthpmtlozb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtoyqrvkpv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvfboerm.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gtarcmsjcl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yongpay.top/Article/details/gtgvobljab.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtklzaprni.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtkcywuhpc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtcemzlunr.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtcwpadsje.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gtclpdwruq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtnazmtbwa.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtyxwvcqqi.html

TS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtnnvyignl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gttddaesmc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gthkqsnppc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtsxrktzkk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gtyvgsnsub.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gteyxvhirf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gtbfeswyfr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gthidhwlrf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtehihjcvi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtpqtjmmnl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtlojgzjsb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtpkckatwt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtvjztayev.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtcxbxfwhf.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtrezhnqsr.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gtzlmiihhh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtaysvseux.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtkcmjjhry.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtkqsewdfq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoxiixnf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtymrkgpge.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtowzrgbkj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gtilguvnsb.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gtbgkyvpsa.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtnvnvpqfw.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtsydlwuyf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gtoyfwzavz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtxhrirgfk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnhzerqa.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrltwbguu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtlzdajdap.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtzppmvatx.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtdekhlqhi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtrahtxwqz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtrmqhgoty.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtrghwbfqm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxxckfsl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gttdbxshsr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtukxrnuxt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gthgtteuqw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtljxadxkw.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtzoafdtvi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtslyxsbuc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvrxqxwi.html


<!-- 参考信息 -->