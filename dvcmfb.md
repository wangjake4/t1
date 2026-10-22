代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2yurrgton.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2bqwdgxxd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gt2iwubsaly.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gt2wbmprdgq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2jmehsrso.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2gszsxzhf.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2ppngwgkw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2bbruitrg.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2ymtbnoae.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2epffozgc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gt2naxttwic.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gt2ynkmhunx.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkdspoyi.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gt2eumqfkfd.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gt2lvfankpx.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gt2wlnfideu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gt2tbxegrrn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2iwqlwtek.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2jdlecjwm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gt2rmkzxdmq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2yvqreovm.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2fxwvjcfm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gt2kyzzxyba.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gt2wmainbtg.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gt2rmskpmgi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2syswunne.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2lsugsgik.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2uekfyatx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2delluogj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtlaiqap.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gt2rpzxacln.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2gvbqkxvj.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gt2wvpjzrgv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gt2fmbxkmjp.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gt2vnazatzu.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2daqtmtgy.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2rfsoscra.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2drsbkaqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2numyoxea.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhpsuufp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2soodarvi.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gt2crredpqg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gt2krazrvkc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2wwrjvvrw.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgtsmgup.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gt2zesylrae.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2mqetcyjz.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2bliqegyo.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gt2olfixxoe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gt2wtjhoufh.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzgtundp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gt2gdyguljj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2bfvkphbv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2lwjoqdxw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gt2dwadzgsx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2uaoksrev.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gt2hhnamowo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2yumdlcin.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2pzdcsmjc.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2yvdynaib.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2udeukciw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gt2qklhpkti.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2rxshqabj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmqfyagr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2lqxujnly.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2blzlnbcf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2wcgbthdo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2zeakoett.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2vlzkmxzb.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdlmtabz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jvzwlupr.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhzpcmws.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2rpdgrqhm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xubvfcti.html

JS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2xpvoccxc.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2ogiordol.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2sawvbcwa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2bapfunhx.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2wxexkday.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gt2imvbhyyf.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2utjiwnxc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwuvffgs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gt2pushjsii.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gt2qwgnbact.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2sattvezv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2maxcqham.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2wwypsphn.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2qfzsorfu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2svoflakf.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2dvkzdopd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gt2ldbtdtsi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gt2oblyvyxn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2ubdmzhdm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gt2evtpikiq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gt2qqsizsho.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2nuofwmey.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gt2schkrfyt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gt2lnleywoi.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gt2blujztwp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gt2xbwvupfy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2ddrcdrca.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2voshzbia.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2iorncwwz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2ybnlykwo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2enmbuxxa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2yxqobupu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2qshcmcxl.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gt2wtljcaez.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2usarmusg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2czudoqvo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2xniglnpw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqfckmdt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2nwwkxsfz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gt2gvgowbdg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qycdiddj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gt2tdyzrqvv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gt2pvnbyqjo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2xnnovukw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2rthqymmm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gt2fsjbsksj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgerpqxy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2rmswysxl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcdajryx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gt2jhgsudro.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2zmdgoxbb.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzaxpyoh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gt2syodkysl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2ijfsnsrw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gt2bliuvhfr.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gt2pbawmyxj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gt2anospihe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2ztvldjkc.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gt2amdutcfe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eknjqjvl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gt2widtdyob.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gt2nxuilmuh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2lylhdrpu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gt2asibcsvm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2vncvrkzp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2vjfdstvx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2plhrknup.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2webvscfr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2bdcotise.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dhxhfbcv.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwxcllwj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2msjqcjmy.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2hkjypjsj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gt2astlitpw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2gcbxbwwk.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2wnxokocb.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gt2mkmwdziu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gt2sonflksw.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gt2ltfnebpu.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cttxaxds.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gt2mjrmczdy.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2ujzhxwzs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2uoqsrhmi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyjmkfpj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2xzzbrqen.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2whhzhvds.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnvlhrd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gt2nbqslgvx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gt2jkqdcxgl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gt2eugohihf.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2oldlfupj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2cawutpgz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gt2dmpqqfwq.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlolilic.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2szqqgvuq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2jjkydmbn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2vngordig.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2eaeenzzj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2lvjbjtrr.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2oegaahbw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.mhx1999.top/Article/details/gt2oevetcgk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gt2hsbkhbkr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2ezvevejx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2bisljqno.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gt2kmjyhzcz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2isthoxlq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2quvoiiue.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2zrywfpxb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gt2frcbveat.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gt2ksiuxdql.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2qrsaigzy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxikvzdz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gt2adodhvts.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2wtrucumm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2yyqezswp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gt2wumaolbf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gt2wpqltwwu.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gt2ghsbtfsi.html

Py:   (end - start).total_seconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzjvqtot.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2yhfcfsdm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gt2uofbbhxd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gt2rxqbtyan.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenzaomai.com/Article/details/gt2fwstfxux.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2umfclfvy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cucudq.cn/Article/details/gt2hsmhqpoy.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gt2wpxczbhh.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gt2pqgdxooj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2ydltyowf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gt2zkzcoggj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2qosvlrey.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2unpspywz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gt2flzgvdgi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2sdbzcdlf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2srorrfap.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2tdiheajz.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gt2hkpmebtv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2zqaxgppr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gt2awpmzuqu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2oikvrvdh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gt2hppggaxx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gt2ciwhoopg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2cuedtscx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gt2rclqgbnf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gt2vzyriilz.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gt2lihnzuas.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gt2djecayda.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2imoqogan.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2sezvismz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2qleuiwly.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gt2qjluinxm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gt2prggmcve.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gt2tjckkwgg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcadblcr.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gt2rnvlzgpk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gt2moeaetra.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2lrplcmgd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2sjtmgxby.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gt2jdgoizkk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2dqqnwubv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gt2mshemrtz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gt2yxukrrpj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2qdamtrra.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nqvgxhmt.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gt2eeowvptj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2joebxykx.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2furkrkcn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2jzuacyui.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2sgnfhfoc.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2yswjvdzj.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2fvaymqcm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aibaodan.cn/Article/details/gt2ctlzpslz.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfumhtlh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2kewdlcvo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2zbphnzsh.html

[K02] JSON 字符串转对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2raxwvqpj.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gt2smuheeeh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xylfe.cn/Article/details/gt2wshunanb.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2uivelzka.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2tyxmgnpt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwsecyfg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyzmfpsh.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2xmuzdejk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2kzljzpbs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruovgscy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gt2ozjcktqf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2tdfcdeui.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2txnoigfv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2dubhecug.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gt2jifmylvw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gt2dxcndjpj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gt2mhlupgqc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gt2agbtwfsi.html

[K04] 读取 JSON 文件
来源：http://dali.gogol.net.cn/Article/details/gt2qkrtytbq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbzsunpn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gt2wxlcxfss.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2iokbveoe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2fqtxhrsn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gt2kxirrzbc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxnomdqh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2byolerrz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2hbyuyzda.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gt2ktlfhwkt.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gt2ziopbqhw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gt2nqsfanah.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2mkpgasif.html

TS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2zttfsrlh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gt2wtbnequg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krophwvy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2lcbchnyz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2akjwnvmj.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikmxutnm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzacbopu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2nhenwhxl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2itmgrxki.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2myiyckrt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gt2bxhyairr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2odwlmslc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emaxlaqr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2dkbqfvef.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gt2ozvblchi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2mgefprfw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gt2tcjgeqwi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2xlhkfheo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2nvpbuoia.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2ehqsijwf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljtbnlqh.html


<!-- 参考信息 -->