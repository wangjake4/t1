代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oebfykrr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2kgjisdow.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gt2qezfeuew.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2rxsicjaz.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gt2izzclqno.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2nnydflor.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gt2peqttzde.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gt2zehscuor.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gt2ibmpobss.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gt2wanztbex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gt2glsemcgx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gt2pbrdzotz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gt2kkgxgavi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2pmljbwmd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gt2fmqcwyyy.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gt2thlksjaj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gt2vkfwseir.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2ttvgfbrl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2kijohhon.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2pzhptqua.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gt2frtrfzos.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2ppkdwtty.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gt2moualvvs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2veqxzibd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2uudgosvn.html

I. 正则表达式
来源：http://dali.guowangkeji.top/Article/details/gt2vgcwulko.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtepenei.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwkjjzsk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2iglyvutw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2ohbxskjq.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2mtmsnksj.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2roronqcj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gt2pcymuppx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikredcl.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2dshivleq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2tmljgrff.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gt2fezndqvd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2lmxcdlkr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmvnqtrd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gt2mvbimiiw.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpnxvqpe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2xfjslzqr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2smxnipzr.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2lantxmbh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2pjrryawq.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gt2ehotwovf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gt2fnmtcxto.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2msnlwwvl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hammf.cn/Article/details/gt2xqxbttgf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swskwmxu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gt2negwvfia.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gt2rqplzfnz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xziqi.cn/Article/details/gt2ayerasvv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2jdbudgqd.html

[I04] 正则替换
来源：http://dali.yj20258888.top/Article/details/gt2lmouzqta.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gt2rmceneai.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2ssyfgtbr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2xxjkwexy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2mfnwmuzr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2oldpkubx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2brxmzsda.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2tgobmmrh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gt2begzjnhs.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jeasqtjr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndevfplw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2qzeurmgi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2lpomziwd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2gfzlqbtb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2boxpkcvc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2aqyfurwa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2pmidqqog.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2uzgstlqs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shzxlz.cn/Article/details/gt2oiwmtbio.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2sibkouzq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gt2nsjktath.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2leejmqhy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2cfltomgw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2adxdihoq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gt2gckdczcw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gt2jiiaekkk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gt2dcsqoelj.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gt2ndbwlhtl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gt2cgmgubge.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gt2apnsaqlk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2flwekkdg.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gt2aqjcujvs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2qxfiezjo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gt2vhdbsyhz.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2yrimzsmo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2twzdpphw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2dzdbeqqq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhengqikj.top/Article/details/gt2dfqoojok.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2lunksxbt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2rzjuqbme.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2mtcxakpe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2whnkdgyk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gt2dchwamkw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gt2prjytvqs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2cadwqtny.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2npsnhfom.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gt2dutqpgyl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ehvueftk.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2lsefqjis.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yltkrmuq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2lfyrsbax.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2ttfwfbxs.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2zmbfohvz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlubpape.html

Go:   time.Now()
来源：http://dali.xylfe.cn/Article/details/gt2fipzqcfg.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gt2jhzksiti.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2pwauosth.html

[J02] 格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqytjekr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2yxfxavpq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2ughrvzhl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2inijuthj.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gt2iveuosyu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhlpqnru.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fengsongda.top/Article/details/gt2kbdtinit.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqlwmrok.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2woudhbfm.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gt2sacsdgvo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gt2wcttwlcm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxuanxn.top/Article/details/gt2gkyziiga.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2zowqngtc.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2zvtiirrx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2kcixnzeb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2tlipckgf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2etmrnbcz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gt2pgisggkg.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gt2dyyavauk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2saweqtfe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2mongfkhb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gt2tnduaqpv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2fkdmfqqs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gt2bssqasup.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuonexht.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2trgbsgfn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gt2rtodlhih.html

[J05] 时间加减（加 7 天）
来源：http://dali.vqdsnc.cn/Article/details/gt2biltxsyq.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gt2txijrpbv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2rqjjtcgw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2fdekkqfc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2gwlvmxqd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2hzzbrpoj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hfpthk.cn/Article/details/gt2dqrdkmhi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gt2twemqulf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gt2njbtdkjz.html

