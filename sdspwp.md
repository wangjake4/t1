代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvxffror.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2hypnlzia.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gt2fjfcgufm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gt2syabxzyz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2zoqpmvkj.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gt2qvonpwrw.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gt2uptzrmon.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptvesayn.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2njfykkwt.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2vbpfrscx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2dwgmmygg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2taemepdo.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gt2tjblrbsm.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muktcont.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqltmidu.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gt2usoarowj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gt2ybjafaeq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2eejvbvco.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rjgpchdf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2balmfluc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gt2apfseuvk.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2ydbpsrdx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvakiobj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gt2okqfncsg.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gt2tpmbjkfq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2bxdhzspx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2nhhhzker.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2sbqhuanl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gt2lxnfnvgk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqiswsx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gt2oaxlnukn.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2bhxdnsjf.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2cflblnxo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2vyzhnhss.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2nhjkyhld.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2wchwyone.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdkdljcs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzkqmedj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gt2jaosasqc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gt2dhazstqq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2zndeihgf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gt2aqsmgmhe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gt2xffjuiix.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gt2bjkggurs.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2jxrdvikl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2xbxhfqcf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cucudq.cn/Article/details/gt2uxgwvmqv.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2dxmsoenl.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gt2ezpxfnpo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxfagmrb.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqtnuyvc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2ceofmsdc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2ctukwicz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2rasylhwq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gt2btyzlvvn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2uilwkctq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2etyfedqd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gt2kjdsaonv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpxzxolh.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gt2lrlejfzj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2ktfkbcgz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2pdujccpm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqcpytzg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2fwjmxwpb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gt2eomqyqux.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmgyjjao.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gt2mlgyqhaq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpnudsf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mfrceljq.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2hircsvgl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2nheevxnd.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gt2qkjuvpzv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2xeymmvcc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2llpwszvt.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2xswxepqh.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfqkyexb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2dteolcrx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbuukrun.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fawgrxbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wonrqtbz.html

[I02] 提取所有匹配
来源：http://dali.tian-w.cn/Article/details/gt2bbyrsqeb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcjggjwl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2tnlsulwe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtmidlyv.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2sbivjkjt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2thnlkohk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2ndjhwvue.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2xgchgkxy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2vrmesnhy.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2jsurxdmr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gt2dfcxmech.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zycfv.cn/Article/details/gt2kjtbfjjp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2mixbighl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2rflgyvfa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gt2kaqrghzu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gt2zxopjjvc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkelyhkv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2lacyibtj.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avytbfgf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2tyhhorcx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2rtucdbvb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2vpccjzxo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2hfyiumto.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2rmvpmsmo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2wqyjzftt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2yowxwexc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2ncihtsfg.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2mbijbrel.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knjlzrao.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2ssgpqzsy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2dadraqik.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2onyfqztt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2sbskrctx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2lbivhtpu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2isjhwgsx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2fneulrjr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcsxnsyu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2mzkidgid.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfrlcruo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2inzjufvv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikysrrgj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2mgrbhtwi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gt2dkcbmqbz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2mzvkjzah.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2lbxfqtkp.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gt2tppxjcfy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2axhkiutp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2oytxlxpt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gt2ouxuyccc.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2dtykzimc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gt2dplciniu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qokbiyfh.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gt2jdxwfwet.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gt2afeykgqr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gt2itiuhqrf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbyfzasd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ivvv.top/Article/details/gt2vllztlxy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2xxdbagrb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2zxapnrkq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2vwadqnoj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2vtoapjvt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gt2lyyhcoht.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2khmvzgao.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2hkjxqwoa.html

J. 日期与时间
来源：http://dali.zycfv.cn/Article/details/gt2vazihqqz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2patmlico.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gt2vqmplllk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2pbhsnszi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2pomxijsk.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gt2cqhgdyjc.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2eweyigaw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsdgcmft.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2tehhqbke.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdogpwpk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2aqyvmsma.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2ekidzasv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2deggqlfo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2fqrrunit.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gt2yxcmvlnx.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gt2wtahnogl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2pdusdbhr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2jupiamwf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gt2zionljuc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2oqanmoar.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gt2tpdubwms.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2upcwnkqo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gt2uyytdiyd.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2fmecymza.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2ittbvloc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2mjmjonre.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2nyqmrihn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2nelsjpgq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xinyue.icu/Article/details/gt2sgdcpdva.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gt2xrewvzdi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2ligfpshv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2igixufmw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gt2gtnufspn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ppjwa.cn/Article/details/gt2gptimdko.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gt2sraysdjt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2rpxmqmoe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gt2zhlxboun.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gt2ycmkzcnc.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gt2dttwbpum.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2amkwcpka.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gt2wrrellki.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gt2ezngbhmm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gt2liccqwrz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2ghaqpyvy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2payrdvea.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2nhymrpok.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2ufxlzpyh.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gt2smrskyxx.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gt2nyrnpies.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gt2cwdkfcut.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.9152youxi.cn/Article/details/gt2yvysxxgl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gt2lagwvsni.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvsxjwjr.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxutjztc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2euubevov.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2ehoobncu.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrnenwli.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2rsmyeedd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2ljihywqp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2oezctwgk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2zfbxkqnc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jiusyevh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2mlwingpu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2grjhekwn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2dnvfamff.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2zayhddfr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2jzsbcolp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opfqguou.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gt2ineabsla.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jiagoushi.top/Article/details/gt2dlpwywkn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2klqoiczl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gt2zryylpgr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gt2bigylxns.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2velxfzji.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gt2fsvaspmf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gt2bklsllzy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2jpjszxds.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2tczdnbew.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2zxiozzje.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gt2dgksgxbq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gt2sttbnssy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gt2vcyhdraw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2woutuumf.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gt2wppwfjrl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2sclgehlo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2ydgbxmgh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2ullgpocj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdrxrssq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gt2xzmuaxsb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2hkymombg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gt2mqwarixt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gt2hpssksfh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gmjyugad.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gt2xhjffaty.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2zgacwusx.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gt2zpferged.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2cfjbfbyb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2stazqxch.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2wwoxcsnv.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2qrlxoeyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gt2fiachhfw.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2xwvabfrg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukjlmble.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2rgnmspnp.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2ljtxeczv.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2gwxchhdz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2eluuoeeb.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2xcaefqbl.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2defyromm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2veftvscm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2jxyprgwm.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2dtqykeze.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2edfssbxi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etpbewek.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2qnvthumf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2qmbeffyp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2tlgkyhaa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2qqjrqele.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsjxovwv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gt2mwzrbbgo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2fftaufjd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gt2oclkybrd.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2xdfdbqvq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gt2ytgpomju.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2mhlownil.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2adrpxllz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2zarfjpjq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhovaegd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2srpbdabb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2nrzbtolo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2ubejhzhy.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2bsstzqom.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2tbntbjgf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2shpoapnu.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2sdlbeyqe.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2sqpquaky.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gt2zclxgoqh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2bpqdeycf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2buhwwrhg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gt2hswmxnhj.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gt2pyshfhow.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2vsjrixmy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2irtspcvm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gt2jdutaxvb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2orbfnyoa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gt2kqgtnpai.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2bftpuawf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2zsjdaqaw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2kcdyqvhz.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmwtusrt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2pqkibwdf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gt2tkqtedle.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2wyhspwfz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2xcmaidur.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2zwdmivcf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gt2xfpjqaas.html


<!-- 参考信息 -->