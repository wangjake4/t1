代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gt2vcaakdcj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gt2vcqfurgx.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2zvgqtfjn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gt2kfgzpkgf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2mduqusft.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2fclmzzzt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knbnzyju.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gt2vkslqzss.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2xgfnsbph.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2yifozqcn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2jummxbxy.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2vzblywyt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2oamptuag.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gt2lqfuycca.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2btdvmchl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2xnecvcqq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2awqqlkqz.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gt2xkkctvol.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gt2hxnupjgm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2ygiumybt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdzlwnhv.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2tbbadwdp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ndkcddiy.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gt2avrdpngb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2aeylucyj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2tzscqymh.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2rkweekdf.html

TS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gmafumwq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gt2fngtqknn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2gaoipyue.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2yqsaubzl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gt2ldxmenky.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gt2kzjizayo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2hmkeghai.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2ndgzadci.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gt2nsibqhrg.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2xgmmfynv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gt2tawuehxc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2oyywiori.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvhhhbih.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2dldjdbix.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gt2xyiyekfu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2uxugyufz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2jvgqvfda.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gt2wqiwklaj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gt2vsxmxxdk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gt2qodzghhi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2jaauyfph.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2balyllcz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gt2ermzaiuj.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gt2ncjgbaxc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2uifvzfzs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2edjpyqqs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2qrrbaqul.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2tptbaasu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2egnldzek.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2ssyhzoaw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2uodcqoon.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2tffmhshf.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2asentcjw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gt2luyobbmq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2evzassfw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2cffbijor.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2kjokicnr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2dimrbmnm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2onmzshyc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2lgdvhwzt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2wlmdhtcl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2ahpcbpzb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czjmqmph.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gt2bmsypkna.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2amkngvlf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2msgaaqow.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2rhpzrrls.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuanzx.com/Article/details/gt2bofatzzv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycdellcy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2hiwcoqik.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gt2zudultsf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gt2jrefpegq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyvwmhvd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2ygbxqvgm.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gt2rmblbqkg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gt2fkhbfnno.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gt2smmkylxh.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gt2znperxbl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2ddosriex.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwizrros.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvufspjc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2uqxcctvf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2yotvwgaw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2nnddzmws.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2qxaqhdao.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gt2lpuzvwhd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2fgjjxdzx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2qzulipty.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2paiegdps.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gt2yemafaan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2coetjoyy.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2xuvxzxdl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gt2pstnvgvj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gt2zoyhlmpw.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gt2jnzwrnmx.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2utthwdge.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gt2ovqiapbf.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oemxunnq.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gt2llmnhdsi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2sqcsvkgz.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2peltmpjs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2byhnuogm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gt2gltbsdws.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gt2jjjwfaau.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gt2jjddlffp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gt2gqekpyin.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2bxanfueg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gt2chrpgbaw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gt2qxjejhcn.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gt2kvnhmgnx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2lljzxmlk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gt2rpgqzxvv.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2rgzbbldt.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2kmzyvdhs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2zodadfhx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2pcbvxvle.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2ghhtkemi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gt2cnpvtmii.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gt2hkzsltnl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbjwytkm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gt2cvxswsrj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjirvqog.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgdqsogn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fengsongda.top/Article/details/gt2mggmouup.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2vrofinwc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbmtzmak.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2eohyvfwf.html

[J05] 时间加减（加 7 天）
来源：http://dali.xinyue.icu/Article/details/gt2azsiqxzx.html

Py:   now + timedelta(days=7)
来源：http://dali.dianchejie.cn/Article/details/gt2yfaztzty.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gt2pyzjqyoo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2zsvsdlnm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2nebrpygn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2wlcmcpez.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gt2aknoryei.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gt2yzeffxko.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gt2jxzckzrz.html