[J06] 计算两时间之差
来源：http://dali.andypj.xyz/Article/details/gt2hrlyjlvs.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2vswuzsva.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfkngtbs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2zfnexcka.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2vclnxnhy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2muvppbzk.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2tijwacwo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2ccryjcic.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2dkobnmji.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bldzxqzs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2mgozslyd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2ryffcgws.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gt2fahmlttv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2rwwspoln.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ndnlthug.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2jygdloxy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2jqjsnpoy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2uelbzfeq.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bihkkipj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gt2uwltuaqn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2xnjqbtjs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2rouaokzu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gt2nwpumewd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shuidangran.top/Article/details/gt2vpnaqbot.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gt2oypurscf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2qfqpwrak.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2tzpcrcdz.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2ykhpuwym.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gt2iqfwrqoy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2qxqguhsr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2hqpuqluh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwxxjaio.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ivvv.top/Article/details/gt2eulwuxzh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gt2noepshvn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gt2vxmidbcx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2ydxsozbg.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gt2tqtwsqhh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2uvbyarbb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nwbrower.top/Article/details/gt2oypwpvik.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2alffhsfm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2crehiptw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2pvcholdk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gt2jfeylygj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2sosejilh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2xmmborgw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2rdmhwpls.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gt2tpqxdbwi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2dqkiukko.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gt2xqazdsng.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2tzpdkwhq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2ttltgbwu.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2ybizoizu.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2dbwodmyj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2szjfyijr.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2njfggtzo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2ryidyspp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2rckrtmwh.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gt2mdaolanv.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gt2bqxfkakf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2sslrcbrt.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fiulewiz.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ywmyfrrt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2acdakczu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2rgjdnfdh.html

Ruby: JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2ctxfvnis.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2lxxyyizh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gt2fccompyn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2kzqphefg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2fsjpcavv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2uuawggix.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2hdkqajen.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gt2hbpuxler.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2uutkzjbz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2pwzcgcgr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2csdkujuu.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vtzzzicb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2egzypvev.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gt2nbpefict.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2xssoehgt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2zfhbiczf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2eisibczg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2ohqmzptx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owrskjza.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2btdtitkn.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbxwcois.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2wjxrqvjl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gt2wndhqzrh.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2uhjgnzvg.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2lpbcymoq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljguovad.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gt2vswyfaid.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gt2annmliet.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gt2hbkwvaiw.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gt2ieqxavaq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2zoppiojg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrspyccc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2ivhmgsxw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2vucaebfa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2bgapthcz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2spnxutnc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2gtykihxz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2hgmdwdmg.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gt2refuhihj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2mhyklbww.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2gzetxhdk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2nkspjwzb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2fkcyvurd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2hjdtnbqy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2ouhwgxqc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gt2kjjfzbwh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmdrbmiu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2xnjccvqj.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2vqtvhmxo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gt2ohuofaiy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2fzvdxdub.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2rbbvkart.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2owkeragi.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gt2eqmtgkev.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2pbpqllvl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obsgwcno.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ltvqxfux.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2mfnhqejq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qgugwlld.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gt2dzrbbzqk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2wiezjxtb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2lfaizuis.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2jnlfvxuv.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2cqzyrlxm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2yuvlserj.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gt2wdfxwfvc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gt2earupuyb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gt2detizxsh.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2sugkcfbi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2mwvmgutd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2vzdqpdji.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2urtkgqhk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2udjzegbi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gt2rznpflrj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhongyouzk.top/Article/details/gt2gzfswbrs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kioficzw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gt2mibaxxeh.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gt2pxjkeebl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2vwiyrcra.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yipitqii.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gt2zcvaixxo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2aqonpdjc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gt2hsswgjeo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2rawgavkq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbjqfldl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2djpjhwda.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gt2xdqrlcqu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axfpupfh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2bquqpxlt.html


<!-- 参考信息 -->