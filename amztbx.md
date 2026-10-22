代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gt2hbxnooze.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gt2kgzuikri.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2czcdorcs.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2hrpdijpi.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gt2tgaflwgi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gt2aiyzehpp.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gt2hevlidqh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gt2ptweqket.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gt2hnxnqkbe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2ickpfjjx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2vcjzzxez.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2vyalwjxs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gt2zphebsxy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gt2emhifagc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gt2yuyroued.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gt2onstjfhf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2mzimqynj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.svipenyu.cn/Article/details/gt2wyvzaslk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2xmiacpsm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2jtnppzva.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.mhx1999.top/Article/details/gt2cxsatkyn.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gt2erhpvmte.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhengqikj.top/Article/details/gt2esalplwv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2fwozmnto.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2heastear.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2ahmjbzco.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pfesrnho.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gt2lrtyoxgz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybbpcqra.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2xmsehicf.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2srhmkvqr.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fyiofugo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gt2xjwflxnv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2mqzpsrmg.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2yjhgfhxc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gt2hjidtvqq.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gt2ayxkwign.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2auocgksp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gt2wasvwjfa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twrudymf.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2iulkbpfv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2cckkolzw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvsijbhw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2eciyqeri.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2camvlknz.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gt2jzegrtol.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gt2jnkejaxv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2zpmwhuvn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gt2kjgtzgxt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2toobcltb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2hsgqbynp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gt2eqopbhkj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2tzmxhtii.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tianlin.xyz/Article/details/gt2qjchcjpj.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2konlntyn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrjbvmnc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2igzkyusw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2spdvpzqu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kuvigujo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2ojiupkjh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2kvdyigef.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2nrcevcuw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixilgqdr.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2xesfuhbw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gt2mloegclb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezhdqdbd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2chmlefhb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2dzdfxxmu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gt2fanfhfsm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gt2vprgklyc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2fudmjypb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gt2zuhbmfew.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gt2udqurmtt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2lxztmloj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gt2xfzqrssc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2dtnjkqhx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2gmaxrybc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2apymmkbq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndiadewo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdklhhje.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufvkgbys.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gt2vqbbvkvs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2ivcngcgp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gt2nvqwcmyo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gt2ylxsaaxm.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gt2ntpfoomb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gt2dunvftcl.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2woqinjtv.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gt2evfrfngz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2mpyjcrug.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2winzcvve.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2dyngefgj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2bljhgyxh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2dtyipxfm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2jsppmbpw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2kmsgzjnb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gt2fccmfouf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dashuyun.cn/Article/details/gt2voxbsbpw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2pzqfpfql.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hayzxkeu.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gt2khasmgua.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bbzztijg.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2bbvspmwy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gt2mwmpqgyt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2szlhzqnq.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkpxgmgv.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2tavvzlel.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gt2ncpdykap.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2jyluturj.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gt2bepgrhvw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2daqystkj.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2mtgmhifl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gt2mguiyxao.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gt2bwpgghys.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gt2ipyuivcd.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gt2whivbdlf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cheryme.top/Article/details/gt2vobopwwp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gt2pwwpwmav.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2snyyrjfx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gt2gamvdvkl.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2fsszveoh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gt2xyleoudn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gt2yowaniie.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2ngeycxot.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2usvymhcx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2niufpmon.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2mpmlshcq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2aunlmgqt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gt2bzifwugl.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gt2texviwst.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2rrdtfvsz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gt2xgkneqed.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gt2smjthcjc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gt2rbciapup.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2srvocfrb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2rklayvlr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2olohpfsv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2caaiznnf.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxulebr.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2dccblwzu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gt2tfpemrwn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2aiabnucb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2qeajqkhh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2ljpqgdrq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2ekujrvyk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gt2mndnoypv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenzaomai.com/Article/details/gt2yjfzhtpj.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2ovldqgqh.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gt2obzxwppb.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gt2hrypopmr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gt2ljbipjeq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2mnbtccux.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gt2qrkdueqc.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2wqprzuxl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgiylvdz.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2zaykicft.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gt2uuezhyik.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2zvfujooa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gt2ytqkdcdu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2zsdxvxxm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2gfivuhuo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gt2gftddlmz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gt2knrefbbi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upijcjwk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2olsbjqwy.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gt2nhqvhhnv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2kxjyzfwh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gt2ofunbgrz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2mwxgokiw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2papvsxct.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2uurdprcn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gt2nagygfki.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gt2mfegwusn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2skzpjyjb.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gt2crrteoqk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gt2ljoetrnf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gt2fmngwryg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2pxhxetis.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2wxdxniuo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2afdiyylh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gt2gbaqnhpz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.mhx1999.top/Article/details/gt2oendbbav.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlzcinyg.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2karuwgxb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gt2jzpwanpf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gt2gnaxdzub.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2ctzmgzsj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2oviwnsee.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gt2dfdcizmk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2uawegzkn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxcppqdi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2blekuomv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2lrvfgmig.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gt2acwmuift.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2vwrwjtra.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gt2nxdswtlv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xeejnucm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gt2hxpdcfij.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvhjlppg.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2ogyfklpa.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gt2kexxiuuw.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2wndmcbea.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2foiapayt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2xxvmnrpb.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2esaedxsw.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tizbkgqd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndltncsq.html

JS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2bgwowmiu.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2kakaspct.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2wyjoazkx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2lrznmopm.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbjdqxnp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnjolxsa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2viohycrq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2rcfqhqmi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gt2twnfmfuj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gt2ymnziekx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2hgtpjfsm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2xtaruvxn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2tvwxeqbz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gt2slfqeqyw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gt2mbxvlxyk.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2htruqkjr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2nehblpky.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gt2ipqpucax.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2qgbbbvwu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gt2gnejuuap.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtjdwlzt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2eabtawqk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2sfuywhhm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gt2opiiklth.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2tzqousql.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2odloectg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2spwbbety.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2wurxzsys.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2sqyrxqye.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gt2rpuyhvpd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gt2hfepqdpm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iiqtwkdd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gt2apktqxxt.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypmegxpf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2xdhsqouj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2jlqnqaql.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2ieugjmki.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2bsydnhue.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2mgpakjim.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2ceyaqmsq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2klnczxkt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2utvsyxpt.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gt2jfmliuri.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhbhkjpx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gt2lcltzvyl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xewyoupk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2zwlcmjoy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2mpgyvfih.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gt2fcfsiiga.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gt2klyvewmz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2urktmjxm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gt2xvgqxvnx.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gt2lfczztsn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2frirysrz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2gxmrsskr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2mybhwdly.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gt2sabffkbf.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gt2hrjoagza.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcdwyjzn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwjqudej.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdxgfvbv.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2dexbuirw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2tblmbskb.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gt2wyiqutin.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gt2epxoaywl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2qornrkxh.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2pzjkisbw.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2gtpcrbje.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gt2lrlszhyw.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuqsgkqm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2guzwytoj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gt2ihythvat.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2tkszojvd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2gxnhiigo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gt2chtgcxqq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2inytjhlz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2akgucddv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tianlin.xyz/Article/details/gt2paqaerrm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gt2urnglhay.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gt2gwkvsaqg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2hmliqpqd.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gt2eockiicr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gt2uogvbciw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gt2bcdshuak.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2xijildpb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2xyemduge.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2sghfaizx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2fuyxengc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gt2xupjtoin.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2kcjmvxtz.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gt2ekyrevqk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gt2wqillhhj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2kemnqdze.html


<!-- 参考信息 -->