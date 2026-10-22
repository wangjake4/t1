代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2yavpjcsm.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gt2cxkjoltl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gt2fyxjgrcu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gt2dcmsdsau.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gt2ebnjybej.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2xvsebvsh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gt2lxzsiaxj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2qznrxmjt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2llquawms.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2vdzwtchn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gt2rdwgysdj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2spsvhsfy.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gt2aptydpgw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gt2hgamgdbk.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2pjnmmpen.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2vhqxtoxy.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2tniyhzfm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2uwbzyjqr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2ytucvtes.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2ukwmxtsi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2xkswiunq.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gt2znvcfgkk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2qsklohhu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2ovwrguqk.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2xgglfsly.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2witclcjb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2njnkuspf.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sejsuxpn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gt2qugiydfm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2kfzocvdq.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gt2mumyyhsi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gt2pmwrfcpc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bktbvwor.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daxiang520.top/Article/details/gt2pbyolcwz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2umcekcvi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gt2bqmaykec.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gt2iiicjdsk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2kehszxht.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2brvurtbd.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gt2fkrdugvx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gt2wnlfqmfk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2ejljopbh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdokzdim.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gt2poqrqjqk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gt2qdiwyrtz.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2fbmpolsl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gt2cadgjunl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2xmatiuzd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qxvydeym.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gt2eypjrpjo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2junjnyht.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gt2mjfwzcee.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vsatfojw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yonumen.top/Article/details/gt2jtkzjsnr.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2fxvnwxld.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2ltmjihgz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gt2xejmnisp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2mmmyttoh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2vyydpnec.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2abnmdkqv.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2qbpqpety.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2iqrbwphi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkhiixqd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gt2tsfdmgpi.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2wzirqfsk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxjbphqp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2wbtpjsqw.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2skesjmyl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2wdpwuubr.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gt2ejudqbch.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gt2gumcjlwp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gt2jmpaybvl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2udlwgaja.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2kirczfru.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gt2veanapla.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2dqlsqnwo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqnypwl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gt2sdluyfkw.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2omdflkzb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gt2lgsfbncj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2ivxstrfm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2hbowmxro.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2suufynfa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2uiazmfke.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.iojbl.cn/Article/details/gt2ayreaovg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gt2xobeyfjo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywnaxwrn.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gt2qrvnzyuc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2janiintl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2bnlfxdoi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2wyuiloue.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gt2fugffyqw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2znxshymj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ivvv.top/Article/details/gt2lesuxbtu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2yburcgev.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2dtrzcltl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gt2eaaxmtse.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2jjdckxld.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2rkytapyf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2nitwhbcr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2lgnyiuye.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2xebhpfvb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gt2toqsotaq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gt2iktdsqds.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hijtsblz.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2waspnnzz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kohvjjxb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2jreolisx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gt2ernnaxxf.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2ygrpgmzc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gt2swgmfejj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqixtbk.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gt2uyrvuhzp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gt2arcqmrld.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gt2jqabghda.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhcljajl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sapufyrn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2lebcuabe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2eoxsilyd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtiahbzn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gt2xrllzjtt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2xfpszdpv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2sachpquq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2cgboemgb.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gt2yqmxjwvp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jfjdkeqp.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gt2vjwkbgka.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gt2zcpzlfll.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2fmlbuaka.html

JS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2sgpfmryr.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2yvpskved.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2eafjhluf.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gt2coqjlrkq.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gt2goyauios.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2eigrsxrb.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2xltgxadt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2irlmgryc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2zrdjyywu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gt2fyqvijlk.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gt2aebcmkfp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gt2kysliboc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gt2zjfuivrs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqnukpsy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gt2jhuynlzz.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2ieofkutf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rerrkpvp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gt2vashobum.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2wdciawvz.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2hpomjshp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2yhrfghhy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2dvoyxajn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2fuuzqevc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gt2euuqiohp.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2yfemzrcy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2ewvpapdr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yongpay.top/Article/details/gt2fybbqpge.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gt2qeidrrcg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2vbgpbvik.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ybcxt.top/Article/details/gt2dhnfkxqe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gt2kcjojzyf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2yiobjspl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2taprmcvb.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwjfdhph.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgupfszl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gt2zfrsxwvs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2eqbhoqvs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2oygpnumd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2iyisxmkq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rloztcqu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2grgxzmgz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2vwrlphrk.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2ncygixmu.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nunkkvfp.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gt2etywadfp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gt2lcouwwwr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugdahukt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gt2btebgjcu.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gt2bevhxpmq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2rzmgyqte.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2tnrjcrrj.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gt2iinfflgl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2eyspjptd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gt2eerjuhhy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2munvxbaz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2vgivpprj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2ytclqibp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edifmprb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2bvinjqrd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2rreocxnm.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gt2gxyhpaic.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gt2qligmiri.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2leuhsdtx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2lszoblte.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgfzy.top/Article/details/gt2nxxhjwvs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2tgwotomd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2duuwfmgy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gt2pqlhecag.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gt2knmpddik.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2umkhmxov.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjplgyxd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gt2dqeixduz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2fshzjvds.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2psusodiu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2jsjfffrm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gt2hnmkulxl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cheryme.top/Article/details/gt2crnlpvwr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gt2dwxgrffc.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgztrisr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gt2fhtonuup.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gt2eqvhbryy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2wmponoff.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ajfjyeza.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2inridjnm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gt2dnjnwlwy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gt2qveultyp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gt2gepytxjt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2cztiyyxx.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gt2avcxghfi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2tksqasxn.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gt2heqqdwnj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2bxashqkh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aivwbmnl.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2xiaarkkp.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2dkrxgwnz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gt2yvlxvhlf.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nozvbvuu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2etzwfiax.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2aikkcasw.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tklnmjzr.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2rbntjojo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.andypj.xyz/Article/details/gt2uyqmqyui.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2hmxnkzaw.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2nbsjphyg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clnisbav.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2tzxobzsb.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2feyazkza.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gt2vwcobllr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2knqxvfda.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2kwmqtxju.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2cvylkqil.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfnbecqu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2dwzskinn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2xalcmuie.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2soiivtyf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cheryme.top/Article/details/gt2pvsqmvek.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwjlmefp.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gt2spykwzqi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2fuqkblpn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gt2efztkaey.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2cvfnwapn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2pylndemw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2qdzdrwnm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2esdtnwpr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2bvlebkbj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2ayuvdanw.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gt2okyztwbg.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2goccgbml.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gt2yqftggux.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2lgijatfm.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2ulheekhl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gt2vgqnwvuc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2twhhlxbr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gt2ginqlehv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2nedfsqpe.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gt2muhidcoy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2xvyubdac.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gt2abslprrt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gt2wxecgduw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwapnsup.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtvlzbd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2obzjdrzj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2krlcnyqd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2zlbwlgqm.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gt2xdzjvnms.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2bwdfzqrc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gt2qyveznmh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2opphgzts.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2utzpdoyg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2cwaslknc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gt2vqaweece.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2uycduroe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2lajuuhha.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gt2qhzoroso.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gt2wzyqayuj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gt2lorjwmxo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2kfqgiqqr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2fehfqmfc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gt2bcxunfbq.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gt2iwolocim.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2eshstpfp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2zlrheyqc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2olhjyzeg.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gt2rjzyjeai.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uixaaulm.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gt2dwplsnmm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2iokuukeo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gt2xcwflhry.html

JS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gt2bdcptlmc.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2hyxwxocl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2xikclarq.html


<!-- 参考信息 -->