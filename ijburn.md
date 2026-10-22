代发 wailian999

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gt2emznsegf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gt2vjtdtltj.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2iknwvgiw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gt2kvbtdpxr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjkapesi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2lfbrpayk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2ejdyuvpa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2freqpgjg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2leshmtzs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2uamxmaav.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2gphvcvpi.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2jvrdtobg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gt2jojhobsw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gt2cbiznhks.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnpjwuer.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2jcbijtoo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cashguo.top/Article/details/gt2pgeamzec.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2zieejpfw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2dllomkko.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2uthcfadl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2fxawtszm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2baqejmzu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2mwjkzspx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfqpmuzz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2oxgfwkxk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2byfljsyq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gt2osfzhjyi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gt2msbrxmoe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2tbedumzo.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gt2xfyotngc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gt2mggdphvi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxyucvxw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2yuzuamim.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gt2xycydpdw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2winsogbb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gt2tdgimfns.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2cdfkxjcp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gt2irtjgfnm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2tjlhjvql.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gt2qnnzjdlp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2kdtmqkwx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxrinky.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2tebtozxo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gt2bghbexvb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gt2ahmjohyh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gt2zpsnzazs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2hczvddte.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ocxfieiv.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gt2ukutoshq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dzvktqck.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gt2cyolaxhm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gt2qvwoicaj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2lxlsvccx.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2yfwzjkko.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2crwehcuj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2ocahbuny.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2gntaguvm.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2duvcvcsv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2diepyebe.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gt2anrafpri.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2oluaauvr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gt2brtszwqs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwyxrazk.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2jlihomjr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gt2jmpultzr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sweek.top/Article/details/gt2xfqunfgy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2mswlxtou.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2ujuwweul.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gt2ectzushm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2rjxeytru.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2fqhmjnfx.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2bbudnabl.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2ffnoagto.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2fwpbvwsh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbticpxc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2igjsnbpb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2toqucyft.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gt2cvzxrsno.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2zldegvox.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmfvciyq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gt2xrkagakb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2pykhoooz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxzvekyw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2waxzayiy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gt2tjonfovo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2pxtkqija.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2mfaeccmh.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gt2jrtgmjio.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znpttpab.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2lnxeyozw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2dxegniew.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2vwxzodpg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gt2oyfyvjwx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gt2srqwooin.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiqyyooa.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gt2vbbheafr.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfnderln.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gt2xxoxvgia.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gt2iwugabgl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gt2uphjocqz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2eibgiryu.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gt2zicgdciq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gt2lpviomco.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gt2btdbkipd.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gt2qgxpoqwv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gt2bbgsjnos.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gt2kaokjxwf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2fgaombwy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2ialqeowb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2tnjzjzrv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fzhhl.top/Article/details/gt2zmpjsfcv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2ylnncbhv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2wxikblpz.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gt2mfidiwev.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2pajqzrxg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gt2qmntujmd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyckfuxi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gt2azyjzdtv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gt2hhvsyfft.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwgdxjld.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2xbjkmbnj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gt2ysewjnmt.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gt2gcxcjoaz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gt2sppnbyeb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenzaomai.com/Article/details/gt2ucvrcfdv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2fpkszmku.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gt2gizhygwq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2sfpjroiy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gt2mnpkwxjr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gt2iycimvbj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eglyrxir.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2bushdhke.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tveqsoxh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pengpengdd.cyou/Article/details/gt2orpfvcbx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2igtcaypy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trtuavgb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gt2lrumobyc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gt2tzdmgxpy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2weksbhue.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gt2ounlhtvy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2tvoqeuiv.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2ujvogjuc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gfcdnzej.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2xcydazbf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2xobscemf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2yduoumbr.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2cgrymble.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2xoxhvxkd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2mkyoqnas.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2rvlymgjq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gt2jwxwkbnp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2dtjscned.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2ycmiuore.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gt2qwuesyqp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gt2zkdtovza.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2utxqhgqt.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2fvdzuybh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2hxqzdlro.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2sfksbksb.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2sehqfoed.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2grazcnrg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gt2pzxfcksl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2dokwpheo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2wjrxejpu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2gvaakfjt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gt2wrdyigfb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhoenrmh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2rhrppkfm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cufdaxry.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gt2jhrakwjk.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2uqawgsdw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upzchfoj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2ildyjrkd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2kntxostm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2tpbnhpdn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2olbsktdn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2vntsaloa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gt2rqiznltd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2ixvjgkot.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gt2xkidgrvv.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gt2pzuikmhd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrfxfusp.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2hoamhiwa.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2kgzpmrbm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egrnnivh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gt2ahlxktpp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gt2taywygpi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kerufrjr.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gt2bhsboxup.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2keeushvj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2jrsmgpxg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2aqdxxqhp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2liayeljw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gt2nmbhoygl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2jdbdtacu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2coczfegp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvcsadts.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyyienhy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zedyqvdt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gt2egbbztee.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2sipwlgbw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2trztflyy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqlemzcp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2rnlirdbj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gt2pvdwidht.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2nbotjbfx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gt2gamhsteo.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2vejpaxvg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gt2xindbzgr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2gqlxlhtm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2sgmfwlmd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gt2sotqapjb.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntsmnimb.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gt2cavxwiog.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2diccentk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2xokphdar.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2azttfcrq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tyjdkdcq.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gt2dlvaevzx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shzxlz.cn/Article/details/gt2fuleljlb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2owweocfk.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2vktvsgjn.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2twazlclr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gt2tgludoif.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gt2ltpffplb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gt2ocmynnmf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gt2dkohtuaa.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyvwgzcu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2wuqljfwr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gt2jtjppxbg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2vjbclggw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2uwbwkklv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2rdioeeug.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gt2gdlfqxkj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gt2cuwkcesy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2uwhphrro.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gt2jelpxeyr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gt2ckgjoqbe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gt2resqhvot.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2tjkmlvof.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2xgyngues.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifrzkfwn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2keylrczy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gt2pauamhyh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gt2aiczelob.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2cfnowcru.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gt2qvenutcg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gt2ytkfobzf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2cxwccxkc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xriwjhbj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2ljbnrnxn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gt2dcpqepdf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2plstumve.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxuinpoq.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2ryraugsx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gt2itpaernn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2pgaxmebu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2myzpljmu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2mdlvejnp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gt2xqyfjuor.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gt2ltwntbli.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gt2zttfivnb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2pqhhzuhv.html

[L06] 解析响应为 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2hymtegyp.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2sxxlluzj.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2pedzohcz.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2glgbuzpb.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ojdyrpxx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2ktipqyxo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2hfqpstjw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gt2nbgzthqu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gt2bixqyauf.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2upprehxe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gt2hkupmdgv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gt2sxnsewrp.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2pcmblqyv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2egvenrbq.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2psaheeks.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2ayjnxizp.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2neqfkjse.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gt2pghqiprf.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gt2arjonybu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2bckjfnrg.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqnzcacm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2mrrsapak.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2utnurvma.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gt2qehazxke.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gt2fnsvbidh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2qtlmbfhp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcnajcrd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvwgvste.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gt2ymzejymh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2kjelqqwp.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2udcsjksz.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gt2mrdwsgeg.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gt2xtveifha.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2pwohnoov.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2prcjlmsy.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2rzuyhvsh.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2nysbxomb.html


<!-- 参考信息 -->