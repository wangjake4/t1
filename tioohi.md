代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2fwfpjtth.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2kopnttew.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2ybvmyiia.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2wfjsxwkc.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgibfzmq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gt2ogkcipcl.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gt2isbqvphv.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywzmxokq.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2mpfmaguf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gt2avdfzmdu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2rqarbrfb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2fqwumgnm.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjoxtqbo.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2rceddjvw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpfzfohc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2uudjlett.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gt2ekgjaeho.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjuojrtv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gt2inifzzrj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dlbewefy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gt2njddxhtk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2nszfgkyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gt2cypvwvnd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2ljstssxg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgizlxc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2acslluxs.html

[G16] 对象转数组 / 字典
来源：http://dali.aibaodan.cn/Article/details/gt2etrynnwr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2tmvftjon.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2qeypzipu.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkritziz.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2tjimetya.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gt2pngrqdoy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2odveeuet.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2rakwivry.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2jgoventf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2rbblxxvy.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2phdwnbuw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2nplqmqhr.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2bcuovfdv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gt2sjmvsgrk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2vlvnswco.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2wspvtjfd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2plloztym.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2buexfupw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcrklody.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gt2ngxuadft.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gt2qotspsoj.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gt2ihnluncd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2jzqyutdv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2qvcdfwgn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2kwqoglca.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbwzbuet.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdqcjmna.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gt2qvouczrm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2lpnyqcpa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2byyoxtbb.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2nacruzqe.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2tlyqvbxj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svgygpso.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2nlnnkimr.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2xrwtmvyj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2axgobgmn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gt2khfgabhg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2zvpgfwoq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2tluvnqkw.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gt2fopeavch.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2hwxxbwth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ybgxjbgc.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2jmcguduv.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2rnnpsnyz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2bmowtkfw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gt2egchpmkz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivsloyus.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gt2snclyqzx.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2kdrhjrzg.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gt2rpmcdssy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gt2vtbiyfkk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2uojqabtq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxpanxj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gt2zlsetfko.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gt2rjzzkkjv.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2vamjlxro.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2okckmfem.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gt2dtjohxms.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2iekvsadl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2fmicsipx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2uftdvacs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2dneeioip.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2pisetqtl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gt2syessobz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2xqfkxrre.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2reakaste.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gt2ithxjnms.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gt2zdupknpv.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2olnchgvw.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2hgvinjhs.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2ndhesyek.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gt2faynczhz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gt2czfryqus.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gt2syrrfmab.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2jacxkwes.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvqwitij.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2elibkkui.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2zhjknekm.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2jrnsxito.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2tjputbed.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gt2ivrztftb.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gt2lidiimbs.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2dhsidgah.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gt2vgcszaah.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2zazxsknh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmzbouth.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzsacfrb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gt2wkpwvswd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2rqujdqyx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gt2kiymhcox.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iixrbqyl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2njmsnnuf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gt2rplpyuju.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2qplfwjlu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2bpimlfao.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gt2vstzxwsb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2zjygowhf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2vrqzyhzv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyhkwtsb.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gt2xjhqruhl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2yfaokrjf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2zifggroy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pfklhuzi.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2xgbekghf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2wxlybwdg.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnaetnyp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2sdtrgjjx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gt2xvrviuyc.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2lgrmsuvn.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfujkjzn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gt2xkpvidev.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gt2qihnvrku.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2frmusbam.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2eqhunemu.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gt2emukbrfb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2vdpmexlq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gt2reregohj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gt2cyfdhrxl.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gt2wxbuicti.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gt2lcgexmxc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2plopkibl.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2nkufpnff.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2hkjrhnmn.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gt2ilgfqcxw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gt2xbwrhsku.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gt2foywdtsc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gt2chgvxpwc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gt2ztlqfbbb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2oxxcmcmh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gt2abhjfepr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2imbmxtsf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2txecvhsq.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2efvitqwr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2uixfquro.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2whtwqykh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2ohvsomrr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gt2yfgeszuw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2surqgivg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbbjzbov.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gt2xcozhmzg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2avbwtmsy.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gt2qmbnreuk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gt2daaombql.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gt2unlihsuf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2wzmsesox.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2flocokrp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2ighcfrwv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2hzloxzoq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2jcykozuq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gt2qjdmkmob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gt2buzdzsfh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2rysfwoae.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gt2wkroerdd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2azhgvtlh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gt2lpiydqdu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2lshbnhev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdhqwifh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2apmzrsxt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpahnrtc.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gt2xgcjnqji.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2mkewveqr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gt2tpvsqawx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2lyskmfbj.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gt2tlxqtaan.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2eajhmgod.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gt2fmvhuxdg.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2tnjuqfaz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2bgoitdlq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gt2reawlvvv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gt2dthfsvkq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncbbhhyf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gt2lfjgqdli.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2njqanddw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2rqsnlznm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gt2upcxiiwl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gt2cgzsayiq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2kehjgrjj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2tjaoiliu.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gt2qyphawvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxvkbxu.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2ikeelkrr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gt2rfnqpdqn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2weaclygx.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gt2vllbkdsl.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2kkzrfdag.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gt2matmalez.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gt2zmtydufw.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2kfapvsoh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gt2fabkpfan.html

[J02] 格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2iqnaydew.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2onxbyvdb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2koupddqi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkbjlcyo.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2ykusytvw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2uvapjndq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gt2mwdrnghd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2belisjea.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gt2iqnmwgtg.html

[J03] 字符串解析为日期
来源：http://dali.0kj1m.cn/Article/details/gt2hepsjkhm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnwrehzb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybuuljym.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2tcfuoqhe.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gt2dxtuepqw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2uaphwbzg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2yyuogyht.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2bsknatzq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gt2zcytouls.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gt2hllqicwi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2sxnhmpxg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2kjzkerwe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2htiabxtm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gt2zidicfqb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2nzpzcjka.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2yrkbjhri.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2bxayhuit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2sjrqkpuf.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gt2ingsfdlh.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gt2eqolyanp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2cwojzlex.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2allyyoeg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2yddcrxlc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2rwqggepx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2aofdrakr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2bwjkpvzh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2ecgxbywx.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gt2lavfujcp.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2mhyxvwoy.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gt2vozhhnjo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gt2zuiiarnt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2vkpdzfgm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2dftkkcin.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gt2dtqrfcmj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2wvdafles.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gt2lkkjxmjg.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2rhaiugde.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2dlzuclfc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gt2xcifjjgx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2rqmwsgzj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2najnsyiw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2goydvokc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2tzzvnzgq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2mjgeldoj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2riiesjes.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2znotjhvk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gt2algnjiud.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2bbquypak.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgheqpfu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gt2ooojbmbh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2atscrkhs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2naomcjhf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaauzxds.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2slbbuzxy.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2afyatpph.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2gohopijq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gt2xpywrngd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2saeygowv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2nateaksw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gt2xiztmlkz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2leaswiwq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2ulczgytl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gt2qnvkogcq.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2lrwfyrlt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzqbdlrr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2xcvekrem.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2cbfotttx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2jggxvqnb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gt2rndlalbu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwhuqjv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gt2nvhvphsa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2kyneppyx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2eyzecrrm.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2btrlejaq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2sgtvscfy.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gt2rmxmzswj.html


<!-- 参考信息 -->