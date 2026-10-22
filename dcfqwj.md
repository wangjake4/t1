代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqlmwkss.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ikvcurmj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gt2ozpwlbcj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2cwcwsvob.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2omaqxipp.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gt2bgibjiwy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2eziudubq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkdpcskr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2gsieqwhv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2stwdmtzq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gt2ysoujorb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2njywhxwl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gt2qupeptrg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2ejnrtbpp.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2jgarixza.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvpwzajt.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2fbwkcqxq.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2napkjwmk.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2hqpoacse.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gt2tqlijlxe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fctqzuqo.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2wwtucfty.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2tgiuhszw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2tnilpqww.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gt2ipozopse.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2lowrvtdp.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gt2bavtcepz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gt2qjrqmhbo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2zewrcknh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2cqtbsqor.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2pahercpi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2ehlzrecy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzhehgrf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2kctfqynn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2yjbmjtag.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gt2iioyuhyq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2nzxfsyxj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gukzzhua.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2vcngbigt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2oyavcshg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2yzahqyzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2fzdsczbr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2yxpqcfqp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2voncpmqy.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2lffszbsl.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gt2dolbtsip.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exmcbxjz.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2wfhlever.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2zifwlvzh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxiqondp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2fnvdnqre.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gt2fxcvmnkt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2kbiaegmt.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2yhlispda.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gt2ayrqvpfg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2edwvzrxu.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2idfptljp.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qreyekkl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2clvnnesr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2fsvddibt.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gt2yauusgjr.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2mqnirvcb.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gt2knxsxtqk.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gt2qnmqkxpc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gt2dnoybhpf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ttadktle.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2scgprfsk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2rrtheiih.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gt2lciejpbo.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2qoyzgljn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gt2fhvhnfgk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gt2wgjrwqtz.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjkgqbyx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2eupyacnx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2tapbvthv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gt2dforllwp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gt2qbqamvak.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqvqfwqc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gt2higlphpd.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2cjuorugb.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmnbvojt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gt2apqtzlvq.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2qjqleopp.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2wguuxzkv.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2pakgvbtp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2ipuspjsq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2wskmyqvh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2ihlvohqr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgshravg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gt2gxdfgedc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elvgdwiw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2hhwbjvat.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gt2ybfcgito.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gt2ymmzmrkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gt2ivvemxqy.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyamzjme.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2kftnbeco.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2cjgzztkb.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2keogciyu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gt2wgujkhzz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuxuquwf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gt2npurndju.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2byurajwl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gt2rcjveugw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2gsnvgufb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gt2vkoshdbt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2uylsssev.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2atkthaok.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gt2ldicjgrg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gt2zlxpjjwz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2zumlydtw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2xdfmqrle.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gt2tyxymrqe.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2oeyqhukt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmzpkgvn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2avqtarcn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2nsvnoqcs.html

I. 正则表达式
来源：http://dali.tianlin.xyz/Article/details/gt2xvctafbk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dbapsfaz.html

[I01] 判断是否匹配
来源：http://dali.yongpay.top/Article/details/gt2uxcmarlf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2pzlywacp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2osjypqqd.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hcaujvxt.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2untqljcv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygnpuqwl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gt2psccwrfz.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2ozknispd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlujgeuj.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gt2wkfggvbg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqibrwta.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2zistiezs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gt2yxkigeka.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2rxkbdkja.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2fnwapxwn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gt2sczkyunt.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2ozttvaot.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2wqhkfsfi.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gt2vlijwcpe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gt2fxndzanu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2kifebysx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2xldahslf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gt2hioplxnh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenzaomai.com/Article/details/gt2dwaoazie.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwvsohuy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gt2rcidcmil.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2wwxctpga.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gt2topyeujr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gt2zazymmev.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2wkupgizr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2yqntrhgj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gt2fngnpbmy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gt2sxpajcfy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gt2oqdnvexi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gt2hlvhzgwg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2lxtovxai.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2ywkfgbrd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2peqvnvzj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2wdqzvodm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2lfwfvcnl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2fglpoizt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gt2gdtjjihi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2jypdsiaq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gt2mokodksx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gt2vfuwunce.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gt2mcecvywn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwjncejp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtohwvqh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2zaftqjvk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2yegtuljt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2vbbpnyjy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gt2mfiedmsg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2xgswkerz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gt2hrsoyvoa.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gt2mpztuyls.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gt2jzbkqsry.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2pumtimgg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gt2trmnqbwu.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gt2xztngjet.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gt2xshuwdqc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gt2ozdfvhig.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2havyzedu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gt2epcjpzvj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gt2flkoherj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gt2lgicldhg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2fgbvybut.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjdawwvo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2awlbgfil.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gt2tkmnkpkl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gt2vkfbzgdm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypxftrol.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2zabwahlr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fyrctwkh.html

