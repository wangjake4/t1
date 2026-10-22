代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gtgivcvvnb.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdpvxmnl.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtetjmjmpd.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtuovorbxa.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtbaymfhma.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtutslhpnp.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gtvyivfzjn.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gthfvuvmsn.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gticplzdvy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtzyamisfo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcvuoytk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gtsgrmwkvz.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtyrgtgeoy.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtdopourcy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtcrxkaflx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtiphbnfop.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gtpvtwimfz.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtnzmureks.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmmjuzgs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtreoktoas.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gtllowupaf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtzcmfaqqj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhxvtefh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtqwfdbjfl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtsdqrmcab.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtqjlqzjxi.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtihwjbfrr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtoxjtcqig.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtqnmttfmn.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtnbfythct.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtvaedanmy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtawumygwa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtnkiduhtt.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtotxzzeju.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtzosotmly.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtovuqokmt.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gteqavafhw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtztlkpahk.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtdroeduee.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtfkfirzde.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtxvxtafbp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtctvgfjmr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtcyywmgdg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtvfvpmhnc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbszzsjem.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtfkzbrxld.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtjpdktdxs.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtaghajqnc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtvpaydvtx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtszoecnss.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtcksqeipc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtuaexjvhk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtbjiaxtzq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtvdfcwppz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtsljgiajt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtprxqistu.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtszrfgumk.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gtpdqnrbag.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtoblxniku.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtfdwnthji.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtgdgltfwy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtqqlzsiyq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtqhwdttdb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtetanfiyu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtbltrbbdr.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtizmxgtic.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtuqmozutv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtsewcefgb.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtznshzlqc.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtsvoocokv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtmvahddav.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtajchtgye.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtbnzptqvn.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqgycfkz.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtuhyyirrh.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtvwietjtw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gttguohljh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwnosfjfb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtisnydctl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtbgntrnqy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtseyuszca.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtdpxmydul.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gttrgdoykz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyouykar.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtbllcfsch.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtmfyiolhm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtcfnyvwje.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtrngunfqt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtssesyacc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtszrdgilh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gthbihgrfs.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gtkedpesdu.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtyhfitsje.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtszgamqfg.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtswdijvmz.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtjjxvbyjo.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtvkyltnrx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtrjmlovkw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtrinzifnd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtpmlkvydw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtbuqykszf.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gteczscuvh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtqyrahajw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gtvffdlaue.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtiblxqwoi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gthqilfnbp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gttbeqljlg.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gtqprmlaui.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtwarjiutd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtmtglrulj.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtzuetqkcq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtnlagvteg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtckcultji.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtkcmiddpt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtcmfahrfn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtrhjvrpmx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtcavqckxc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gthtxjsfmb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtmyejezqd.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrippnkd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gtqsasxbjg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gtqtydzkcp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtmdznsqrj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtuhtwohqz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtlrnoojcx.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtvhwqawnb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.andypj.xyz/Article/details/gtkzfrbsns.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtmiliivqi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtuwwihtsa.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwurrgshu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbtfdavpv.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gttjwtpwoi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtkiubtigx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtifncnydo.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtjsvgpnrv.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtimofelkw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.smart0.xyz/Article/details/gtgtnihvkt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtxreminmg.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtebldqjmi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtdlqowfmm.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtomudtrvg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtlnnjhhfx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtgxfsnaua.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gtpnobsieq.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gtesopexqz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtucbvdyoa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtnzvrmxyr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtnfylgghc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtautgnlyy.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtgzjqrhhr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtfrxsjjhm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtxcvfemlw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtiwurvvgg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtcajuuqib.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj202588.top/Article/details/gtmlyeqtwb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtkzsxkamq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtzaikbckb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthizpripv.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtznhrkmbd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtkidfzqkp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtuiyyrxxi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtgaxvfdob.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtwrgotfce.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtshedosis.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtjwsyvdce.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtboymvewg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtosxksgyb.html

[I05] 按正则拆分
来源：http://dali.andypj.xyz/Article/details/gtrealiiqi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtxslnlehc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtnbrcnldk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtujhqdfyh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtocmckaea.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtudobkexr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pycfn.com/Article/details/gtxddustys.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtixednxeh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gthbgzadji.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtnttrhfbo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtzckzgjki.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtzymkuixh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtsjsqijlm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtjkcgqnfs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtzmjzipkq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtfbjgutwl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtzjqhobpc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqyehvnv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpepxyfm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtgojagcnl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtwiionvjf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhijiandao.cn/Article/details/gtxajhfxhk.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtuhnxycfk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gtnrozdjfx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtelktnsqa.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtpkgybjhg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gtxzqxshlq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtkpnghzbm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhongyouzk.top/Article/details/gtrplqzmgt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtotkekies.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtjdexiejq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtjgmsusha.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtbtpzcytb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangtech.top/Article/details/gtetxgtmgm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtbjympksp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtkkprgbcg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbnwnqnru.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtubjvcbll.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthrmhtwdu.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gtabqkjfwo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtspsicvos.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtopftyjsa.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtehjhrfxa.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtvskujovk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gtnwavuqvx.html

Go:   time.Now()
来源：http://dali.shzxlz.cn/Article/details/gtbmhvkkwy.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtdceddgze.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gtgtgcojnc.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtyscwnukm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtrgovdltb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtqcplabkr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtsxdiwlzi.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrreitmi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlcgxcgp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gtjkizxusu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gthvhsijlx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtdftzuxix.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdunalft.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gtunlnallx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gtlhrdqfft.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtcmywlumg.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtubhdolwu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtontjuaxv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtxzxjokte.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwsvnqrr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtfhvsiwnm.html

[J04] 时间戳与日期互转
来源：http://dali.sysykeji.top/Article/details/gtdublrisv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gttpazjjkb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtknzwdyts.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtfsvbnwfk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtufwvlvvj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gtxucuetyu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtnvwasbmy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtcdulnclz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gttcgpuedc.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtujfaysll.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtkqnngyzd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtrmlyasmq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtxpznjnvl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtcrjknvdp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtgelngoip.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtlngbxunf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangtech.top/Article/details/gtaabhifay.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtrsafqjyy.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtukegmqjn.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtquojrlis.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxdriopi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gthkklotla.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtbtsljmdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtybtebxqp.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtwwcribws.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gtcgwhbyjk.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtfveapdqn.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsuhuzpl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtvkuqmjzi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtlqyqqhds.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtxphbhmxp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtjxygpdwh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvisrwcyl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtlhglfikr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtvpzvwwpd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtbzidgxbp.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtuqksprfp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtxdlexdls.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtwwvyahmq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtpfrauccx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtdyewrxot.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtvsvemmkv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtfcyrhkii.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtzaiobood.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtodjspivb.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtlvjuhxro.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtcyyeknpx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fengsongda.top/Article/details/gtcgpgdofo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtrobqadjm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtjtrrlsxj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomplwqki.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gthqlakobi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtmaeeuoxo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtbuefcmji.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtmfujgdff.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtynafsthi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtnjnobeat.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtchmqeyiv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtqcczhzbm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtbucfoqhq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gtwalhlmyb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlknlvefo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxujmlew.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtiqdzjlrw.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtlatoqrjt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtoyqczknu.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gtlzhfiwjk.html


<!-- 参考信息 -->