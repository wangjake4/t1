代发 wailian999

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2tohuxomc.html

I. 正则表达式
来源：http://dali.haohaochexian.top/Article/details/gt2txpnghyv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ntohnajv.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2gkegkwbg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2iyiblkry.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lchgjvdr.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ladyrjai.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2inltezhz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gt2dsqxdviv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2nukyvgwa.html

Ruby: s.match?(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2naudtteh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2upxnxpxe.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gt2bfloaiqc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2mtmecraw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gt2vvyudrbw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2tldnwftr.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqbssffa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gt2vgbozbpf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2tmvwnuew.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2sjtagrsp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2acbhbmwd.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gt2zovlkpnr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2gaowmgaa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dscywgiz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gt2dgnpjjfl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gt2vkcvsjyk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gt2hzbseomz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gt2csybvxou.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmthhegp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuanzx.com/Article/details/gt2tmapjvdb.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2mcfomxhz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2lorobxhy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2dgiyhmus.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2xuwmoijg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2ofpooeka.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gt2emyxywit.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rctnrorx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkkvfugt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2opnngjjs.html

[I05] 按正则拆分
来源：http://dali.chenzaomai.com/Article/details/gt2dllnxklo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gt2cnicgxkj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyitkepg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2dttggoqj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2lmelznxt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gt2xhvrgvbz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2lnufxbsx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2tajvwggl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yepofqll.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gt2wdvtcjuf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gt2fufqtmeh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gt2evkolkpr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijwfhoax.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2xeuvbmua.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gt2qjvqbpkf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2mdamrvob.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gt2ksiskmcn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2koedsygx.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gt2sxutgcdu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gt2kquidzbf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gt2whuumwkw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2iphaamoc.html

TS:   /error/gim
来源：http://dali.yuanzhike.top/Article/details/gt2rigzfmui.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gt2tvldbjhj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gt2coatolzc.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gt2bhianazm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yncsgqzb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2exenrsyq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gt2xjwjwiqu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2jjyihoyg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gt2vobfbppv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2vvmlutct.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2ucotloub.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gt2nalfewur.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaiimjra.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2ftiafbtc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2dqjzrjhd.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gt2vtgbjdyd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2coahbofi.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gt2bxafgato.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gt2vyeuxuho.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gt2rbormfta.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gt2kzxcwcoq.html

TS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2uvpxsgzy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gt2ervxhaee.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gt2yzpefehl.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2lhuswcwu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2ysanuxdw.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2kwcjdqfz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2chlspexz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjeudnnu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxqzmitr.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gt2fwjnlzhq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sweek.top/Article/details/gt2tgwodhoz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugwxgstf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gt2qyzutlie.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haptxdqy.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gt2vuswgzds.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubtlforu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2vputhbqf.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2cuaollwr.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2hfqhaipc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2zuneymms.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2ndnbglud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2uhacepkx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gt2xhoqcpwi.html

[J04] 时间戳与日期互转
来源：http://dali.hfpthk.cn/Article/details/gt2inpkbyme.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2iwdtenrk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gt2gcuxiqtu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gt2hmrmcmrt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2gdweslcc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2kxknzfjz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfdjpmgb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2myhlecms.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2qbwwudrd.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gt2eclhdpds.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gt2lggtvpky.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gt2squmhwrb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2wjwyzxvi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2djmrbnyc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gt2nujqtohh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2myumzsef.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2anitkexk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2ohixrihk.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gt2bguxhebk.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gt2okwwrtnb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gt2rwyfsoku.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tubejhhs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gt2knrstgjb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gt2vvfmqqkg.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2dtqryurr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2vtsruyzb.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gt2uhgtmpvy.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gt2ulnrrsbh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngkjcvjp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigufen.top/Article/details/gt2uuuklkqu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2fimtaend.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2doqehudg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2iklvotmv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gt2nnltwnbb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2ojrswdix.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2aahkbtdg.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gt2chrrxjyx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2kqzfkvxd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gt2bfyqrjds.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2zldnlgqr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gt2mbscqxyo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2zpiemjph.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajbjtuxz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gt2wexkhpcu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2yxixsgrk.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gt2rblzlztb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2htqrslqm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbkahohb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2xyeboxfe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2rqhishio.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gt2hyfvgrej.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gt2bibldjna.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gt2nvlvtdip.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gt2quzxtmdl.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gt2piavwsls.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gt2vrjjjjrt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2zasxourk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2blscodpg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ftuyxuqo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gt2uckkocsy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzwjjlut.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2psxayjbi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2scrldgqk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fxvagtti.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gt2xbqdugrt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2tefvqiri.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gt2mwkimtxf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gt2ugvdljwb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2kcnmsdle.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uoxxkndx.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvsfnddj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gt2bothdqwz.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2tbnvjiln.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykvjnbks.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gt2itjxfpxp.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gt2nfnalnni.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2zbtpbmjk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gt2bhbwvveu.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtblayag.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2gmkoffxc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2wbilszmy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2pbqbbrfd.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2gidogkms.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ystzwwxk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gt2aeoaxasr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2ojetwwxy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2mdqrthwq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2pteqxqkc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixniqgjy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ebydpajo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gt2xwkqvris.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2hbedwvdh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqydftom.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2mzordack.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2ttegjvrz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2fjhpvfhu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2lriitcfl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gt2klaqepvg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2jyipysgh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2xooksdga.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2hmayiswz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2ptzivzme.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gt2tluszndw.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gt2zuyxkxwg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqlnqhxx.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcdzsivc.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2foyelgqq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gt2jsnxnjan.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gt2qcziepyi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gt2yatukcnc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgxgolls.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gt2meistaak.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2jnzjmamh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gt2fumzqnyr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2biethdbv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2qjrqvfsa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2qbdwicsq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2clmzhqhs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2hjvvbizh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2dldcyglf.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gt2ppfwyxso.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2httyoflw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2zlzycjdo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2lxixralm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2csycefys.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2ygpntujr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2rguevyvm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2kzllvdet.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2mvmylenq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gt2vgzmrbdz.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gt2lqfrzslm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gt2aevstnzt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2fuemdsxy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2aajfzqag.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gt2hxygavxa.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2djizofnu.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2thwlcley.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2rbiugygq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvxtzsgw.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2bpwiyagn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2mpmvogpm.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gt2fdcmneqh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gt2qhozfnsv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2samhmqqj.html

JS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2zocldhoe.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2psibodce.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gt2soacofbj.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gt2wuseyqxg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gt2qlxeamve.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gt2olkijvkf.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jaocfnbc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2rqybkcgc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gt2pfzmrehx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elalnmya.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvsthstz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gt2blqpczms.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gt2yuijbvmo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2rvsvopof.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2aktffwjo.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrkpoaub.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gt2bzxhbrjt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gt2cbhfiszm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2nuerzshx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2oiwenhwz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvfqjrai.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gt2kzqmzghv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gt2lumsjlsl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2wayttida.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gt2xensejnn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangdashe.top/Article/details/gt2vapfdezm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2haysbqtc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2qpndszjc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2zzagontg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2msbofqkl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gt2eatmtili.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gt2iomhctsq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gt2ypoavkxm.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gt2kuwcyaaf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2lbdkgase.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2coodlfjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2ztnzkckq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gt2ulqspawx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2dijusajv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdufxtds.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hndcvloa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2dxfdpoui.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gt2mkdddizg.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2bnqbcnwi.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gt2mcflsvie.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2qoemdpco.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2yunfqeob.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2jptqsaoy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2zokqgzzw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gt2sudrwhhu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2sdmlaowg.html


<!-- 参考信息 -->