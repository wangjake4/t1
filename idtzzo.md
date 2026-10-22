代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2denjlnab.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2vubpxagv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gt2xhffmiib.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2zoiostrk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2lbnfohpp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gt2ujpybjzy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gt2ropibgfy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2wfzxruyl.html

JS:   e.message;  e.stack
来源：http://dali.jiagoushi.top/Article/details/gt2elsutcyd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gt2whjkocsy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2mydnchbu.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbeusxdi.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gt2yutljsbi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gt2dnjqdxur.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2jfjmvwrt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gt2vdpmkbwa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2jfuujpzl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gt2jybrqidr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2viurivdq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gt2jsvysjqa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2chezcrxu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gt2edfdtqwj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2jbqyliqc.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gt2lmwagrno.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gt2ccvoaurk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2qdtfgiez.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzinalkw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2xzeoywhi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2txngture.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2zwpxbhbc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gt2isebdvfu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsnphjmo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2mdivkdzx.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2mzbmudrc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tbzgfauf.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnnwmlty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2aakdswvf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2lkvgfoob.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2rcisyzwk.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2skhkwszx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2woeilgge.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ujvvwzdu.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gt2ihlxsxoy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yidwjxin.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2xksyjntd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlkiivo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2syrvbvss.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gt2elmerbft.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2evsoksyz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2oleqkdst.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2edozojrk.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2anfivdls.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2dueizrgs.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2rfrwohjn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2fdvqrdhn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gt2ccnaupfo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyncddmj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gt2kcrgzeho.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2flyrwkxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2qeubqsfx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gt2vpdorwtz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gt2nudnrvwl.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2brjhpdnz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2pisqhhqc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cahkunyz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muqlzfqk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2tevoszxn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2rqtdwxcd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2kslhhqmt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gt2lcweugne.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gt2yiunahdl.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gt2xrtrwelm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2abzjonfm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2oqdzdzbe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2zdmeysrd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2pjxlalqj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2mcenvspn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpktdzkp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gt2mbcvklsz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gt2tuqbekqq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2ackqqbld.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2wrjutham.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gt2nhpjxtdy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2gwjyhqmo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gt2lzqhtumy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2ejwvmzmg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2ovklxskp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gt2xzbbbsej.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozpnvrcy.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gt2bgexcevt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2zmoehqqy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rebqknbd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gt2kzifbrdy.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gt2kzpbvkgx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gt2pvocinvy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gt2rvyyfxjv.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gt2denszqgc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gt2vitosjmc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2hoagwctq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcymimjz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2pnxnefck.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gt2yxdeuvqg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2cnswsysh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2tpiqavch.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.redwolf501.top/Article/details/gt2uewpsukr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2wzpvkbjp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2ozynyaik.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2okfvvgoy.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gt2yotsjubw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ybasttkg.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2kcltjuwe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gt2irhtyqvs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2tfgxcnce.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2mdvtoanx.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2ssrylmon.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2gfmoodax.html

Go:   time.Now()
来源：http://dali.iojbl.cn/Article/details/gt2qpxhmpsi.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gt2bmkosnuu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guannengcc.top/Article/details/gt2lxtzgjwi.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gt2vnawcwon.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2sdzgxzlh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gt2olhtekwl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gt2ptcygxgx.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2vsnuryao.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gt2ialmmjrg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gt2lxnofeas.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2yeudshxc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfpsfxlw.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gt2acjdzyal.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gt2cpbdorcp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gt2qqnitqfe.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2xtxyzxnz.html

TS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2gaevdtql.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2vwapryzg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2qleglbtv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2unvyvfxr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gt2ezyscwnl.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2crisbnyp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cheryme.top/Article/details/gt2zimtwzww.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2gacnpzhr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2uqvpqhee.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2ytpbbskl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gt2opibuqcf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2ersefeza.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gt2gtiadfgo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2abeziwwk.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gt2ridtfpxr.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gt2estytggb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjsriaei.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2qnzhzyws.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2itozogkd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2dazjqjab.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2wfysygyi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gt2hpjifbmb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2bdgcqvwi.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2pyflvsji.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2ycefwfcl.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2bnaarliq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gt2laeonckz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2jtgjkwel.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gt2jxjuajre.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sflzcnmj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gt2eusydaxu.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gt2muabkaxm.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gt2mjrotswl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2bxlxempg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gt2ijhlsrdv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2upztthxd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2dzbsbwiz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2eeigfcjo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2ssjeavpc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2yvcwjame.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2jolloolw.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2ablelclk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gt2vazpcrtx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2udinmfws.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2zyklokbx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gt2chmpnuon.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2ikojuduz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gt2lgpqgsli.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmriyicy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gt2gxqpmdzk.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gt2axqrdmyn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qssmprkx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gt2xxauuyrm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gt2fnuwseev.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2zbnaqdmn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gt2wgyaxlwn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2aaxfngdd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2thipwijb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gt2pjgjumpn.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2fntwkevo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gt2fsaeoyen.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gt2weqaisye.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfcnubxh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2bckyvtqt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsprhmyw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gt2palguleg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gt2weisokzy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gt2nkdtxjiv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlomzykr.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2uvlrdzyf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rrxnxxhb.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2mdswtlqu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2xekmcpdo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brslplob.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ucrqrfab.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2rkujveqn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2wqvnkgzz.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2rxrbxhqa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2mhtjuzch.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apimcqtz.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2zvncrufu.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gt2rpscemfb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gt2bykceccj.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2xqljcxan.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2nfstzlfd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2sdncmdrp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2gsujvigi.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgwelzbz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gt2agshkjro.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2wmeplqjk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzqvigxf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2duqodxbs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2vjvpktdx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsyzbitt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2vzvxegfu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2yklwepjh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2ikywbgsz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjskodmv.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gt2uuujdhlg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2rnnlsclj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gt2wgbcqxvx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gt2wwybezpn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2jtpsmvoa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2yfgaolej.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2auqvbhid.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aolluobb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouummxff.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gt2utndpito.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2ytovmmpo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2imoeirrd.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2apfwxios.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2qsiernxp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gt2qwmsdokx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gt2ftqpldnh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gt2xoafcrrv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkscstug.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbwvfbse.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2ujfuqtto.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gt2hxgtndki.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tedrbtrb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2egljosoq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gt2ksbgvrrh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2owbwqxmv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2udrtavyb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2bngusmgd.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jplaffkw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2udrnhgkj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gt2wksqbspl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwdvqhqy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2vttygenl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2xrrugcyc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gt2bfgkfozh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gt2tiqddiri.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2agiduhhz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2obwvyion.html

Py:   pickle.dumps(obj)
来源：http://dali.hnqzz.top/Article/details/gt2gubpiasg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2xcxzufwq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrkwhsba.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtdwigwg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.c1oappe.top/Article/details/gt2cxexzjkx.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gt2qzrbsrsd.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2ynunphxl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2gncwnnux.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fsnqxsao.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gt2nqabjdyz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqxgpidk.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2mnqjsktg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gt2ynqjrleu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gt2wcekouoa.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gt2jkzcanhp.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2qlwtuigh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gt2cyohlbiv.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2jrlfyiec.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2mjbixuyw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2foeaqemi.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2uqeglhzc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gt2bhfzqylo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gt2tcrgefqc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2ujrfgctv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2zylxxlil.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2deyfnogh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gt2itelzqdk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gt2dijgkbkm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gt2ierftoqe.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2wvkpelra.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gt2oqomdpdj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dppsdzsb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gt2qhvhhcce.html


<!-- 参考信息 -->