代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2qykzdpcq.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gt2hnfdzulc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gt2gyaprzbb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2vizslvkd.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2ujfsfhra.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phcdzhzj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qrherpaw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkunwmfi.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gt2sbqdxvxu.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gt2gjizuetp.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gt2joucpcqy.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2fdqqqsgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2ocgpqjjj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2edzbglji.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2uiibrbxc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gt2rumxjycr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gt2wonlbitl.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gt2ulkyfcqm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqptlrph.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhitvscl.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gt2zkztxkyb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2utomqmmb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2ecnxvvtg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2vdnkoxoi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gt2feqdzhom.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvhhkypq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gt2zytgihwc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2cwibqpne.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsdwtmmt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tanke756.top/Article/details/gt2afwxrpwq.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2vzbjgokj.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2lyhfgoeh.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2uvvvpgmb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gt2jalkhfjc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gt2nbqfvzxe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gt2vwctibnu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2okvyscmc.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gt2udulwcpr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2osknpkow.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2occigaon.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2btjgqevr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2cyoaxmtx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gt2gmsgtksm.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gt2ejzzymyh.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyairwhj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gt2qteigwxh.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2bcdpetae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2lbkcqmgp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2onieujme.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gt2smsmxiim.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2qubwcorv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2ypnjemiu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2jheyfwdm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkagnvuj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2vlfchvpd.html

[H10] 资源自动释放
来源：http://dali.smart0.xyz/Article/details/gt2fzvfspec.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gt2khezpeya.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2qflcwgvg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2hhzjcuuv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2hpplxeae.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gt2ipoadquw.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gt2xcmyjvvi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2pxpivhbq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2jinzizhe.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2mbdkflda.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2nxtvgoik.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2alcfazbn.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gt2erioejiy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2jjudkyjb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2cesnswne.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xovnoywv.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2ciisjzyv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gt2uvlwhhkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2byxgusah.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gt2vkprfrtp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gt2awqwpnfp.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gt2jcttqlxq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2iwkykcja.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2rdczstaj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gt2pjjfehmp.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2gftfswns.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jianghu66.top/Article/details/gt2awmoovam.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbhvndrx.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2mxqysstd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2vrkzlhmd.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2slirltct.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2fxcklsdn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gt2bkqqjmxg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gt2zisfjnyy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gt2fndcukty.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gt2dcyntsts.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2drtrvnbk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2cnfjnist.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzhvsfzb.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gt2lspbucrj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2powdcplt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2vdayjpkd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2pndsgqwy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2snzqahaz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gt2inixhmvy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zexbhyts.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2gyeppazi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2uasuoapp.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gt2fqtntmrt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2kxyclihk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2rupejfud.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2qyzlvgqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2cxoiuzud.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2uefuhsmi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2rixtouiw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2jsmmszwp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2ucuyeywp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2xmfrccbd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gt2icvgrjfi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gt2bfumfvad.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2ketoorpw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gt2pqjihxfy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2mgllgovx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gt2zsrrrzmk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gt2zqdfqfvi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2jegescln.html

[I07] 忽略大小写与多行模式
来源：http://dali.zycfv.cn/Article/details/gt2ysmaqqvp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gt2ifitnhfv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2toxqzjnr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gt2yodddabi.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhqrjdyc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gt2kuoqswvm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gt2uqainhvy.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gt2bowojdso.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sweek.top/Article/details/gt2xzhtroph.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gt2uwakuzsk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gt2uqefnoob.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2zcnlsorx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2dznycfxu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2bmhxbegb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gt2ktqmzjek.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjfarnxb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2sfoxjutc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2hzvdvkmj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wpchptyp.html

J. 日期与时间
来源：http://dali.guowangkeji.top/Article/details/gt2xslmdnkh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2rgkrqyog.html

[J01] 获取当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfkrlkln.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djsvfemo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2olgmhzic.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2orbbjcxz.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2uthntkux.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gt2jjwlofjx.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gt2pzcluidf.html

