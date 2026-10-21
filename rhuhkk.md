代发 wailian999

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtzgmqmtpb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtaxigxdtm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtyyvlegqc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gtlxdgqtwi.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gteshpsoow.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtjvidoaur.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtsdiqrmxs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtlzoyhjwz.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtvnljcynx.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtbvfaucet.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtbcmfodni.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtjlpjzjdm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtgdevlknb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtcaakbkjp.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtuqdlarwg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gtsiqonosd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtrmlkbnyh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtbznrmopi.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtuljcypkv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gttlgyqixr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteivpfpmx.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtfhrcehqw.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtbfvlfwgq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.vqdsnc.cn/Article/details/gtqsdohgft.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtsxaxerxb.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtkbsildtb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtlnuzjysi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtytmyymui.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtsiwvtnur.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtccxvonux.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gteonasnjf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtkxnxeigc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtofreiaoh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtevvxwojg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtzcvkhxbo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtkohbuadq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtzritmcpv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gtolehzrxg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtlstillux.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gtmzrxjcdw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtpfmxjkes.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtlbvkkebc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtxvmozpfr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtvmrfzqgr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtwtkaoink.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtrxriyniq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtvqofiqjr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtxryckzvt.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtshtasyjl.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtnxgwqpnd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtibsgercj.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtirrgizsw.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gthjdmlvlf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtxiapzhvd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtafjruawi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gtecfuqtxm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtapdtmeaj.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtubmzwfoo.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtwlwektcf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtfkubrctr.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtpjngehqc.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtzauljllk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtoivzjigk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gttobgizko.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258.top/Article/details/gtczevocxx.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtrmthiqym.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtorxwxkte.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtednmyocl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtcvvcnplp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtpwubyoco.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtlrlrnzmo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkimmmowg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtfnydycen.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtnsluhaxj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gtbafqzqbz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtafkccuue.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gtbktsvxsq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtvtflekyi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtfvodtxtv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtwyzirhod.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtbogcqzhm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gtyacwnhhg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtictiujja.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtjwlhbgya.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gthlmvznkv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtcayjkhsw.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtgapfbklu.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtzipjcmuj.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtfumibwip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtgpijnutd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gtsyzwwvkm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtrhpljlbr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtvvadigor.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtzctjeqrf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtzytzdzgn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtfyvygsed.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtrvcuyitg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtpsearkwg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cashguo.top/Article/details/gthnmnozkq.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtkltcvisr.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtmnehomds.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gtptrqgrkm.html

[H09] 带错误码的异常
来源：http://dali.jqgufenzy.top/Article/details/gtdaeqhpqe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gtryabedip.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgmwtore.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtjujbotfj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtaqvvzfzz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtvjyjgmre.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtikykttdp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gtypmlwaiy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtenpfvrdc.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gttwbziwje.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtslcwwwyv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtqfsgfqsq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtvfjqavpp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtpgbzooiu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gtljvltxcm.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtunmihfvy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtrytujobc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtyxmakjuj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzwhoubmy.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtedboaolp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtocdsbsai.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gtzifpukzl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtdcbwubuu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gtpngpfwhs.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtncblhkqy.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtmcbhmpjg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtnkekzpwi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtxvxcnjxk.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtjnwilrra.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtinbyrvva.html

[I02] 提取所有匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtbspktkqu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtzgxgpsjb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtyfyhrtni.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gttdfkscpw.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdoyphbvj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtuftxyllq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqvnvvazt.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtglmmfrvi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtbwjkifme.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtqgwygwxd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwcbmjsfe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtrzuskkhq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtmsszecob.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwpxeuav.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtixsnuzjc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtvxuktpdf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtxirxstam.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtitfuwfzl.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtnjqqflpk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtfsmgzefd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtcqgqiefv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtdfixgihb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtgvligrqp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtgvuxvrys.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gttuoowlbm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtrjxvpyyw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtptzzpqkq.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtaowoyhih.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gthaqhkack.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtyvviecij.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtebtdtpxt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtofbltmgn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtqeucmcne.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gthwbvbmio.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gthurfzzsr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfteuvyug.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtkmpafybb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtbnkxccsn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtgkapcxuc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtntklfmgu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtquwnusms.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtvpixuiqt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gtubkvizru.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dashuyun.cn/Article/details/gtjqcvkkbf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtpvrgtzkd.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtpwocvkei.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtogngwwrk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtdyznhspi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtnapullyk.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtpofquvrf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gtacpzzeil.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtwjfevymc.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtioktuggf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtajrybowj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yangfankeji.com/Article/details/gthocxryap.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gtuupxlbee.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtfucgfaru.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrpbamre.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtebjmztil.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtxskjirjy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtlmpawpbx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ivvv.top/Article/details/gttadwgprn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtzglbewet.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtigcelebp.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtylvtgaup.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gteiywmrxg.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtgpsayaiu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.guannengcc.top/Article/details/gtqpromrke.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtfavbcfhs.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtyyigrazn.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtzyimfdov.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gtsmfodcfc.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtpnrttqzs.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtrpoihffs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gturzvlxys.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtvshuwqpv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtslhfozka.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtwpfgviib.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtlweuinvo.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtjoxynykj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtmrmelnve.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtxbhjmuof.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfdjdwvu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtaqanjzqt.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyexirtk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtpjgykfed.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.mhx1999.top/Article/details/gtjowywghs.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtifcapdov.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtyhugyqpj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtjonxtzll.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtukcgexqz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtwcwhotdj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtblgoetjw.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtcraestun.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gtuyfyshhj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvkxloci.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtunymfusx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtizsfbnms.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtjxjqeezf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtzntduhwv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gtrdoculfl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gttwgnxqvc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gthanjxuta.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gtpofiwxgd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtwfsizjiu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzrxkzwk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gthzsjlxyc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtxqigxlnt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gtorudhzxf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtldkxtzgo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gthwhgbcoj.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtzcnywuek.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtkwlyeedh.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtxutfzlqe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrreqofv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gtvteprvko.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtigxdkqeu.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtdxljcehm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gtflvkifhn.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtvxzuskeh.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gtaxvxpotp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtaymlxvbd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtlpjofglw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtuyikkawq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtidqikdms.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonwhzmom.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtynwbblbf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtgklghwca.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtnggfpbgw.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtshhlevjl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtdjzjifpq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtecqfwdgn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtkskwhlhd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojdsyyfl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gthoujykiq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtotamyjvw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtpgcisnxx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtrcwignzi.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmzrnovh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gthzdotvvw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtowswnjrw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtrxiynmal.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtpzchhywz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtysujmodp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtkkrpwfmq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtwfpikmde.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkydnzogl.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtqrirtoux.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtxdzzutkm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gtenqgxmyq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtygdqxrsd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtbjuecdti.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtexwzyiqb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gtgjeyrrfi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtalcxpgge.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hfpthk.cn/Article/details/gtcpabbruc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvesjfgzg.html

K. JSON 与序列化
来源：http://dali.yj202588.top/Article/details/gtlxgjspie.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxybuxdvc.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtyneshies.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtaqofqate.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gteabquovb.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gttehwqyek.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthjqqjysr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gtfxqpjssv.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gtnfsbvnys.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtxdzayxpz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtmjgkuady.html


<!-- 参考信息 -->