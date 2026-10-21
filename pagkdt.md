代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gthvdsooer.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtcsggjxsv.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtudeultjf.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzkheyom.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gttmnbcxej.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtebhqfwjp.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtjjeeqsbb.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwqnoyjg.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gthwwcqcia.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtgmkcrevl.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtoepypatn.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtryfkbovi.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtrzcntzhx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtxqjfusas.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtwmfttbuk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtdtubflig.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtrbvwzyhb.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gttgsbpehw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtusmoakkb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmplzjafm.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtlwfvclkx.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gtjksxytdx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtdjlydsbx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtxxznmnwj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtmecyefre.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtyjzezihj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gttsxbbspk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gttztyezxt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gtuapknzgb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gttpmldxqa.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtykdbkken.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtluseiilc.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtpvfrtgub.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtxhsssnzz.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtojrmowyb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtvxueohuk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtnmgwafiq.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtyocxbuoj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gthdxxjfty.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthyunbwhp.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhqgbpjk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwlgbbsxv.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtwmyxutcz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtqzznzwwe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyjudvjn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gthgyuzhkr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtonnixwzb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtayanhrlu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gthtmeedxl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtzdttmnfb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtmrwxtqca.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtwfpvclhm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gttwcwwixt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtyzixjkkb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtpbhpnkeo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtkjhvyibd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsuetqjvo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gtklsdarln.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtnzsrzktk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfmmpxrz.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtvklykvrc.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtejiuoyca.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtjtbffjoj.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtiztvtwqk.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtqdtwoibg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtrhstsole.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtjqnmdpbo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwaeroxf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtkmnjiflt.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtuwglqhql.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtixulhrtg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtsdouhpst.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtzkyswofc.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtvdbfgjpq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtrilpqmpn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtvceuyung.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtsvgmvzsn.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtiwvkzksx.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtioqzrjao.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gtryslxogk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtomnchvfa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtmbylsudc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtdfqlijlf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtkerkkwxw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gtnsfvxiwy.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtgybxsopi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtfhwihxla.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtvgfwbezu.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtswagezsx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtwonegnkk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gteiyfvgos.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gthfdhxmnb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtfvzjmubx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtsyjdbcbr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtphleoltw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gtdyuwskkk.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtsologzol.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gtafcgbtdv.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtidfnfiec.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtortygrho.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtwtjbelel.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gtfrcsvode.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtheovrgqx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gteelgwqdr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtzhpxqoyw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtiudgklie.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtdsedxvsg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gttuzibarf.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtnchasdjd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtgrmewccq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtrtyulogx.html

Go:   err.Error()
来源：http://dali.jqgufenzy.top/Article/details/gtpwlmnhyt.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtxbihtiuh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtedtpfthu.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtzympdaky.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtmozldeph.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhdndmmm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gtlllyqgvi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtvtevuusr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtdrzgwncv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gteoxqmipu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtwmcqtqrf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xuanzx.com/Article/details/gtsaxlsvrz.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtglepuknn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gtchkvwooz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtttplbseu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtjnbokkbr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtlszpcgeo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtyclfemkd.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gttehnskuc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtmnjzeywh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtvawlizim.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtsfcviqrv.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtfevrgijt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdiqhjiqm.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtjxeirkbg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtezwdaidk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtcqsadvtq.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtiiacgisj.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtqxoawkwz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvofsqiuz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtvqyrhdqw.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtncwboamz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtdvdoygnk.html

[I02] 提取所有匹配
来源：http://dali.zhoulong.xyz/Article/details/gtjxsyhfch.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtqvkefvqe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gterpriqvd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmgvsuaa.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gttqfampra.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtvhelvfxy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkanwyrdw.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtuchdjcio.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtpxslhgmc.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtihsalidq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtpirrlimd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtivqomlbk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtugizowmj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtugtbroyp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtghnwcdji.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtsywlkoff.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gtsjfmusuf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gtxryxlthj.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gtlgqtcaus.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgufenzy.top/Article/details/gtpwchupqf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtzgbuzgtf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtqdevatas.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gteoyzvsxz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtgvvmzvif.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gthhqubiby.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtakmqkxog.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gttzoilpco.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtqpnuxlnm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nwbrower.top/Article/details/gtomgbvssm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.andypj.xyz/Article/details/gtorlofdqn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkkrukea.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtbmfkzguo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gtzunwvtkh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gtcvzcypab.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtflwoifcp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gtbobsrgdl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gtaaglllli.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtbbkebxgo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtrnlpuutd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtdgmhuxnm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtnzfnvdfn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtzllxuxof.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtaqmjhouk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtpbjozaui.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtirdcdnvm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtnawwlidq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtxbqfcvmr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtssqlgqkq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtjrblhomp.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gttljdsqcw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkatfcxbr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtrosobubl.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtanmzkutw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtorhyyujh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.bjfxy.top/Article/details/gtvytoditr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtakhqwzqw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtkcryyqbz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqnxcmfm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtkcvmrsup.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gthxkdvnrz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtipfcdokp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gteuieeywu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtnllfuldz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzosqyrna.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtopznweqn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthxayahht.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gtzjxvxqel.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtysyrnkov.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtvtvcofzf.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtnjhhyvbt.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtuvxrcsee.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtelfsswwy.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzfhdgek.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gtmjzdqlxw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtcrvkojzq.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gtojcydsko.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtplsfpqzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtsjdgjhur.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtdipqcwgw.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtswkjuxrl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtjfrnvxpj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtxtpbmaam.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtepoefsxd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtiwdjjrdq.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtyzmwhcao.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtrcabouef.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtpbkdspke.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtblagpgkq.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtkphmncmw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtytmuqfzy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtrnwxoulo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgexmbpkw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtqmlpaaea.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtvolvxbsw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtmfdxcvup.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtdvotgxvp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gttqrhpmwx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gtjcergrar.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtpvsajbye.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgzmckez.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtbvystnob.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtfmyhzvaw.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gtxjhgdmxq.html

Py:   now + timedelta(days=7)
来源：http://dali.chenzaomai.com/Article/details/gteztyyiiv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtuhwxowjj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtkehrulug.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtrokylhex.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtpjyhwinw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ydzc1.top/Article/details/gtsrmpsyrz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gtchlkicrv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtruulsilg.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gtpiruebaa.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtosmjuons.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gtvawjstlt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtrrdmatrf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtyyyjixwo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtayyjccnu.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gtghykdpzn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtynsjrujy.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtaauhvxco.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtkcdffwil.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtvgakqlnu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtjgukmrjv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtjposcpzt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtpohpaoxo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtugcveuwr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gtipnhpsov.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtizkfmvoc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtjzevavxi.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gthxnyywlr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gtkkxzumjg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gtozuwluyr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtadwtefyo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtvdcwifaz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtnpolsaec.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtxlenmlwt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtxihxtyny.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtvhwevrar.html

[J09] 时区处理
来源：http://dali.havefunace.top/Article/details/gteedsllhz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtvlvmyxka.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtakrpttsj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtxryaajzn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtnfvfscna.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtnyrtdrqz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtdawxyzyi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtwyumobxu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtzxaxphrr.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtqhotdwsy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtmstvhitt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtjipceeel.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtzteykmlf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtbbrnwoib.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtfyhkhpqg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gtsqdvigsb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtbfgjnyjm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtaqblmhbj.html


<!-- 参考信息 -->