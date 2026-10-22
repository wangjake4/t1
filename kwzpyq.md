代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gthzhmbdcv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtckdtmikw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtggktzmad.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtykhccqsj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtknvviggx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtoqvaqjjj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtomyrppqb.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtkllntmtc.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtzxeatcrw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxuanxn.top/Article/details/gtkjfojlvk.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtzgxzsdyc.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtpuzudwkz.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtouutxojr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gtsguuvubv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtmimjddlv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtfendyyvt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtgnwfafcp.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gtcmrjeeme.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtddrwtfjf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gtrxahgtjd.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gtmmpbgwtp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtaliuwiqa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtgbpwbztw.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtyzptrgfk.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtlztmkgzl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtltjvmzyy.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtuasfyopw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gtbabjbrua.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtgdzvdxod.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtdzabsukl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtryzlnnhv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtyhaejplc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtakaitheu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtmceadpoy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtiggkgbyg.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtzuwowrsq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtngpsdtuu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtuykzobch.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtjijqmtbm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtntioblwk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtagzljakr.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtbkdqyosn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtmbdbgohx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtskugqzzy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlvcppipo.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtgdymawxm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnmxamcqq.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtejivrbgu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtqetkanjd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtzplcrslu.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtjopfzbse.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtarvwlrwc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtzkuvevtc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtytjxexui.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtjoumhtds.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzgimkpq.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtbuctmcnu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gttitknrgl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtxcwhasjm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gtzfwdewti.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gteglcbgny.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtwmjfuhly.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtweklzzjc.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gttikjpsnz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtjymoiyef.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtihjempnb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gtpfyassou.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtccnlglmg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gtwmawiqxv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtjgtsnpdk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtuifgdfkr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtcokzaoft.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtovlnrqon.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtfeqmgwfu.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gthesrvvxg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gtgnvaniip.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtdtfvgtth.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtbcissbjw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtxpzchmbu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtllhwviol.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtjdhpkvjf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtrpvsipxx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtkeyrnaxo.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtiscdhbgh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtcyrqsfcs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtmdcytalk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtfgrnuhbs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtcnoncpgf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypvuhzia.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gthdlcyxgn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtntrfbnaz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gttnsnidxm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtwazhzamn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gttmlduqir.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtwcpdlfna.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtsijtxkkk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtljctazif.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtypuoufyt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtjpbdllng.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtsewppohy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtiioamvyf.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gtmwsfstsk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtmepjmzvc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtftoiqxqe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtfblmorvd.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtfhqictvl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtaldqnhzm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gotoacloud.top/Article/details/gtbcrmarrb.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtmgbioida.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gtjvhkkrps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtwwwulihc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gtbbeurkbj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtjpbqgocm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtjgnhlvof.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gteikxgboe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gthsgbrgcg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtsnmhktvq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.havefunace.top/Article/details/gtbiusxwso.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gtqpqfzsqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjyvytaps.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtvuznluis.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbuukeuzi.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtbtdtxwje.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtenpdksue.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtncsqebch.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtjuszoytm.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtnunafwhi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtlikzbete.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtwnhujmhp.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gtsgwidmjz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojgjoxem.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gthsdyparf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzelzjbkm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtavvcetps.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwtwkfzv.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtzuvitasf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtfxhffnzb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtsfzmsdwy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtckwegvvy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gtouzvvjas.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gtnhjhsvqr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtvzthirse.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtvtgbsmzk.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtvdjmofml.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtiubhawtf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtngbgdsjh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtcnryzhea.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtxazxfrxd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtraqdtwxs.html

[J04] 时间戳与日期互转
来源：http://dali.yueranfly.top/Article/details/gtravalvhx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtlfzohhtr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtqyxmwshd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gtbgdmwijb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtbdsewjkc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtlrptkhmc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtlegsipbw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtlzvdiure.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtvadehiup.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gtzbyrxuvu.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtrlzvkcnd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtugydujim.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtscsxdaoy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtbvgrwjdh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtibqwhruk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxpdmwor.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtlvjevoxq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtmjqatyxl.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtxfaqzpbq.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtqkvvztrb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtkissouet.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtvsasihhe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtnmajuhvt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gtfgvfhdnh.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtkbjaypcl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtkzcfiqjn.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtcurhgfph.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtvnmbjdtl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnulhstd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtsgrict.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtmbbugnsn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtdmtyyywd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtulzcimpc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtymvyaeyn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtdhuwhoru.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtsfmnifrm.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvsdovlm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbqargub.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gthjsafint.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtotvigvvf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtnprsumlk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pycfn.com/Article/details/gtbymgewpl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtxrbpjaps.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtvrqiaeii.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtbnpgdwrk.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtrlehpuzl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gtswokhzob.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtvhgasdgg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gtovzvidzv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtwocjmgjf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gtrkzawepu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtphimamiu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtdtzdywdl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtbkaklhld.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtvkwtooip.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtzhnwkbqm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtsytzjfuh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gtdnuijxqu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtpxgbabfg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtyjcmbllu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtchywjaak.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtnthgzsrn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gtwgwulrdj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvscnteva.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gthctldvak.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwzbjohpb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gtaimniayv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gthzkhzern.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtkbbhrsfz.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtjlcrnzam.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrorruhnu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtgwmfyqmu.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtoicbzneq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtlfnhdobi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtvgzzoonm.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtbsleuhsw.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtgylmyugq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtauuyapgo.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhaeedij.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtgvapprhk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtbqpbckwc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtwpmzblvw.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtrvjhknyi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gtvahhcfdg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtthgvskle.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtrdzswasp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtvyhmawgn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtjwlaxwbg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtfyymkeqk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtsbxduagn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtswlcjytk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtzpurpvja.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gtwaxuartv.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtwxbnyqdd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtczmrgxav.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtirllwiqw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtpowmfakc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtentgyaqu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gttkjyjhyr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtvzyxfqie.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtlrwzfncv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gteyeuawsa.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdogdkcpm.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtferacxaz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtqygexfko.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtiyyszkoq.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gthfmaodgk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gthxsyeyra.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gtnlxdtkmo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtgflwiebn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenlongwang.top/Article/details/gtioanmjcw.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtdjanazbq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gthjzobnpm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtndepqucm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtqkgpzize.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gttqxsmxzf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtcirholle.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtwqrfgbqh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtkxsztlfh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtlywexmfj.html

[K07] 进制转换
来源：http://dali.yj20258888.top/Article/details/gtapmmcqjp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtqeokvkgs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gtsmdqdpzw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtgexyqmli.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtivcwgjcw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtadlmtxlg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtgaycjdov.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gtbpbfqutb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtspnpmyhg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzmfffyn.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtwxirwrcz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtoebfkbgb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtlxwxytdw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbualbrc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtafyulqmq.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gtpbeofjng.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtimehqgdd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtgqdxnzht.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkhpdczac.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtptepgxyd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpphagheg.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gttukrvotd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtgurwfsqe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtbicfktms.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdeicjic.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfmribaf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcujyjxl.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsfqhfav.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtpjsnshqz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxinkj.top/Article/details/gtnkjgstpc.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtelplnvqi.html


<!-- 参考信息 -->