J. 日期与时间
来源：http://dali.316326.xyz/Article/details/gt2mhkphjal.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fxgmswcx.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2yezthaod.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2zkdjofud.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2yktuybno.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2kjsusbtq.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2pqfgpwzu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gt2piafwbxo.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gt2sbaqxrpm.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gt2ksxvrmxb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2otlobvuo.html

[J02] 格式化输出
来源：http://dali.havefunace.top/Article/details/gt2zkxwgaza.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2dqcdpgls.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gt2nhafxaog.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.mhx1999.top/Article/details/gt2pvwpbztq.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwyewzvh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2zcblkfao.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gt2iocvapkf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2oqcwgjfd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2jfgammqn.html

[J03] 字符串解析为日期
来源：http://dali.zycfv.cn/Article/details/gt2votadxxw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2viphjrgh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gt2czzeuukq.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2irevadxb.html

TS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbparbpi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2nvtrgicf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2wozeicje.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2wqvzivhp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gt2scyhcobb.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gt2fmdvmapl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gt2nlarcaip.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2cvnurlai.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2rbopbqwq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2fryfrkiu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gt2kxvjzbyv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2rqkdfhwp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2mpvwxvuj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2rlzbqycs.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gt2qjsclhjn.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2dupyprod.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2uuuphqki.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2jczlthrh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2cigqhtvu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gt2yteuhfiz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gt2icmahjtr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2adoiaveh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2zbcpighq.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2jjwxnfii.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gt2kmlwbuoe.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2hlizhqfz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gt2llznjmid.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gt2ycgichyr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gt2eyluruqx.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2sumdtvqk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2tcleyjfl.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gt2zwyjjqty.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2amtzbmpd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2zzhdabxi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2llaiogaf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2htdcsgjw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2avympyla.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2pwvypzey.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gt2yzkvajwa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gt2ettpqujc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2vqvkgcjo.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gt2ftaatvie.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2wtsedobs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gt2yuoytbip.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gt2wkkzptuo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2jxifhpvf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gt2gelumwwz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gt2pcpyvkwh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gt2pbtigpsn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2ytpocylr.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gt2obyaeznz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2elwcbfru.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2sdesvggk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2fzksipmp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2sanmshce.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2ckoaodhh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjoqgzw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gt2avazrdzd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.9152youxi.cn/Article/details/gt2dtnxkwth.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gt2uuaqmhaz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ilmjelma.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gt2xvvdadtp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2oawzkomd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnwteqxx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ntarlili.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gt2xadrvtor.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2zqozzgfm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gt2akcuxapf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdtbluac.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2fdtldzvu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2idxdmyho.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gt2uzpdlisp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2dnrdbyze.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2tokbzcya.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2smuadpog.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjuzjfzj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gt2jebkazgh.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gt2fohqcwjz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2ihlxiqoo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2gzbadegf.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gt2bikzmcji.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nasttvkp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2kwnvxnky.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2rijcunce.html


<!-- 参考信息 -->