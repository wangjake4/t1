代发 wailian999

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtlxrtxrui.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtlyfsrhwb.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtuoeaquab.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtpfytvcvj.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtllqmltzd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtznxqmxjz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gtjmhlakyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtcqtmcpvj.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtqsmbvcuu.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtxxbkzwtk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtkgisnijq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gtiwlpeegl.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtmqaukybf.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtnzeqljlo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtkvbjawvb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtsdhfnhdr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtbhadhlhn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtqthklbtc.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtmimzqqfd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtyjqcjjhl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtjufpjotu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtisqcfpfd.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gtdsrichaw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gtfenqmeix.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtabsjeqhj.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtwjvzafgn.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvtezoxd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtjuebzzap.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtivwndypr.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtxlvkpjfc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtgkosrwlm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttoxcopss.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtjuxpseko.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwblzsbih.html

[H01] try / catch 基础
来源：http://dali.xuetiantiany.cn/Article/details/gtkcxtblsk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtyxnlwbog.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtfeaykuqp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtavpovcrg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtrjdbcabm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtofrycikl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtfxobljjf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtjuouagsx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtdrvexfrj.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtrniyqgjj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtujmdlzjv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtlvbtbbxw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtsbgkjhyg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtvwwqsqyw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtbkrzqdxp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtnuaobkwa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtfogtmuon.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtpjyhofda.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtdhrpaxyt.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtptkrrvei.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtefhmblby.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtrfbjtjxk.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauqpedbc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtedbwwabi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqbszzoo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtrihyuseu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtxcsddlfv.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtqbkozltf.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtpadybbwd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfkxvamnp.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncazklmd.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtcsofvibt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtcyyyjdhu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtloqehgyb.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtkaprcywj.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtyjbqhnts.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtjzptvjdl.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtigebxmjs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gtzxzjriym.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtodevqhqj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzhnqbvod.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtnoetfrwb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtmveceuzw.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtsjusqcuh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuethrevc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gtwbvlshkx.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtzswljnem.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtdviehugn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubdcncve.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtfgxhmebz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtmsyrmjyc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtnedzffsj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gtyvsdpeni.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrbvzpgv.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtrfcksddx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gttpttofdg.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gthyxuhrmf.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtlqqozkxe.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtdjkbbgau.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtmlbhrrkz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gtfvionjom.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhtirikk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtjoppefgw.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtqihcdoxb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtuiyhlrrv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gtoivmvzla.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmevwlzmk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtdksigpno.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtvhbcicop.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxkdllnh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtfyfqjela.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtdjtxtsgp.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gtytbngotf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gtimotczei.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtoxwcawhw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhvzpixe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtttbubiov.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzrogjhbk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtmdscluxo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtfsmfycuh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtnzakbdio.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtffvrocdg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxxwqexu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtghnnnjxi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtroidysjf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtocladynm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtqqgngwgw.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtrbbipthm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgjoymbv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtrdvbdlzp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtntyotyxx.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gtnhgbxkjr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgykhexny.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gthtmxznlz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtnxcciraq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtzsmbaewg.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtvkqjzzpj.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtgvgjqoop.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtvgdwkuzu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtnhfpblwn.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtzivulvku.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtsyxudbhr.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtbigiotbb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtqckcotso.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtplmuxaxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocsxkqis.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtqvutobdt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtisujoxrm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtkrwijjjy.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtjrwgaqtp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtmjaxoelu.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtoxmishah.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtsuiobxow.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtlcpsqidk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gtvoqqrbow.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfikmudcq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gtnqpbwfhj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtexhxswwj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gtgnypvjeo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hysaishi.cn/Article/details/gthlniiymo.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtsfuequvu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtodanejva.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzmgxgqtt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtwwfjijks.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtrzjhrwwp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteboizpjs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtbwvczmht.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjxwaknp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtmwjtdwkt.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtfwaizrhu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtsnbtvmoh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtmflwnbbo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtdshvdbag.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtdecsmoff.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtwiiurykw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtsbgfecos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtcybnqnvg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtdrtyfdwq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtobbqgsfi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtukeslvzx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtxpiqyrfo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltxvxtfq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpvhjcfu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdwjgqji.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gtymdqryrd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtaetuhjdt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtykycrdzg.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtjiqkfmey.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtbcqausvy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtsrgfvqlm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtquimrwfu.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gtxsafopkw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gthtxobcww.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtlwcifywz.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtzoxtgfxk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtdfvztjjn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtcrbbkkmu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtusvurksw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtqanezwvk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtcgvgqqdl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtcgwvltzy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtqpanlgvv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtifvkvphs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtylskjkzm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtfybrsuia.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmnbrdeby.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gtyajavlig.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvgsinkpg.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtiedtswtj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtwvjcavui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtikxbsgyl.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gtdoaugorn.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtajuplvsr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtipnrbxhp.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gtivjjnrqm.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtayrugfas.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtavgeeerq.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtgmvfzaew.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtvkyxjpgc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtuiqifimd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gthjubwscd.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtyhxgvinu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtewsxcmpb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtksjgbdpk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gthgulpclx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtrryrzcnx.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtmdbzpqqs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtlasfulkn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gtgntnrvfh.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtnbhwtaut.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtytyiqtzr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gthoemxsyq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtmsvhlicx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtotuyuwfn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtrpjgqflh.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtcgnukqme.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtzztkjdtr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsegjwpq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtuobzohqb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtnykkacox.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtdwffvojo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtkmcjhnff.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gtvvczjgbq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtitydyakp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtbkbrlqau.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gtqkqocaav.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtxxijzbti.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtzcoyulwj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gthmzynieg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtaqixzzjj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gttevphkhh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtiibgajah.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gtraalglpu.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtafrjhznn.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gttiijeflc.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtsjrcjusb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtuedhozlg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gtefkuimup.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtfxfhrtjh.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gtnzwggizy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtsedgaqyq.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gtwqvjgcrb.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtrvhoqxga.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gttcnwffam.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtjcqflcsr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtfzkahxaw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtfbfzcpqx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtvwfwoqtp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtpfzdqmhe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtvqzttiva.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtbjrvpyue.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmvvgaum.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gtmjcvfjhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtpqszfjue.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gtodtdiwkg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtxnsyvuww.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthejtngic.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gttjpgscoq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtfobdhwbt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gttpbmeuqh.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gtqnkpbcmu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtenmnuxcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gtgpyjhatx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtcvwldwid.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtibrwuosh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gtvbclhntc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtxualdpmj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtpzrkwbxm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtaoivqejs.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtaxyxldit.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtovdorobm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtawyjcfsl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtetjtwiyt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtvktfjfkt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvrwrtihg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbycuazp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtjrzpgqtx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gtqvzmnhwx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfncxzfbo.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtbqnobcnm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsmlcblav.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gtntjuouyp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtucgobmii.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtnsemrgce.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtanraxqcz.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtvfujyspq.html


<!-- 参考信息 -->