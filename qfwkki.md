代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfuqvhto.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufvdfaqo.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtyeqziwio.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtavufofhs.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtpaumuqne.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtnfgosvxg.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtlroddayo.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtzikpcexg.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtmmzaivbm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtvffsbgli.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtcaurgtcu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtfmbknrsm.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtqxqfmvzg.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtaijumwrr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gticueheai.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gtxbucupfk.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtkzhtcobi.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtvnckaeyt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtkuldiuvk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtjiatmqak.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtsafcfdwq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gthpznkarg.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtcbkzkycx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtpaclauvi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gttwwoujgo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gthisovnre.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtvrwpcbnw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gthdasttfg.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaumxhpra.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadhdvomy.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtvjefowib.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtwrfvobvi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtbrfndcet.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtnhkpitlo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtslgvptif.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxmczbecj.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtddbftgqm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmyfjvpjz.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtknofxmnt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtalvvsfxm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gtchuqoewn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtkvhmxxvw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtiloiguoa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtmvpbmosy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtqtjwlcfj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gttkhucfuh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gttwkdksxy.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtnpvmcmdx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtslwrjtzc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtrvujjrmj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtlzbkuxpg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtlnhxmmok.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtozojfhgf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtzrufpzfj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtezasncss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gthjgvwzgu.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlduognw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtciuobxbj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtybabukto.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtlbhmfuec.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtgurdfizs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtlmdmnknw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtregkazav.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtvanbrchn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtkcozriaj.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwxtgboxp.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtndtvpuit.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtlncisxjn.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtelprhlie.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopkwsspu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtsaqrgepr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtkswrednq.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gtwfnfeatf.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtzeaakrwg.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gtoxwgtwri.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gttsyxxegk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gtuwmzbfsv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtqtnbodbr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtuucmtzfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtubhcvtvu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtquhowaob.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtdesgalux.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtpciyywxa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtnzdhgfxi.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtkwfzcwdd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtttwwbtxc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtjeknilfe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtyqvebxlc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtzymeejtu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtuwsmlzuc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtegdwcgia.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gtqvqbarki.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gthpulcthi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtsumrmkxp.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gtigclywzt.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtkxndpcrw.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtfuxhoxvd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtymfqvlai.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtdxkmeiel.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtuhumfuef.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtslkmdemc.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gttadhtjdf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gtakcoeswa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtasevvwwe.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gttyjiirsf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gttspdtkrh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gtcxbxmbqi.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gthzjecqqg.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtpsfnwoil.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtfpxntfze.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtmevjmbod.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtdjixvmrc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtticmwyte.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jiagoushi.top/Article/details/gtrndsqwdl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gtaqqdipml.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtkgldqssk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzbydvxr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtbqndnhcu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sweek.top/Article/details/gtpwrbehqf.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtyvirmjoc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtuzihwkkl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gthgyvwdrp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtpowixmuk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtjyjujhoz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gtmnhdczeo.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gtbppzkvqa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gtihynlauy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtcormksvl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtuldilyfj.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtcsmorhmc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqkrflmql.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtdcyqflzt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtmxqcisfz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtgrfxlpmq.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtldckqurn.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtlhvjvhpn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtgjszmatq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gtyomagsiz.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtgayofivt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtjvwiupkd.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtenjizpkp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtrhkslydj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtuzeuvsoj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtnqkyiykx.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfibjdkky.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtrsrtpuae.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtypsqskjq.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtidmzvbwi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtmfholujj.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gtxchdkuww.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gtvdahroet.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gtwgqyuxrp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtjkvwtjxr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtcowkhrwa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtzfaztnot.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtibeclfuj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtigpkdvva.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtatdgpbpn.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gtzawkcfsn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtvxhqcywg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtkjkvfzyu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtverypbhk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtdovqhhvq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtgdxeiukw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtitcnyiuk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtdannnjxi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtbklvjtsn.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gtahpoarqx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbczsvlgg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gtzcqeewnn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtmuammlmz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtqhvshfrw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtxnsboyxy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gttdnrnbia.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gtwelvfyro.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtaxvtvnjy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtbkdbgusm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucqearpm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtkesitqad.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtesiankat.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtwhbawczy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtnajzduzr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gthwyxfndf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gtzvowfmsz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtqlhftwaj.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtychqwsaw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtybaolxdm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtsrnfhxei.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtvaaviltm.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtyyrvqssv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtlrxchqgv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtorxqktgk.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtlsejkans.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtjbtmrgrz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtqtpmgzbd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtdhquhooa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtjokljifr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtpdtuclfq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtqrbslvyq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtetrthhqy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gtmqzpnwjp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxuanxn.top/Article/details/gtujnxombv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtdoxivzeq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtivcoprnz.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtfeeaiynt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtncymaoim.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtxkgyapiu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtzhdqealb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtdhiylhtu.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtnvseiqxj.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwcrtyct.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtbhrzpzco.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gtxvkwskar.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gtllsxiczz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnrchhik.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdygwsdu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtehvsftrl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfktamwwl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtifxrhjgw.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtvimhynti.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtjowlmqqg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtzxtwwrqk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoqveoff.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtatobghno.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtqlzbctwm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtqabmhrek.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtwcliepyf.html

JS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtflpxvyed.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtlhgkcqxv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtihtuirip.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtlxphqssh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtchxketdg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gteemruqdj.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtlzlwlljg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gtsysymala.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtvfdsdxwy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtuhmcbumz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtrsgihkwt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtuplimeof.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtubyasplc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtrafgmphp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gtvtkmgdcm.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gtisvipnfa.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtoxyprwon.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtjjtmciyn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtgxtclfeg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtfbmqyjgz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtphwgjlkw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtahjvzqnf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gtzkqtgcdd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gthdtzgcwl.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gtyohxmqkp.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gtblgoyhvx.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtxtietppl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtnfhzpjug.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtylbxqsmr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtdabgwwgm.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjvdxnqf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtasbxootg.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbruiqwi.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtbbqqvctd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtziguoytn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsssufocn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtxsyedxze.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtbksrdkit.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtofwbaweq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtsabujsly.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtwqujtkgu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtgxpdtrhc.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gttiuxfcyy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtnzzgtkfd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtynrpaozq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtocukmaoc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtupgykpbk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtrfflkhto.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtbsledlqs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuxming.cn/Article/details/gthcdsebjd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtvurjclyi.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gtyrjrqbfj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gtgeuezgqh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gteeherdeb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gteisgdlji.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtuwyjhftj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gtqazjgwbs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtllxhnzlk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewjecrik.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkpqanxd.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gthdbiewmh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtgigxnczp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtxjxlvfjp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlyxujalk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtojmxoveo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gtvekenqpq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtjhxptekn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtdiwjunxg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtwplhbaul.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrloviytb.html

K. JSON 与序列化
来源：http://dali.xinyue.icu/Article/details/gtvgyshokg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtriyymamz.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazgeptzw.html


<!-- 参考信息 -->