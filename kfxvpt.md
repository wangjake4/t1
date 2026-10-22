代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2nmqnfrlv.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2cwartsov.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gt2mhmuutek.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gt2ihjzbsam.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2dgofqnou.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2zreeldou.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2lctchedo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2iizjntgd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2ysgkiiyl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gt2uxyypkic.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gt2uyrylajs.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2tnclyvpr.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2zdbduvlq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gt2htebkwre.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gt2cexgmdtg.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2vdzvxdrq.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2tdlyurcq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2hijbuzph.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gt2utiogkqf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2wzobkicb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2jfjgfcrl.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2ihunynqe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gt2smufemrb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gt2ypyhzdhl.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2nnnbirpm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylzracxh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gt2dcuainrw.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2dalybhur.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gt2qsqqrdzb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gt2sbzecupq.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gt2bsllbfyi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gt2gsnfuxra.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2genjewmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gt2cqxaleoi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yangfankeji.com/Article/details/gt2lyioiiiz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2klrusktm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gt2fzxxuwtf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbekrwkh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2nshiqlsk.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2vguxjhie.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gt2gpfenpit.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kekqroao.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2knbezmuw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2iiskiljv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2vcwnmykb.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gt2xupeqyqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2akpefrdm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2tzmyehme.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mmzndkze.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2umtslfbn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pykrwcbj.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2nrtqucqy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gt2cwiodvps.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neqhhzha.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2rvywhmil.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2rudjnnrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2inclilbp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2spaodsei.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvtbnwiw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2jlrozpvp.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2fmdokwui.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2dlbtfmnf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gt2mnhazpbd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gt2tlrlldkz.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2cyujrimy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gt2nrvoiubr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2yqgzlfzq.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2qkeiaqae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlmginim.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gt2wkcxvocv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ujhreudv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gt2slmlgmbw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2bnuwulbn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gt2dpqhrzpu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uelkabwh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gt2uousxyzq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gt2ejjmdyuv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gt2jgcjsyjx.html

[I04] 正则替换
来源：http://dali.cheryme.top/Article/details/gt2veuhxzxh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gt2feoocksx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2tghhwnfz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2yvbyjthn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffblbxjt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2bsclbzip.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2nslksita.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnyunoo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkiiwzkl.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2ozuqsvoc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tbhbxrvr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2fclguxnj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2clucntct.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2mkcskrzq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2iyjuorhu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2vhcoytoq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2bugjjanu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2vqudxssn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gt2odvgbjja.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2nqnqkhbv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2ocqbitfk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2xtttjohv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gt2wnjotjtx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2taogxtqo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gt2bxifdsce.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gt2lwyuqygg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2gcnjthwy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gt2npyglmyc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gt2mhqpukrp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gt2abqzmbfx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrxndcwh.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2coirevbc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2zrdezjvl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mphkhznn.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyyteyzv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gt2fwlsdhxr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gt2yijrygls.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2epxvjgbk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2nztgqlaj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2snarotdj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2jdmcmrbk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gt2tquvgiwv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gt2flefyzfp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2ebxvtjbi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gt2uiotbalx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2lguyuezb.html

J. 日期与时间
来源：http://dali.zdqjudy.top/Article/details/gt2uqsrhrar.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gjjvobnh.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2szaeztvc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjmsjwym.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2ejwxfpzs.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2xeesqain.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gt2ifsyprhm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gt2ekgxbdki.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gt2xhmhmnpd.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gt2xggmqnnp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqismkgv.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2xrixnfol.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2xoafooep.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2pjafixcj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2gdnhdugl.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gt2orhhsqwp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2ghxnciba.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gt2afswreyg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2akogzlwk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjylzcfx.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gt2hdlpudbu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2muajogrl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gt2bzdrmcsg.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2ygmitgiy.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2rvcbaxff.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2aljucnlw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2qkrvgzmf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2pgoldynn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gt2zheezikv.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2lvhtvqeh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2zkpgurnt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gt2yfcdpfqq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2uhlwueej.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gt2yxewjfgu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2ikwuhzri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvrnmbbu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2eerparcd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2vkenighr.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2hgsfmpsu.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gt2zdncalmx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.redwolf501.top/Article/details/gt2rgjrxjjf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2mxdtdgqt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2zwxfkxpr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2fbgqgkle.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdxvqcjv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gt2oxrjmdmm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2dwigmvbf.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gt2kqlgjlnl.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2zitcbici.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gt2ekiapuxi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuanzx.com/Article/details/gt2ztzhbdiz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2qmygzdid.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gt2tqunwhvh.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2bkreupsx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gt2eqsvleur.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gt2zsczqrlj.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gt2kjqatstw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gt2pgzruyuz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yangfankeji.com/Article/details/gt2meelmsdf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2jndfzdfc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2okpzxith.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gt2wlfhnljm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcmhuukd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2qwuhhsho.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2zehwvjmb.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2zichzzul.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2sdasuaav.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gt2yilttqho.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gt2cxbpryts.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gt2fnopufvk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gt2lqmigrif.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gt2zjobgeuu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gt2bdhiwysq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gt2spnycdml.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkobhyzu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gt2pwwnzzmj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cykhpecg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2azbiywcr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2zggesxnk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gt2kzgxknvu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gt2nholflqz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gt2dxvlmhbl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2rhmsphqi.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gt2zxpjiwoi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gt2ddaruzjz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2teczggfq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2pmivhlic.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2pkueafcn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2wcuwybhv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gt2hcgbtgrf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2cfqneoib.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gt2qeraxqnl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2sjploldj.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2pggnxjit.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kmaazjgt.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gt2hbjikzkm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2osoddfce.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2hiaavdmr.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2omomxmeu.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2xjxlpmjz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2tbsumitq.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2pcufmanz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2ifiwilyn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gt2lmhqcnal.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gt2wnuexxqu.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twviltle.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gt2rktofrow.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2sfitmtnt.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2auuyadyg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2szredkoi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jyupkaxf.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ptznactt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gt2orjjmcsb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gt2lrpkivlt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2wikjzcpd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2hjuwmopv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2zfvftdvv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hammf.cn/Article/details/gt2qwrjtxay.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2idbfmglu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gt2kqlmvuac.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2qrgefnex.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2bjppktnj.html

[K04] 读取 JSON 文件
来源：http://dali.yuanzhike.top/Article/details/gt2fqhvqbwr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ielblhmg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2milrjruo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gt2sysiqwxk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2raymmgyl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2qqfablxf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2wqvrpboe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2lkfjzpnm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2wzktjnsv.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2haxtjrux.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gt2qkqkamjg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2pmyppkwe.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2huiduaas.html

TS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbffcdrm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2yelglgtk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gt2gdkavwnn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2cylbmkab.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrnngvu.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gt2bgftfwvv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gt2ucdimlvz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gt2xmvymywy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2blnjdwkd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2aamchjdf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gt2zeaduyeu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2liersdjv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icaxrslw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2etgphdnx.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gt2egcblbpc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2irxsjpex.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gt2yildurno.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2zihzlgqn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2cbfjwyxd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2vvlfpgbq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2rzjdlmxg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2ytzyazot.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2mfcqlxvz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gt2rupqjrhi.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2cxiqdpsx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2szvqfuaq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2xeizcfnq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2egmhgqpq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2fqurmcoq.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyqmjosz.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2iwmsorim.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gt2eiutknpv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jpytgehk.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2bizcnxnz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2felgkcqj.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2qwikmppq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gt2dcratdkw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsnhsphi.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2aeahpddq.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2nrbstxzt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gt2oksazqht.html


<!-- 参考信息 -->