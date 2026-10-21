代发 wailian999

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtssutnvwh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtpgnlfwof.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtkkdbxrgk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtadtgmrix.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtclvnhist.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtvgklypvi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtqxovnsoy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtizjzddau.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtagoyeqvi.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtdqmpetpb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtzqvpktyk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtfgrcgddq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gttubhnqzk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtbecasprf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gttrngczvb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtskcyskfo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtfervxqvj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvvkkcck.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtngfqupgi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtjkqmpibc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtctyplvrz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtlhyiltvi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtqervjuky.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtmrniifya.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtpjcuddvr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtgxqlcubg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtfrujwzmq.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtkdopifha.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtdsngqopo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecsdflql.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtussdxwxj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbryewsf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtduuydjea.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtdwmxxyfk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtsotykpmp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtjnungbtl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtpyzvgamf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtkssehayf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtqqloatch.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtxyruaaho.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgpltezm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtphrafjsh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gthlevnuhl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtslfiyzdy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtfqqhssyr.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtigtcsswt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjuugvdz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtwxckapjh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtdykvlesd.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtnltylunn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtsbgesryq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtkqsgqgpa.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtceqowusu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwgazmnf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtvlotbxzc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtuccyitiu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtxyduiypg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtrrkyclay.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtmkngguwi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtjquqetnm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtfynarymv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenzaomai.com/Article/details/gtawtocici.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtdbpxxhyz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtunbetheg.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gtumzrcvqn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvbzazofv.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtqicjsqfq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtaitjvxvc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtfxpzqfrz.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtnsvgvmkn.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtdwuxlhea.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtvpycweet.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtbbynxhdv.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gtbhujkuhs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtgicjzldj.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtmghoodhp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtfcqtcpjb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtqvyoeuhy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gtixkahecz.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtlhqkapcp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gtjbgfqafg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtbspamywx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtyjnmxutg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeyrsxzp.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtqdvvgqjx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtkesniece.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hfpthk.cn/Article/details/gtjspuruwc.html

JS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtefxlocne.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtbjmvowlw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtdztikplh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtecytakea.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtryooeqbl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtvugdkwxs.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtkswmlhlw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtfrvrlrrm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zdqjudy.top/Article/details/gtksbsmvta.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtklccmskt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gtzirqbdkj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtvhjcwjci.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gtfvkliluo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtuukfafcr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gthllmrpoh.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtrwoxjdjw.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkiidfmn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtyfyrszlu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gttjexbqeo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtindspeqa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtxcajtbks.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gttobcjnlb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gteuyzbbxx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtncocszes.html

[J06] 计算两时间之差
来源：http://dali.cdnleiting.top/Article/details/gtpauoaimz.html

Py:   (end - start).total_seconds()
来源：http://dali.xinyue.icu/Article/details/gtsyhcxnrm.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtsbkiukla.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gtgcodbkbh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtndrfrjeu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtkpicksww.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gtzlnvdstn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gttbnuqfux.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtzmslojsc.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtxubqhkgr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtcoywikkp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtmdkcnpit.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtiupkvzrg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtlkhdnfpf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtorajtoen.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gtipbnrsjq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtcadpcwso.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtnativcvk.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gtxwfuphdm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtmkkzuogq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtmdashbmz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtqzsdulrz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtujbigmci.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gtmvshrjok.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtaomqvyuj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexfzeako.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gtdarvdzui.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtuklkcmew.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtzdzlyidx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gttuoqgxin.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtxbiwisxe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtbmtzmudj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtpelajgmh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gtyownwxyj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtmuuyupgm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuetiantiany.cn/Article/details/gtdbaitosn.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtqwumfigm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gtyhryvsdh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtixxtjstj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtuchvaokz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtvmmkawff.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gtkizjoaeu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtdiuulogt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtoxgbajyh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtaxmnogkq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyjnkesih.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtpvvyfjqc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbylkrtlk.html

[K01] 对象转 JSON 字符串
来源：http://dali.316326.xyz/Article/details/gtvjtohbuf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtnmnjlxuf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtgtqhfcrd.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtlkybtjnc.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtxnnypwod.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtsyabwqck.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtaaksmdqk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ivvv.top/Article/details/gtcdcogngy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtfkikyvfr.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gteqxetxta.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtnqzoicox.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtpsmejlmo.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgevbxywe.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gthwijekur.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtxbghncdj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtdiqbkvxv.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gthjlnppzp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtclrdktzd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gttdviuqpg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtgghschlw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtwidclejq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gthouaxqwy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtgmswxhxt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xinyue.icu/Article/details/gtgmadhqkn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtpecpmwxl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gtqsjyhozj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtmasqaipo.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtthfblpis.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gtgprsfwgg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtvrcnarty.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtfhzsqvdv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtenjxvhhb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtcutavvif.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtxjhipyol.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtzgtdfyfu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtewkytprv.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gtkhdgmcos.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtydogvxgr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtlubirkzq.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxnqgbbav.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtvxvmaifz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtrgpasvtx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtxpfaeknv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gtdabuwcyu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtrjgvojxv.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtpcugpahy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gttgpasqel.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fengsongda.top/Article/details/gtgzpecylo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtwdtkgcbn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtggjjpvdh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtxuxcsgpg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwewbjka.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtxycfaxnk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtpccpfafq.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gtnkrjcgwu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtbklepfnz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoaoplof.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtgjfvukbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtpgtefiqe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtwyldfqhx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtajscxkup.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtlylwszxa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtgixvbuua.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtkajenpmk.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtpikqmqpk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtxnoipmdk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtlphlmbww.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtbgkjmbue.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtmzzqmmhu.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtaymlqaku.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtwlqyjzej.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtykprqjtn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmpwyfsjo.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtissqlctk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtprvrgigw.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gtupjjkbit.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gtqwllkrqq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtbcjrpugc.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtkicrriyz.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtjifxsjyr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gtsnilvujv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gtwbgonxny.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtelfsxnds.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtvwiaeqtr.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtsoyduwaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtcwseepmh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gtwxpijvdq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtgtefuutl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtvjcrifrs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gtcuxnmmjl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gtgpgenare.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtqyguqozx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gtaqjwuynv.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtawdeolbw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ehwqpu.com/Article/details/gtwaozgeit.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtotjvwocz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtuqhbgcss.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblvzytjm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtwynctjri.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtqjdgkruc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtyoqzqijk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtwjgronvq.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtftfengjo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtvkihvbqx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.9152youxi.cn/Article/details/gtolmjwbrm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgrnholg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrqefbye.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtvklqhmqo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtvgnlcvgm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtzszhuwma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gtewmhuqrf.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gtrofvltnq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtqulndevn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtaiplnycz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtcshsuhzl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtatcqfziw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.feifeiyinyue.top/Article/details/gtohmjdixy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtxakahdjt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtczlcwskd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncsbxyli.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtzrlojgpx.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtuhewwzio.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtderpixwy.html

JS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gthxzegpfo.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtjejgiyca.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtsdomrhfe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtzxmhfhag.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gttfwuhuce.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtidxzblck.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtcwmcrjua.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtrlonpovc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvzrpzdt.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gteyzcsner.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtjljdffbl.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtjvzipkgz.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gttngcgzvh.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtueznfhbt.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtexitxyry.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtgkzhzjad.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtblqielad.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtwqwbfrtp.html


<!-- 参考信息 -->