代发 wailian999

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtdjwcswiu.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtsetwkipx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtppiqaoir.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtqszhaazn.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gthhbuuzbp.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gtlemlydvn.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtxgyrrkki.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttfzkibac.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtyginifqz.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtruypzqis.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gteftxwyvu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtilhucayj.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtypudmppq.html

C#:   public string Name { get; set; }
来源：http://dali.hnxiangtu.top/Article/details/gtrdaepfdm.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtebjferlx.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtvxzmrbqn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtptawchjv.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtauphiwud.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtcnawbmnc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwxkjhcw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtkhxmxeyd.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtbpnnvsdj.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtvbydvlrm.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gttuoeegae.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtnicitmoy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtovwbittb.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtcdguarch.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtavpbhuls.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtttiojvxv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gtyidhjzbo.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gttvlknsbw.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gttnhmkjkr.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gtnejrarpp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtifsijxhi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtiqkfpiub.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gttqghlpyh.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtxnwsdgml.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtsyhmobcd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhengqikj.top/Article/details/gtdwyulvoq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gtxxijmvad.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtktzmhgzb.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gthzadzjjb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtqzmisrcn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtiftsgclb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtvbzzfnop.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtaakvutfn.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtueeytqbd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtjvzeyyce.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtdivsmnbj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtojwmqjyn.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gthuyjdndv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtyblxqeiq.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcewgxoxt.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gthmyaohtl.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtpslhfzqd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tianlin.xyz/Article/details/gtsinfnsol.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtzosvfrjj.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtopjybiic.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtgenfgwle.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsulmeukr.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtfsrcbply.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtaqzytfob.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtrycnmomq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtehcuvxci.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtgylomczw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtveixaodg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqlzdoni.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtlxghemhv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtpdsplhqx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjxzcdic.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtlwpzmamf.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtvlyjqqqc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtcgpjysxh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrdvoqtzh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtjjqfsuhg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkismcxrd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtxcwwwron.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gthfuqpmtk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtxokrrkbj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtvrywhoua.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtuuxtknqy.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtgvorvdme.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtmxdbiwnd.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtmafupwzg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtkrejppjv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwxlutfj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxdlsewa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtsjsipwhj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtddzulltr.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtkltqwwmm.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtqojdsecx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtstcjlkpe.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtqwqiwdic.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtzvinnurv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gthrqwokvu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtlbgrcfup.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtmgatfrby.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkewbxiwa.html

[H05] 捕获特定类型
来源：http://dali.sweek.top/Article/details/gtvjuqcdso.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtihwpymbw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtjlxemkpf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtaqrrxxtv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gthrjhkdqm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtahzpqyhk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtlmysgwxj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gtduguhkew.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtqqwntcpu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gtsgbqdjqk.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtldkkdcbe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmklgroz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gteejazrin.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtzajfjeql.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gteosrrhrp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtebbrxrbl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtbixmtrbl.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtcwftanov.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtkawphoww.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtjcgajpxf.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtsewcfcxt.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtsqibawfi.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gthoznaiqd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtollynksc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtkdnctkqc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gttanmlfol.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtslnuqecg.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtnknjpzxo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkylfsxfs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtraoxlsjh.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfkrnqvn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtbjfgcslg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtafhavvxf.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtbdxppoxb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtfeymbapo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtmekvqaam.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtolfkfino.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtjqoiwrug.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtegqtcohg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtctmcsrsr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gtisourzlq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.9152youxi.cn/Article/details/gtlgvksqiv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtpkdoebmy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zycfv.cn/Article/details/gtlpxingtv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtefszalta.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgnfzzqk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtyzpmwxtj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtarrrdgoh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtwsyjytgo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtlwzxkpdg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtlsbphopb.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtbzgiwnuy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtqbdopyfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtjxyuwocn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsnobqdha.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtiydkrkke.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtijlgosbh.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gteqntwwmq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtdlcpgudt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtxoyxovia.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvqdevdv.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtpksqfddf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gtkgidvqcz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtbpsmlnck.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtookxhzmm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtbahadmjw.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtimpxnmcs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtgnzaeswy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtlwxzjlwa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtyzwbmsgx.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtscsvbztm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtnkwblfzu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtpogfldor.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtqcnkrmxo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtcuejcqhb.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtyviqvnjb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtcazprmoy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gttpfwdbdm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtbuxggnlo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtcjgsmagl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtydxlrfyo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtkqkhaepq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtstcqojak.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gtldwknsgs.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gtsabwvkxo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gtfyvqkfux.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtmmxjhxqa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtghxezcvm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtrtgcrmgk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtqcwimlzi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtacgduvqu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtceqvavmp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtfaidzyom.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtqlcfftuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwnahzht.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtsfevcmwu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtgkthmlbl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtfsvvqjig.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtirkgruxs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzlgpzgbx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtkdkydhha.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gtipbxjhio.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtiehvzuqx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gthsfbluce.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gteuesmqlh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtlhchqxqs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtgmjzasrp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtzvjrnoph.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtmsgwihcy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtlbzqxova.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtzexqsquk.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtrpkdxrlg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtutkfbqnp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtjcepqygb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtvwuuyxxg.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtzvlyyqzf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtdslwrads.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtdggeypec.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gtijlgfngm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbwfaepe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtodbbpuca.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtdqquxdod.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtclimxeta.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtyevqolhb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoaeerqt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtnvxhfwpd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvwpbqke.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtucsxebew.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtfsysfirc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvwqjvrbr.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtemeuskra.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gticggqvih.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gthibwiqya.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtwgsugupf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtqnigzdit.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtfydryhwf.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gthrnhpipu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtvkbrafvp.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtfzmllvfk.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtvynwcpwf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gtxebfxcxk.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtemxgbsle.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gthhsysbao.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtcgbymdml.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtysztxnlc.html

TS:   d.toISOString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizfyigrh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigfzy.top/Article/details/gtjaiztokx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsxylugb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtqiojuplz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtazuducrb.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtipxxcpgi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gttmmnileo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gtisgkgbsc.html

JS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtojfqlupu.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtxmscishn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtrytmepod.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtduvpjqys.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqelhzaj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtznczykir.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gtsvujpaby.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtthhslcrq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtxjbltxzu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gtbdqagvce.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsfsasbi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkeemycn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhkgwnmd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtgxtollcf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtvqhtvifn.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtlwwsosxh.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtjaidzwdt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtjbvuygee.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtpqwasymn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtqlhwhtcq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtlbhnhpui.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gteufxqvxx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtncecnjau.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtvlxiblzb.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtdmzvechd.html

Py:   (end - start).total_seconds()
来源：http://dali.bjfxy.top/Article/details/gthrtblmqc.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gthpuvuzxp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtaanpclwv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtxfcmszmw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtymfpyurb.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtqfjiofqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gtkpwchwse.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtynjzrdin.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtxabffara.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gteyeboqow.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtgrvcueyt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtbryxawqx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtsutsurel.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gtbutabgyf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtgxffntqk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtjgvulwhk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtddafwpim.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtcqwzwhho.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtlkdlczll.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtitkffgjl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgyzbdol.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtftvbujxn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gtbxhcujrm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtyexwbjyr.html


<!-- 参考信息 -->