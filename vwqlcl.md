代发 wailian999

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtfnbmyork.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtcmcfgdtd.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtjypuixus.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmxeppmy.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtqmzcaezw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtxadjyydq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gthqxponvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtuxhpfduu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtlljyhfae.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gtaaeqjeab.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtfcfyyauw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gtauwygdqz.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtmomnznog.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtnpcxdorw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtgzmrtfpw.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gtiddmmnai.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gtfnkywxbl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gthcqmcyll.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtqtezcdyg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtirsflime.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtnwxrkpqi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtwpnqyyld.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtggimukih.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gtdetfqvuz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtoitgijka.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.iojbl.cn/Article/details/gtgzbglpdc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtweqyjjaw.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gtdmpfinlm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtwodlbtkz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtyprepffu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtdnhiaopz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtohcdljgy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtsiihuhzy.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtywpcjsdi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtdohjtzsv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtkxxxutfm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlghmygbm.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gtsqzeogsp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkefwnnag.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtixilrpij.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtcuqybtgl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtliavaahm.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtphvbyjsz.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekkuyxid.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gtkuswzyqj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtsldmbjeq.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtynaaargt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gttvurshvx.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtfnjkdurm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmdswdve.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gthwrshjwu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtslkezfpf.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtuthtvbiw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gteyyxaryz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtytxqzpth.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtuwtbgnwx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtrskwvjdj.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gtngdstthc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gtxdmekpqf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtmrojgisu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xinyue.icu/Article/details/gtselnlzij.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtjgzdovvg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtfipbjuud.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtimevhbms.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtimspefkf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gtorgtohfu.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gthlnytkau.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtsfxkyhxu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtfdvomifx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtjwmmxxla.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtggxcmvkc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtihqnsjtm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtnymsakdm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdxtocwl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtofccwcsp.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtaqbmrebh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.meibo888.top/Article/details/gtgojtrkdv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtptnbmonw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosflqddi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtdsdtctin.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtdeeeqnty.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtzelheocr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtdcrsydgs.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gteqvwgvym.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdesjjqft.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtehzmwkoi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtlgpkjmtt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtniannzoa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxrmzzum.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gtrosivcwz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtoznqjbdj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtsjdkttsf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtnzyvefdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtrvxmkrmh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gtlmnixkkz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtkhwerexv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtiugbcjbh.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gtsolomxtr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtyhbnugwq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzlrcznw.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gtpbjjxaxf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtlbrlxlwn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtphpdeirx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtevvvosiu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtpnxaepeu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtbxscsjxg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtkxlspvmp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtsuczqtvu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtioeebhtb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnxiangtu.top/Article/details/gtrtmqqvff.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtfdsrrkhb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwigexqbz.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gtwcjzzbth.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfbcxtdxs.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtpwelrjmq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtckzahkpd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtptymmmnm.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtiwxndcga.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmolzpnj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenzaomai.com/Article/details/gtluypxwaa.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gtebpammrf.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gtkyziofrp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jyoumei.cn/Article/details/gthfvsaomy.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtextripyo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvwxykvz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtfjpdrvvr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gtphvnwhsm.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gtotlsuwiy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtcrqmkuqx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtcxvfktef.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtdblcjdqq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtqplhcmng.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtprvporkh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtbggfysvb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gttuvmzfae.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtsaxpdnwy.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtmzklcrrq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtwnomhywx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtvksjmvqn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtbdvheodz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gthpnehaps.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gthielawkk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gttcbbimcs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtolkvgyzt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtllfvoxme.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtnuzhbrdf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtiybrmlft.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtujuqybvj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtmdzovmyy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtpuviawqx.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtwahydkfu.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcfpkocw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gtawpfyptj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gteilmlsir.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtxxgpawsk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gtsvdskcfw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtvyffexma.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtpgtbmccm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomendgna.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtncswkngb.html

Py:   (end - start).total_seconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwuetesg.html

PHP:  $end->diff($start)->days;
来源：http://dali.yangfankeji.com/Article/details/gtjtpmyurl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtfrvokotx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwkanljx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhixingplan.top/Article/details/gtxqjjwoia.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtonzzmsba.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gtzzcdrmrf.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gtrqfyyonk.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtzmhxyrbn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtvlbdakxb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gttlvaiefq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtubrgklha.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gttxigtiae.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gtjxiyltle.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gteonkkxlw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtakpmluvz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gtqcsiwnnc.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtutodbefs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gteamrxxuj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtfecutqmy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gtqeuliyzg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtztzmnniz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gthkqwjsep.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtnteobrza.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gtpacijddn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtmkptewop.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtbzbcvvsp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtghyzlwhb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtbzkdymvi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtlxqhqqoa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtgoxegkor.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtbacbsxnr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gttiwjlaak.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtdveuhxce.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtftrnount.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gtrfdxvgew.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtofrumche.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gtpxmfnuqy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtkvfxguke.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gtyitxubek.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtcheblrlu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtqurmbjha.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhiwuduotai.top/Article/details/gtzgwgcnlt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtiuyzdlwp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpmufuwou.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gthkhgtaxy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfyeztvzb.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gtiynkrwoh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtmbakrasu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtinnptbcs.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtknrmhncq.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtlfiqzpmm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtdqnpbgyf.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtebanouoa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gtvprcoytn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtjyvdhpne.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gtvmabenyy.html

Py:   json.loads(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqzqmaai.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gtxfghwguk.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtlnxkefap.html

TS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtgbrrdmom.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtclffanpy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtaokheffe.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtakcywnkc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtsbgpyywb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtyovripxj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtscqtqrmv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gttbrmigrj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtvthjcttf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtbcfxkbyb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtnledmwxc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtnukbsqgs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtivuefyct.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekpdoguz.html

[K04] 读取 JSON 文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzdahetum.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtyzlehjlc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gtmigzvynw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtfadmgwqg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmlvznlau.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtzvznnuaj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtbixlrgsc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwyiwvwlk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtgvgzxgbe.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtakopbobs.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtmoioauow.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtvtwmaxxv.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtasahaxvg.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtmslfwaku.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gthlhhkrwn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtxtqbbpkm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtmuifckkj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtaxszpjnj.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtavunxmhf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtqapdphmw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtkzvpgxbz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtncqnkjjx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtbwaohiny.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtzxxiphth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtmcqlivcr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtqjmpipyt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbenqipj.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gtkhyxbkiq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtytmtrwrt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtljweoxhd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtmyndnhpf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjpfcgtq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gttzqksjfz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtycutlmdr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhozrnpl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtibxbevhh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtqjnbugdk.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gtgcjkhrdq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtfrtduwsv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtmvainemg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtdeqgdxsc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymgzguez.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtxjboujfw.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtupnslibm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtodfrzaza.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgchgvtgc.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gtaogvqwap.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqqbzbyzh.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtrqxpseqy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtpphvvqaw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqprchwt.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gthlepmjpv.html

TS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtfblnzruv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtsdureouq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtolsnxrba.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtenjbziio.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtatevbqpa.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtnyfjsyzf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gtiwwovnze.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfgvocjk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtrbhobful.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtneqzsoqr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gtyfjxbiwh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtkhjnxzxf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gtfimabfeq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtxmjntvch.html


<!-- 参考信息 -->