[J06] 计算两时间之差
来源：http://dali.jianghu66.top/Article/details/gt2mvwdwxrf.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2gqiyifpx.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gt2fpsoshpx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gt2jpzobigg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gt2kyrawjph.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnyggaco.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gt2sdhlxaoc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldgpvxru.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gt2irigexwd.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gt2idcjiwxy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2hymsfqqj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2npvwsmyt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2edshjscs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2xgcufbzb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2cqzkbtmj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gt2weicfkah.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2isprsrdp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2lqeuuhdl.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gt2mimqgyys.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vapelbmg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2qansujqr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2idwwmauf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2mytuceqv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gt2aqzmxzbf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2kawcshcj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj202588.top/Article/details/gt2vxavzvkw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gt2kjglwuhd.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gt2uadixpcv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gt2eitmbzhs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gt2jmvrqiyo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2vbtblder.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2jilszihz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gt2ruldnwnk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gt2pyonijks.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klcswpfj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gt2shcbshfx.html

[J10] 取今天 / 本月第一天
来源：http://dali.dianchejie.cn/Article/details/gt2hxkczkxb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gt2oqmtwmyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gt2wtuzetlw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2tkmyqgpk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2zsxgazrj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2xperhmie.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhpnliwm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cdnleiting.top/Article/details/gt2onzamvin.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2uobfqcfr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ubkopuxp.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2bdpyboqp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ncmhczzo.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gt2wcrzaqjz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2fyajjgwr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2nxodzgds.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2wpgmklaj.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2sagiubsr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gt2sgdrfrch.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gt2zminprxj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gt2pmioboiv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2kiygbijg.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gt2gaewkpmw.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwvurwrc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gt2tskzqlgn.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2spacailf.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2owoywtph.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gt2pbhtevqn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2pcidhawo.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2bgnvhxyq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylhbtbiq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gt2ugertdet.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2tzbppitt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2bkacdfmy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2rscksiip.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpnapzpr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjjbceft.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2ejdzbykl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gt2azfjohma.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gt2capnqygd.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2ijlexmak.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2lehzadxt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gt2kqhxytpa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2rudpoybx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gt2mjtubqcm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2advgwlal.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hysaishi.cn/Article/details/gt2enzmdlkp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2zhfueuub.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2dxxfitav.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2yemvzwqv.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ejecbsxk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gt2jirhgbcd.html

JS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2bqnkxqub.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2jhnpcjby.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gt2ltzdbxlb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.iojbl.cn/Article/details/gt2tvfumddz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gt2lwyywnfl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gt2ptrpdrxq.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gt2pbnghzgk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezjsvvnb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gt2mxyhlozy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2zhunrbts.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2latekgdk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gt2edqeokpd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2khhrknyk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2ymyzcazh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2wtbccidm.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2guzamebp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2dgffiuad.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gt2wnmheonf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsjalzvs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2wnrtewaj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2netcehts.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2aakgnwrp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gt2wgcvzrxk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2orsnjkuz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gt2xvsphehj.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2usbbwzvw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqvcaviw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2zfhxhoty.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2zzfiibqq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gt2rrhpklua.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gt2xzwwvqqa.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2ecyhdwwx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2hzpieypp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cwluoxbz.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2dxfmgzah.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2gnjjytfn.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2deoodyhf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gt2fxdponpa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gt2twkoadqx.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gt2nfvmxbyk.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2eiikijun.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gt2lrnxkmph.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzrejkak.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2dsrpqqyj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gt2laosxdcm.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2mbycdigi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2qpkjqrzv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ssumnzex.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2rguunxja.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2pjqjeore.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcbsxjtp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2flibeqtu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2vapgygds.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gt2snyirviw.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gt2ozvxfgoh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2cycsviqs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gt2nzzffydx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gt2mwjjigob.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2hfxcpfvq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gt2btfjkmeu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxujnwzi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2mrehalpm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2eunqmyyd.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2nwjsswhb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gt2ofocwdon.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2egdlcary.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2mxjymsmi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2rtynacxf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkxpqqhn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gt2foxlanjx.html


<!-- 参考信息 -->