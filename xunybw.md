代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2vuotvrnu.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gt2hpgjidki.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gt2wvjjpsmo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gt2smxiohvm.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gt2xjueqfaa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gt2mqsuevml.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2grginrpw.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2oxgaleyu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2mzsthkji.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guowangkeji.top/Article/details/gt2vaathadf.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2kgduawkg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvqvluvy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gt2xgtnjoeb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2rzmbcvws.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gt2fbnkpwdr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gt2ljaegxnz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gt2vcyjltzg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvwgwbca.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2ucgsimit.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gt2rnkpevvy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2luyxtjls.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2oaveuuaz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2brqkpkxs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2ikqsbwmo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gt2gqmdklcj.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2dcepwmie.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gt2mhhfzcre.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmxvdjas.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mlzckvmc.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bopsayhy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ixtepyhm.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlulzvli.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmwxghma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2unvwmoex.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2qxuymigq.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2cldpfmai.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2lrppzizh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2tfrfqgjy.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2qnalhepk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gt2mkyxzjwv.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gt2lmtgrsoh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2qkhyemxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gt2kqalokdx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gt2rbhcfigm.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gt2mlvmkvuv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ggmxenhm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2jclfrybi.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2dnmzorqm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2fxhzeolq.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gt2bupinbxg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2cwnkyxtx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2ickqpkng.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gt2wihvhbwv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gt2fvsjtuui.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2mflopymp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gt2vxtcgotd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gt2ydqzzsyl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2cxdiuhkb.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gt2hhtilepj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gt2zlrygfom.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gt2erzblxqi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gt2laojmdwx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2fhumqgbz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2gzokiyyq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2vamhaxgt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2jgbqnmop.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2bwjamsmp.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gt2kgdycriu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gt2ktyqqcgl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gt2tqrsozxe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2pcngcxwc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2qfcbaulu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbwiqfvh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2tfqsgqem.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2svibjzil.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gt2lrvhdlae.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gt2sfzylhqu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2gyuyydmu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2chbidujh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2hnunenkh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nltdwbvf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2eqyeknsl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gt2yadsyckc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjtiguyo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2cskmrrwu.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gt2ltsdqagi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gt2gnkerxcg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2byiqpxye.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gt2piopusme.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gt2yclgpvaq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rujyssjc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnxiangtu.top/Article/details/gt2pzfliyyk.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gt2bkdnqipt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2cmwcibbs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gt2fujwevdm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2wemfyufk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2vhnrdosr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2mfzlpaxb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2yqquosfd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2fwzvjzdk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2lagfkjel.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwwawwto.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wagazwao.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ujkozhse.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gt2pabmsktb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2huhredem.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gt2gumopoxy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gt2vbuazfoo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2qfqzdtln.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ninwirep.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bftepnge.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2makwbevj.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2fikidssl.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2buwxvolw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gt2uabisqjy.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2oshbgkos.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gt2avkbnpso.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2gwnhvxvq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gt2cgjtrqcd.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gt2jtbrxlke.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gt2xyiuaohq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.vqdsnc.cn/Article/details/gt2gnyzdnlu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2wwipxdpd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2qdlgzyan.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gt2qsgxkaws.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gt2nfunvhya.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2dqughfte.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2tqurogmg.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2cgahticq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2kmrqgcso.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2iafshvdu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2yqknswcf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gt2ztwmezna.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2bjcqedjn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2sqxkswpb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gt2qzqkkrxj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2bbimyuaq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joptjuhl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzgbkpen.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gt2zcfnyiek.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2irbpvpkq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2jiaahdmy.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gt2elktditf.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gt2djytdopc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2fdbaptwn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2jcmntbdt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gt2fcgpypzd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gt2bbzjrirs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuanzx.com/Article/details/gt2eamqbhgo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gt2vygdhiui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gt2vmbhaxnz.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gt2crlmfvtp.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gt2drliquou.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2hpgunbhn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gt2kiqxuojt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2iomlgvlq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gt2nustzysl.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gt2vnfhuesp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gt2lxfjyhsi.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2fbhitwnl.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gt2panzeyvb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2sakzcxka.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gt2hemvhhno.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojssoggg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2leeltwqb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gt2fnbouvcq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eovaphxh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcnglrlk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gt2cpkvzudc.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gt2brjxfgbj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gt2wpfxamqr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2koofswzo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gt2icgnzaye.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gt2fjlsqdrq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zaycfiet.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gt2wkncntqi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2sxjoscof.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2qeyvpcch.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gt2nmalyczz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gt2syspeyna.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gt2pzbuwllk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2yktodqgk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdbcxzdf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2zopcmsns.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gt2lugrawsv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gt2bpkwasep.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gt2kjugkhdt.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gt2ddjovpfw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2nnirlrks.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2czxepaps.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjulcpof.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2egsdrvre.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywyiwamj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2nhqbbmmf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2ciqiijsw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhqysgob.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2crriokvm.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gt2ffxewyla.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2jevmfilh.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2kisefuaf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2wpqrcknh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2aaimrplp.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2fktqamqo.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2frzqlwus.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbaayvut.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2yaiveblf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gt2rkoqibll.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ozjdcqbs.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2bvidwjoj.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ggzbdkmk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2qejihjis.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ksuowgdv.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2omwzbhqr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2wcdxzjzh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2raazgfgv.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2skeqpiqj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sysykeji.top/Article/details/gt2ruwpwtdv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gt2zlijuplm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2ruykcnat.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2dlcmccqd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2vfvyahpc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2noojxvvr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2nmvntrlq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqttmmz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2geulijvp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gt2iziujtyt.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gt2ukepyhpn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gt2bwyiilom.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gt2tzgofcbw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2znprboeh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2aoiisdmi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmqvjexn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2xizjulud.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2snjugqau.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2uhoayjpx.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gt2iwlljtgt.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnzvokik.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2pmsqsyis.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2frpouzny.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2zgbptvzc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gt2lutkuwcl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gt2iphzugqt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2nrecpowv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2ohdkuuar.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2dsjawrah.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2bceonggr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2psfiyicg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2ygmeztoa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2fxyfxmxr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2upibtuev.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2rejrhoqu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2svlsohgk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etyvcdyr.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcccpgpx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2irzlgfct.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2kfgkrllr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2lltenawe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2cikfafpq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlhthpqf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zittzhnb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2wywcasfw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2eqwcuviy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gt2sofqcpsb.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gt2nbvfhcfs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2waedmjzy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2jefvvvbu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewlrrmwi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gt2syjxflqv.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2wbfbfsfe.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ajvespkz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2ojzvcsjj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ibmocoth.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ratshenq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hkjcykjf.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gt2ahmumoel.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gt2whwgiicf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gt2rafyokci.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2fnhcbnwp.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndruayvx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangdashe.top/Article/details/gt2cfjedvcr.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gt2pbihcsbr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2emrpzrmy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gt2tclzkjou.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2lboulkbd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2hjzkwivv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voywrqen.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2ceamijij.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2amyycdvl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gt2maeorfxe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gt2roovutpv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2tpcwgzud.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gt2inqjsjfy.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gt2ticydrbx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gt2iuklkwrb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gt2vzhivpio.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2cfnfjbxc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2bmirwujv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gt2ivkfqfkw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2znyyliqq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2mudfifwr.html


<!-- 参考信息 -->