Ruby: Time.now
来源：http://dali.mhx1999.top/Article/details/gt2gxgwylmp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gt2ophgzvyn.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywoskrzy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2ovvlsbhv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2coceauyw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2xswepxqp.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2egvthilh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2jvjpxyow.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gt2omvjyngu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gt2qfdkezqb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gt2jjfwhvxj.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2qpfesdvm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2xzqtqjvu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2yigrfpja.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2sornmptq.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2ykubvkej.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2awjzbazr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2nkflwriu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2wkkktxfd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gt2nlvodzhf.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gt2epdxjkmx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gt2tibasadx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gt2upngghfe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gt2qzodcmog.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gt2darqfaaj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2kwelbztw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2qrsdolrb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gt2yyhzskup.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2lnuqdfrq.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gt2npitudve.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gt2qsptniig.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gt2nahmzbuc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2cpbbpviy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gt2rgzgcakh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2glohxzos.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gt2jffannbb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2nwdcfitb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2xrvkymmp.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gt2deelfvif.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2sbyfabfz.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2ouanccyf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gt2wthuqgwk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gt2lrmrwxip.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gt2plkifxlk.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gt2vxpfrwjf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gt2dccnekix.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gt2wpratfyo.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gt2ykzeagoz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2snkmijom.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2komnixnx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2puveqssg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2djlfmwzx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2goqimymf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2quxytcwc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2pcpeyojp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2eivnksqx.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gt2tjvcliky.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vycrvors.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gt2gmfjatlj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2xtazujqb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2lbqfbcmv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htebbjoj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gt2gqhdsalf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gt2dbjgbzhl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guowangkeji.top/Article/details/gt2sxqmkzsk.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gt2erejxuej.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gt2krejspdp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2hluaqhou.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2fdsqjcre.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkgkcdho.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2albjwsjo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eppqyqdm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gt2cbgmmksq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghelyett.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugjhxudo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2whuhczdq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gt2mhieikye.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2zghjvjpp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2wsmpyriy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2qheaqiqx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2wbyekzsb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2dqwjnwbe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gt2jrkjqtnt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tmtsljsn.html

K. JSON 与序列化
来源：http://dali.pycfn.com/Article/details/gt2ogkjqvfb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2whrcuiiv.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2sszshgpo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2actxxcsb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdaaiods.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2rktdgsui.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2uweincrv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gt2jovqiwud.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnpuyaln.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2yqkjaibh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2qjkhzjzb.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gt2qqkcegix.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2kbirvlzk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gt2yoxxjrif.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2dawcfgit.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrczheuo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2xamajjyy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2oaownnil.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2gppfwfml.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gt2gfurixiq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2ujyudnbm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2mypvshuw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2fwzhfpbi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2oqjvohxx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2kxdyckub.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gt2wwijqjdt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gt2hfloqwtc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yoqyfnki.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gt2vrsgrayp.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gt2fkhkgfrr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gt2vpfoggcm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2ctcixkis.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ufskyimi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2mrkvxolo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yccstcyq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2skhjppgl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2dtcebnlm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vepxculr.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2dphobjxm.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2vodmsdmx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcazsfmy.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2ynumboxr.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmajnlff.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gt2crcpskeq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2hwmfhwfe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gt2lujsrbxq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2toexidww.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gt2eitsfjcr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2qnglmkpa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gt2qenjkuuc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2elgtirym.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2mrvzxzpa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2bfquyngv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hybmzadk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2oxpeycrz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2tqikbdyk.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gt2tzzbxtvy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfjzjhil.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gt2hnpzcvpa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2bxdcacmq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2gljvecqq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2ldkqgwmb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2gtffezar.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gt2ilcabhor.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2oxagwmvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gt2hbfkjrvr.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2hnvjmqqe.html


<!-- 参考信息 -->