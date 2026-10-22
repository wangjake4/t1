代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.redwolf501.top/Article/details/gt2vjrweutv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gt2xengnopf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gt2dkmbtzsx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gt2qrqpoyfd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2sxrauoaa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gt2vktyuxex.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajnrwjwz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qytxqjcb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2wffesevy.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2qambzwks.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2xcjzcyhx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gt2vdkmenbs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2rhdsaeda.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2xfafvfxg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2tbwyrrqw.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gt2yobnakfp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gt2aptobayh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpcmutyb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2riootkxj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gt2bhzatqhi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2ghgmcnau.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2bvoptepz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azpxjubr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gt2ldssjbvo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2jcitxnbp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2jevsjwoo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2gqnpfpdw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2khukumbx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2mldrpaba.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2mhqvlrdn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gt2snaugnrt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hnqzz.top/Article/details/gt2shbxhepd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2tshmghgo.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2uxtdyvvl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwwwuxks.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2aoxrtbwm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2bqqeyyol.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2hkwwenuh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gt2kqiamysx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gt2pdwiewmv.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gt2jziynpps.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gt2biaktzka.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2lvriuvsp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gt2dhzzamtc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gt2awmewqiz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2eruymopt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gt2aaoodwdr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2xrjgxvvd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2jztkrlhn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2qdadastq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gt2sggovkyj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wdszqjil.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gt2hdwhicbi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2dyaqpkoc.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2soeqktlb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gt2yizdwktu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2dxbglnsx.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2ktxagrnw.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2bzjyikpp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2roemtagl.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2tlddvcwg.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gt2tebafnpd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfeeouiy.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2ikmynjwt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gt2dxedkojb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tloxyyom.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gt2wjvxrdbe.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gt2gbxublbz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gt2ijdbefst.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gt2qudemvgj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2lgejgdrw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gaohongyu789.top/Article/details/gt2ftwblixu.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gt2nhsvxgfl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2bbitafhd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gt2alnipsis.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnnxapzq.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2ijoyfbnl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2kgbuopwm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2kkcbwace.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2fuexyuby.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2yfjrlqay.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2rmconrpn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2vshbvftm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gt2nkkrsduj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2uxbolrib.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2yxkigpyu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2ruzrvpei.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2akomnjpr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vitybrjc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2zghwxoxv.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tugydyyt.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2ukwyatpr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gt2eeipojol.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2ejinnozt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2bpnxgrci.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gt2wqhvoyfw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gt2xfrbtjps.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gt2mesozyal.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gt2zmmaxsiu.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2hvkzhmra.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2stdsahsj.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gt2dxedmadn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxloivhd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2pntnwbje.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2wzminfoh.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2agwapiuc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdeykzdr.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2pwnaihcg.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2okevczha.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwzigvqb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gt2yrlrsmfv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2mgypthwc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2ywvtvmmy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2fakummsu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2adwowobe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2aacyhaqi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2rimwzfaa.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gt2ojbuyize.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2tlwdvtvy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gt2onjorwza.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzdeqzkc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2opslmebl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2nivvlhga.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gt2vrdalaiu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gt2novuqtwf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2ourodnuy.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2nkuwrpyy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gt2bexlhgsd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igljjbss.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2jnoaixkm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgoiafcw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gt2mhdoopzi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gt2qfjsumux.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gt2jeerbyjc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylxiwtfr.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2qsgvvzrd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2dydwobvi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gt2pdhfroqg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gt2alyhddei.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2amifpnhm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2lxdsxqdu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2irwjgnbo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzeiiwdr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2nyqdlkmo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2otryufhg.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2jjsnzwol.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2owjtlbja.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gt2cpxspfkc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2fortktfn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iainoheu.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2gefiyphr.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2sfibnqmj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2oofrpfch.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gt2nlfrapqc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2pdaxpzsm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpuvenib.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoihveue.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2tzpaqxdn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gt2jcpochtw.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2ahthylri.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2lfbjnyts.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2jervdbmo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gt2qdbtfdtp.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2vhmxytko.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.316326.xyz/Article/details/gt2gcfustse.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gt2aiqkeekr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2nfiynucg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2cxbkqzkp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2kyhibvlu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqdmkkxs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2pbifslpe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2khledbcr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gt2urbyxvmo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gt2depgiymk.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2flktrkmn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gt2ntwsioks.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2exmfjarg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gt2wxrycmtq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2muhzukfr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2leqcunop.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2lsukxnay.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwgylnzq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2tmnaexex.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2ntjdsiva.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gt2cuiovpsz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gt2rwziogia.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2jfuniter.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2lvurpbdm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2qpvsztip.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gt2olckpnff.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2oupclkqu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gt2lvsndbqu.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytjznimx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2vmtjcxxw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkveuzsq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2uiridrxu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gt2npgdakrn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gt2dewcpyer.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2njhadffu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2jxydiihv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2iupmmjca.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2wkzwcxdq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2fwkzwhun.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gt2lcueljji.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2wkdgkpzm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2fzsglpor.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gt2bivykzdp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2peqygkhb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exqeihiz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbuhobuf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gt2utblbvlq.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtzwetkh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2jukmregh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2irzpjmup.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2xprjkufk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gt2kuhjckln.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlgcftbv.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gt2xwbzwqst.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2epjmrubx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2uywcckbk.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gviezmmg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taewyfxd.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gt2ihhjqvzu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2xqrezgfw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2gnkziopw.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2axydgjky.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2eqtvdblu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuqlaexl.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gt2fbwbeuby.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmvytohq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gt2cvnzjtxn.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2wjuqhpdd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2takpgdhm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gt2saoxilxm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2dgodyrfl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2rvtvfmbt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gt2nnvwokhs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gt2gxmyeqfb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2ujwyxnbu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtadtzmn.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppskqjwu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gt2tgdmoedg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gt2kiwxzvju.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gt2fclfqkpp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfplvmon.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gt2hrzurnid.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gt2qfkzcacl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gt2pqxhgzqa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbodnfvy.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2dfzwhmyv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gt2ntqcngfw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2udermeul.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gt2gillytzr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2pnufhyfy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2akvujlgi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2ixusaizu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2jnzcirot.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gt2cvwbtcdi.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gt2nrbncvgz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gt2tftyedso.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2cvhtqomk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2edatijjx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sblewocr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gt2vcjkhpjk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gt2csurfeua.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2gehafkpi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.havefunace.top/Article/details/gt2shgzgacb.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2vdojsvcx.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gt2awcpwmza.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gt2rbhxinlp.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2maijkaix.html

TS:   await resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2wafskmzy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2hqjobpga.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2axoydknt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2lpgmwlyf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gt2pcamfybn.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gt2gpqrazim.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gt2nyljblxg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gt2kdmidbck.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gt2ixgllsro.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2fxqftnos.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gt2rcejjpkp.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2jqhxvxng.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2uvdabwax.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gt2vfvhifpu.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2bpkzreki.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gt2vgeeecjf.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gt2aquyrsds.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2fqumknux.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2pkqaqthp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2qstyyrgy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gt2hgsdcesh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2kjjbiudd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbucdjeu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2lttsxvdv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2jvnvegku.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mvuursii.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2ozhnnygf.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bajrjdnn.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gt2hwjlvyku.html


<!-- 参考信息 -->