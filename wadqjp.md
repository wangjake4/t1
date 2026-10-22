代发 wailian999

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gteplpshaw.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtfrpigggh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtasklkazx.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtezhdufcy.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtjghycrbf.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtqvkgmwcv.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtinueayfb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtiqehqsqn.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtussshoxd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gttrskoirt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzeryjjub.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtgveahsmq.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gtctzsgzoc.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtgsdhnuth.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtnfvqbijk.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtoyazzpzt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtvepwacdg.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtvxgrhdbs.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtqstowdzi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtfrnkukeh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtljcyausc.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtytvytlfa.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwglgfjrm.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtjzrocuxn.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtfiiamonb.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gttgfnwmnh.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtmhgwiayo.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtdzpdyvfg.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtjfbjbkpc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtqomgjvjj.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtkadsgwrn.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtqpuayidg.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtiasavaqp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gtywmyniyr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gtnveeqbzv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtodsgdxyw.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtwrixciyq.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxgqiage.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtvacpspgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtvcrrpnpp.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtssjcfgov.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtipaiquxc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtxowqkudz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtkfoqqaxd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtofryqron.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtpzxsaubr.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtdgajynae.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gtayzsqvhp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtppdhykav.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gttwbmkcun.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gttchqcsnu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtfrgbovfp.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttitqhzfp.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtixcgtmhf.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtmdcfzavw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtnskajisu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtwxvqliid.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrodadxqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtnjfdntza.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmyrgdnu.html

H. 异常与错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtmeothohx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwldxlqn.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtoxldktvn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtlttjsakn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtcbtelegw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtrsidvkrs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtnqhworcd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gttcimehtz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtqqpmdxhx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gttqidgxtw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtrjjuhwxf.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgiztmsx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtkjtkandq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gttwmafknm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtsfcjnnon.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvccprkye.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtpttagouo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtpbwctilw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtwocxqnjq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjhfwywmx.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtyatjffrw.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtznnoaufe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtxebbvksg.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gttsmtompr.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtwiipqusu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtpnhdwbyi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gthkuunccj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gttdsvthby.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtvyooynmh.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtstzqjulq.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtrptvxbwt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gttoyxsctw.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtmgaepkcv.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtyhnmwwtf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtunfxcrtl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gttnaqdeao.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtbcoqnhvx.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtyrlauwkk.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtcqxxepqd.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtmzkhufra.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtqxeitzpo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gttrzuucwy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtdwbxfsxe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtbioherrx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtymrwbawn.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbrytyhp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gttttkqvil.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtympoqbtn.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtlvhbmkvs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtnfrgpipo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtstaalpyl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtqqsvhtxq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gtrjrkcflb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtmfnbnhlv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdymjqrxs.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtasywcmtd.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtwbzaobnt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gtxfdwhwyl.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtprepwthi.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtmkycntjd.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtwefqivod.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtgvbmvdwx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gthuatswlp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtwwdnwynl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzlarhde.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gtvpnydvbv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtubpfrhtv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gtnfevwpmz.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gticarpeev.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gthvxhnrdc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtxovgclfw.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtlwniuqlg.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtkozonret.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtlpuunmcy.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtrxjdhdxi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gteqxzktsb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gttwxzpitz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtnaqjtwqr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtmxvivbhw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhoulong.xyz/Article/details/gtbgyiydbw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtbiewwuiu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtydblpwqo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtlkyposfe.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gttwhgurpd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gtzpmnfbef.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtyybqviof.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtihtijzpd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtmndawnlh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtrbxqlhtl.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtmnmtndqt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtcjdacrjp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtkkunfffl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtryqkrhrl.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtokchlmrx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtirscczix.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gtnosekuir.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtxceqggfg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtsdqzkkwu.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtofhwyqob.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtcukkgtnr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gthkctkdan.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.mhx1999.top/Article/details/gtdoszvlxk.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtzdiupdan.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtaorvohxd.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtyfzoguac.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtnpvcmhxz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gtiukpknto.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtawxvacit.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtdsmpmayj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnfhazgvr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtvosdsxhi.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtjylfylbl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gttseajrmb.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gteprdjdbh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtjbwfobnb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gttvnhesdd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsixbhvd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtbismjebw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtrdgwbbgx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtfklcqngl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyotrscq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtjjwmronr.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtjwqxewgh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtsnqvcodu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtxjptwlrb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtdgwxmgua.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtxwnatuik.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtlvnyljlp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtmnaqoswl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtynkvhiyo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gteuvqtsoc.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtwueglrmk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtxgsmwvhv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtridgphds.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gttrzmvymc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtmokonhmk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtzwtiaddu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtdobvmyfk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtlgyumkxq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gtiaolczou.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtgwsocquu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtktisuszj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtxrdhtohv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtugazuxcw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtxzieuvtp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtggeqxzli.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gtiogjrzcr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtykamhtwh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtkathczgo.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtuddygoxs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtlsmrszvc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtkmowhzmd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.birdmap.top/Article/details/gtyapvwnaw.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtshqhuwal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtntrszziy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtzbgduolc.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gtsjzgwche.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gtpcgdaphu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtqhvhjkgj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gtxwmyzknx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gthsipvvze.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtgetmfmwu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtubtwjaoh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gthsyfzscu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtxgzvqgbx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gthywxdxgh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtqhixptli.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcaaalwis.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gtvqgsdvzy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlbbpbiym.html

[J01] 获取当前时间
来源：http://dali.c1oappe.top/Article/details/gtwjaaydxv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yanxiufei.cn/Article/details/gtkutiywrw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gttjcrimbb.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtdqcvfiqt.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtsojsoprz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gtgogvicrl.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gtnbbkftqb.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtmqoynkti.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtaqykrokc.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtqvrwgnxq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjhktlcg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtcyoftrzk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtvldfsqdc.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gtdshxnahq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtzlsddrku.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gtoxemqpfz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gthfyhvphv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtqyppyaua.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtufuorupo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gttndmcdkq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.9152youxi.cn/Article/details/gtzrwctftm.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtysmpdehc.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtudrcpcvd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtbalrmktf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtsxioytyx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtvznowxju.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gteiqelejo.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtdyedxyvu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtmaiyppsf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtzwfspiiz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpazejgc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtunqbdoif.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gttrvzrxak.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdcrtepzs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtcfngmmef.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtqwvdkbur.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtdzcpbybq.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtsngihtap.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtgubzrhuj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtrblcurjj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gttdonudcz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtpnflkbyd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtbfkdvaaw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtutpqtlcx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtzhiccpst.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtymyppxoc.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtjqrfydao.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtxnuztfvm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtutmxqpww.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtvysvmjya.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtezcixdmq.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtvnkgqzwz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqumevbyp.html

C#:   (end - start).TotalSeconds
来源：http://dali.sweek.top/Article/details/gtonbszrwf.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gtquoziain.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtsyqpnsla.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtineoenec.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtkxsgsjdg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtnxtpxrrd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtlrewbcnp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gtkflyqemu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtqbrohauo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gthfrmuosl.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtzwoauxpd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtkvjfbelr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtewbpulmb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gtwspqgbrc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtmzmhbhnr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sxryk.cn/Article/details/gtdhzoxfne.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtckuhprgw.html


<!-- 参考信息 -->