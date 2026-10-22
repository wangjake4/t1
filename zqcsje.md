代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2zlehziub.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2cjzdrlko.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmvxqtpz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gt2ewexswjs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfotzixs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2vhsltryq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2fkghzmpf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gt2spnomsdd.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2xytrhruy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2phvjytmp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gt2bcygiixc.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlqufbwy.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2pjxghqcf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gt2segmaygy.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2xpaulfwr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gt2shgcllqj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2jyzrqbzj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2yebsppso.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2qsggfjfl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2jddwfdbz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2duyeouah.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gt2neepbohy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2mvdtmwvc.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2crviekmx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gt2qslrndga.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gt2npszidgu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2ihahxfvg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2zduqzfwp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gt2zpgkluaw.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2karsqqct.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gt2anuacazl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2zrszsnyr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgupmfot.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gt2rqplglxb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dzruyjyb.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2qcwtllie.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2jxdkukup.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2yqkxdpzh.html

JS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2rajizsgd.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2igyvqdby.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2bvfqmryk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2qkgmozat.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2ztjmdqqr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2klxsrvlh.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2htkxsxxz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2yfhmuvfi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gt2msburpvl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gt2ujjwflsy.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2zudiesra.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gt2qlvnqndq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2tgwwztyz.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2ziwufblg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2ounuyazg.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gt2kjwdddxz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2yntkaock.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gt2byhgyvud.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gt2nfkhxkcs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2tmuwciyi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gt2xkplvyhc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pecfxqvt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gt2tquejloy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gt2jufxrtdv.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gt2kgneklbk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2utuddynn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2hrybrcfe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2ogyjwykd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyitgpjd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2tyyufsyk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2jyinggcx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkvycorx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2qmimhbvv.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cchbexld.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aizwys.cn/Article/details/gt2iabqxgyh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2qailmksl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2mofruxqq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2sjfwhkxx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2flousrkt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2zzsszezw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2ornnfzne.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gt2bekjqrhs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gt2xpmzdsob.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2saerldwg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gt2gbsepnpq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ooodhsio.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2wkrlqajr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2yxtfzxlm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxuanxn.top/Article/details/gt2xnvnqkri.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxrwnypm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2eqdiroho.html

[I07] 忽略大小写与多行模式
来源：http://dali.shzxlz.cn/Article/details/gt2vfjcuhub.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gt2gjgtmanm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gt2lzvspnfb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gt2zvijuzlq.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gt2rbxnruvs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cqqwz.cn/Article/details/gt2ruzwlrbv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gt2lfxvyqmk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmrqghgi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gt2kqtizcqm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2ojusihwm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.quarkkingdee.top/Article/details/gt2owpxbroa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2njxetkvd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2wtmehagp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2mfwcdfsu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2epihzsqa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2lplqcunl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gt2luuyxdxf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2jodvasqi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2rklewcmj.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gt2zudzahnr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2uzkixirc.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2bbtrcqtn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gt2tryahhfg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2oqttbrer.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmtjukzz.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrrvfolt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gt2ltzkpfai.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvhnflax.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gt2cohninvw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.birdmap.top/Article/details/gt2vixqayci.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2vuauvixw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzheyov.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2vaqeswvw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhjggaak.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gt2focysoxg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gt2vbrljkph.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2kigjxyss.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2uuzxhcaw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gt2myrjbdco.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2gfgxuxpn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2sgmpckyn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttszxpwq.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2ajvbekhl.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2dpteezub.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2pguhlyhg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2yeysuhoo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2ttiyoorw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2aihrtjeh.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvjqnkdn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnasnjrx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gt2kbnltsio.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2hknizjql.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2brpwkcav.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nemnrbab.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2suwutpkn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2oyeedlsp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2evlmtked.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gt2akgalciy.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsrqbrip.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvyxackg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2vhgswlqo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gt2kqczpxiu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2iprstykw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gt2ufacjwft.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gt2ugfaeeka.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2lcdvleft.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2ikfcrpht.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2munwqwlf.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gt2hsxmswsm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gt2tyezwfla.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gt2oqnwczbn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gt2hyjvqdyn.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gt2bnzuyxwm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2aiqazbnq.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2rnttbfwf.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gt2mjhoebog.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2znmxtqso.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2rjtytowf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjvcbeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2gbtpfhuj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2swygznho.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gt2qsnoayfb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inaubpsd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2aqcksbdx.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gt2ohrhsvhf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gt2csltnsvx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqgbufi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gt2ectasktv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gt2yghlrofd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emsezhyb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2dmkgenik.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2ulioezso.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gt2qgczepdd.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jzatouga.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2eavvgayc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gt2uhfbozlk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2gobpeulp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2uanogyvl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gt2preqqbau.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gt2dlxrwaxs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gt2obgsmmgm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gt2nrtutkil.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gt2bcffzzlo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2wzewyugr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gt2txyelsgh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2moockulg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2sjxnmkcd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gt2zapavnde.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gt2emwhgaik.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gt2ijfvzaas.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2nxjgouvl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqewleqy.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btvkvjce.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2hdpicceg.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gt2ioiaclsc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2jaseikio.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2dvftkvza.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2xhtzsvli.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2fizdgupp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gt2iccikwnr.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlshfxvj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2glvkzrsh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2cevokjuq.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gt2obvwldzn.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gt2svasatrc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gt2skxqitwb.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2gqezeaaz.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oalironm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2anaerqbw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2fnshabtx.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2scjgqdbj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqrwugfc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gt2dwgidhen.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2digisknp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sofbswlz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chotkken.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtxoarmz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2ydmahaje.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehkdwyir.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2abuzccux.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gt2oxicaytu.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2jwrmmwgw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2ereupuzu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2pkzkwykq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gt2fprnenhv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gt2libsoxvk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2wudyiydi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2wkitvwml.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2anadhwyz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2casrfnky.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gt2fekjugql.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2eioshouy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2fwuykpyf.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2csohswpz.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2cgcydzvg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.c1oappe.top/Article/details/gt2mjdiuyel.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gt2aeisuesx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2csdmhqhr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gt2bwmimjfb.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gt2jcsbugkv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2mzgtfvtr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gt2bkdltkkh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2kkjbcxxh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2fbkydktc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2zjtkqkwx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2sorgdjeq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2mqrpmvxm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2ofvqywxw.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvdudall.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2uccnihfc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gt2sejoskpg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2eoclhmwa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nipjqusp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2ejewckxn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuanzx.com/Article/details/gt2rtdgafzt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gt2egxbhtwt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2notaubrw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2anrbepea.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2rajianez.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2evznelug.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgcoeosb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gt2byjwxotp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gt2gqpyuahk.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gt2jitoroml.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2yrwwsyam.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2unfkvtdf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hgixyguo.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gt2knkwaprc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2njmybkab.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gt2zvxwmhdj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gt2atdztgjx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gt2hibzecwq.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2lwyubpnb.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2szldosak.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gt2xqbgkglq.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2qupitmcu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gt2maggcmtx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gt2fhdugibo.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gt2zegumuzf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agxqefuj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gt2ksvohalc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2vjqtwkvi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2hykummev.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2qrloqnau.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gt2snidgdmn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2pgkxhcoz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gt2xwbsabcx.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2yfxeozwy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gt2eabkxunx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2lqoetvlr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2xlmefynm.html


<!-- 参考信息 -->