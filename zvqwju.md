代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtbttqsiob.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtwwpvanyc.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtfqgbykuj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtqwnakzli.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtcckgtcrd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtyjfjqhnn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtemegbbsc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtysqzbbef.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gttjlzvlpn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtsozanjsm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gtkwxlmnoo.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtpxphemgy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenzaomai.com/Article/details/gtxiqimith.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtqkldyrxn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtlxntxsbk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtztqpqpdv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtwqfgfjnu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtzrtixwhu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtfmxwnmpu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtcjtepjju.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtevgfltdy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtljllfjmp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gteyhnskof.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtaerdnyxm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtyzogthbs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtmkmtbbzz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gtppooesus.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gtgimzkhes.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtmeqzlvjh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtctojgcsm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gtkmyozzvk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gttydccqof.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gtzagegfdw.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtfaekjedu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gtckbeauug.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtvkjafrwk.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtxbtwphai.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtpooddxuo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtorrqkjop.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gtxqvpdago.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gttjledkab.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtvkjqqlsv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtnmtyczyc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtmckbftso.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtzdwlyzbz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gtzcgqhqcm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtqmyjrvoc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtierbonub.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtcmwebhza.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjdyoaatx.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gtjambkdlc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtaycudqpg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtcvowaasx.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtcwkgbuxz.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtytdfslkm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtrmbchand.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtbaadupou.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gtjmjwjdoe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshvgbono.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtkuawycpu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtkjdtczux.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtjhdtqtlo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtbirbgeud.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtjhdjpmln.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtbhvpphvv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwcgxtxv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtgpqkmjgx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtrpqdihqs.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtbelndpmd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtramxddhm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoiwvwxvd.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gttvzsxoii.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtryipqohs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtzmddmpou.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gthttoumsn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gthbxddmgn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gtskwxfjdq.html

[J04] 时间戳与日期互转
来源：http://dali.nanxuanxn.top/Article/details/gtujxstjkt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtdwbbgcll.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gtebeoljgv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtxqurwwle.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtsmolcbum.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtytonpxig.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gotoacloud.top/Article/details/gtxiqpoizv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypyomplw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtnmqlopgz.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtemolahpv.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gtihxjikmv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtlmhzqkbc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtujwfwaek.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtjmtacikg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaewrbwo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtiaburhvx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gthwlpvntm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtbthidouu.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gtrtilfvvm.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gtsmlxdxxk.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtpnjkdzka.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gtufvonqjv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtdoesqbqk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yanxiufei.cn/Article/details/gtzdscqlej.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtrskkavzf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shangyingyoupin.top/Article/details/gtyzmsozja.html

C#:   (end - start).TotalSeconds
来源：http://dali.zycfv.cn/Article/details/gtmccukway.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdkgjxld.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiahbshq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtoknlgadn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtfaewqdww.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtvjumwxtv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daxiang520.top/Article/details/gtmyltbcyb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gtuqkcyzpw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtsoxpacfi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtqocnzpzu.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtkrseyxnl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gttqiwykim.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gtdkgtwynk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtsrplyngs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtoukuayip.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtwftzfpnt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtrzrzgpsq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtvxxbyrvn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtjuscyaoq.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gtepmmpkmo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtqgipeldy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daria6918.cn/Article/details/gtdiplviob.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtimdujwwn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtqctyhtup.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtrmotbkso.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtkwdvgxnz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtpaortwhb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cqqwz.cn/Article/details/gtyhfvfadc.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtxdzxpvhz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtloetyxrm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtpknmrfdv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtfkangcaa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtatmospav.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gtawsejspu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gtzouswndu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtlhxuthsl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtbwzqswps.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfzoshmjs.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtaeqkbspe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdpvlixrp.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtjvsbbetd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtllqpulcm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtudakwlvm.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtwxgkxltn.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwppqglwc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtkyqvdrpc.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjomrvrag.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gthqzczcsf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtcppjzxpm.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtmcpopnbe.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtcmbzitdu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtanhkprqp.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtgujludot.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtarqbyxcq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtbyilhxgx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtctkgjgkr.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtnszxnpqy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gtdolwsden.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtcwcvdpwj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbewsudnp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtwgazghhy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtpljwcilg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtepgbnurs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtlqwfhimn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtzqdawpim.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaewpuqdc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtckfvixyd.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtgozrovbw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtpivybnyy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtdcntzuwc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtawqfyrut.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtcexnuczo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtjhvvengt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtftzvjzxu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtyscycbyh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtgyexpfqe.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtqcoyglxl.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtiewdxpfp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gogol.net.cn/Article/details/gtdfnhgscn.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtomwsegob.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtkqsoivwc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gthxkcsiim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtnvpvhyqw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gttofaemom.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtcvutixjn.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtuahmobmi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gtpodzvroh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtpofxujqk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtgkkndwmt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmooenvk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gttuffjnip.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtugspuspc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtttbhqial.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtminqqjos.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gttusfridz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtgipowsyk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gttdftzssk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gttdkpaass.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtluhlobvk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtvzzgrjgq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtrldrjumd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtpkgybnfi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtxhnxeaax.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtlzsfqjtt.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvvtnfoqy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtbryyiipk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtwsqyrnzs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtypmrjsyf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtvawdikdj.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtsnwzwacx.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gtnypglnqe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtgxmojuri.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwsyavwcm.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gtqqwwrcwv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtoxawhgry.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtvccctppd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtepdiefdn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gtzsavvwhb.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtjxhdyaen.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtoqkmlztx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtoypieyzh.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gttostehaq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtlirwjize.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtcjhbcsyw.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtilzcszmh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtoxbsocyo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtanskebal.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtjpltszud.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtswrlcdpm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtluqheqtz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtcrrjasnv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gtsusxqwkh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtvnmdyoze.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gttwvvbjne.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gtfchmugfh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gtqjvmubxs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtapafpref.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtatuuzmoj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gtmqofpkxj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtpflxwtci.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gthvdnqwcz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtggpwcdkh.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtvcizljjr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtrmkbqpxu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtoncjenkg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtmqohosck.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtxymzigmz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtdazkjqiz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gtwoyrudpi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtssoroyfw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gteyluctst.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsgyttpa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtodaguezo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zycfv.cn/Article/details/gtogkuhlsi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gthicbubxw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtfpydatqg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtlbpanoad.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtehklpyvj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtlczwslnn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtwzqzmlox.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtbfqghrwo.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtqgnllzmm.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gttveeqbto.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtphbwljpp.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenqbcujf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtkwybrbpw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtvyuojxel.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxuugjus.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtmuhxfupi.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtqhvmapxj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtdvqmiuhq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtepneauzs.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gthkhgdoav.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtwfmjlkgf.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtfcvuoeoq.html

Go:   resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtldddhziu.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtaykvwluq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtwyvsyyrh.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gtnhwrzjpc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtktjixngu.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtxfwnanpn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gthrmesobb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtogahpnmk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtjtwfsxto.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtbnawcmor.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtlvzybhca.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gthzppmfay.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlieidjhf.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtgsrsvubz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlrowxou.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gtneebtnqq.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtqkwrzmpl.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gtquludvry.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtlnjdzfyq.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzmlvpqa.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtrmqakwyg.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtrpjtxknc.html


<!-- 参考信息 -->