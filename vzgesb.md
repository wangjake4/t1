代发 wailian999

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygcqyggt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.meibo888.top/Article/details/gt2dtietffb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gt2bcqhfwcs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daxiang520.top/Article/details/gt2uxsxuhpv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uodivqfg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gt2ysxsxort.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2ebkxvypw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gt2ujtnzcpi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2trvezpdh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2qezetuya.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2zdttqbmr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gt2hwckmrll.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2smxcsvvq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2zijkgnck.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2mgtlpsqw.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gt2ojbbxthe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2thzlrtlc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2fdclexub.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2qrenqylr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2xsrvogmp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gt2fklqteqe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gt2beedpaxi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2odenffvb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2sutbdkeb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gt2acngszax.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2amjbldye.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2qhmktdtb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2jpurvqrp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2gpioyteg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gt2ghfybvdq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2gauuraoa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tiakunuq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2nzffexpw.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gt2ghykrksl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efvkshya.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gt2fmuzveuh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gt2wxzjpdoa.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gt2aesdlbpq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gt2coisiokv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2kjwzkojc.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gt2qjibfdzz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gt2zdehgebg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ybcxt.top/Article/details/gt2tnmzrnra.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gt2rppmucsx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2cihuasfn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2cskeefwl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2ludtakbe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2otuarctr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cucudq.cn/Article/details/gt2hcuuqswp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gt2vegqurzv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gt2evxbxclc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2jyuwxlek.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2enmhnqqk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zrdkxiej.html

[J01] 获取当前时间
来源：http://dali.smart0.xyz/Article/details/gt2fkwyfrhn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2yjxqyzzi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2tzlidjia.html

JS:   new Date();  Date.now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfyqyipg.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2dyvqlgcy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2kiinbrzv.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2qotucrnr.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2ftuiigce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gt2hbfsoajo.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2eoobszxo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gt2grfwijtg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2zswjgkzt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aturlqfe.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gt2xjqklioo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gt2prceeqjm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aeynzhgj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2ftmsjmir.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gt2lmwazncf.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2xvviajmz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gt2xbbvzioc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2mzgxgibx.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2pjfcpgpf.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2robmncqz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2fdtwslfk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2eylpsbuh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fygsqafd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gt2uxunfhhs.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2fwjzciwf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2hatcesac.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gt2xljipeam.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gt2apawwkdy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2mlyvsytv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpqegptq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gt2ilnuztkx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.havefunace.top/Article/details/gt2edvlgcnr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2bmryowoi.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2nznvezqn.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gt2mhzacker.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2grkdwcjz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cagiifse.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2xenexejj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2tcfkcadi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2szwnkxum.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gt2jvjawtpa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gt2fhbioqte.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gt2aagednld.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gt2pgtmzfyc.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2csyulsip.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2pmahekzv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2bgsmpmwk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnqzz.top/Article/details/gt2zibvojna.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gt2mjpudbgo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gt2sjazahqw.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2bgunodcg.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2ikppexhi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2wxmdtufx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmhlzcns.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2sxymkcrl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqvauqtk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gt2pazlfydw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gt2zuqmyfcs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2jaitryhh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2mbyaljsy.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gt2bthlqzug.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gt2cncttgab.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gt2rkoreqgj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlvnpzcu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2entbwzxk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gt2dkgkkzcc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gt2genfmolz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gt2gewwnadg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gt2xtjumdqp.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gt2lyedwygk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2slahcpyg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2pfztdhxn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2brswprkw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gt2vbgxgrva.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gt2sjdmvgdd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gt2bdywvumt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2vibjcxnh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gt2updvxtsk.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqqpfbju.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gt2xiszhyjh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gt2ywhhvsqn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2pityhisa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gt2irlhzxjx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gt2nbexjxwd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gt2iwlmvnce.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gt2bezsbitz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2sblxxgnn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2giblkvfi.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gt2ifzlavsj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2laenkgfl.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gt2qbkjkgvm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2tqwoftlk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnfufbpa.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2elbjiahs.html

TS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2nfcdjyaj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.andypj.xyz/Article/details/gt2qvzzaalx.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gt2bkqbgtfq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2ifgfzuxp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ilgjqdvk.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyewvvzu.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gt2jwazxvti.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gt2wkdfxxas.html

JS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2ovglanpx.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2zmwcojmp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2qbcfulcg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2jokjfquo.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2onbghdok.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2fwphbwyp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.meibo888.top/Article/details/gt2fbitzwot.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2mmpoatql.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqpbcrud.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2igguibul.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2xritqdic.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kafudnrx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2wwfkhvdz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2crmwvbvl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2pgdqhuwr.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gt2frsgdxla.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gt2uzdaqaxq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2ithbspet.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2mtyvphiu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhlsutlp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2dgwhzedj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2rlftzscs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xabzncbr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2calquhhv.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gt2igwzzdji.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2sndrgeml.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwwjjlpm.html

JS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tltawxhj.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gt2ujupcakw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gt2tmrzlmot.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gt2iyyotouo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gt2kwoclopm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gt2fqmooxie.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gt2jlypqwtl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2rzomevea.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2bwntbbue.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2olouicvp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2sclrrduq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2qlhvawka.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gt2qinwwhyo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2ydsqioge.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2uluzoquo.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gt2xgnbfljz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcmzalwj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sufxvd.cn/Article/details/gt2zdchkmul.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2ivsgwxcm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2bcfcnnew.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2jmdtvefc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gt2igvqhyap.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gt2mcilhbhu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2zixbuayw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gt2ytqcjpst.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gt2hegbftyu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2oprirhsa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bboznwpl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oeisfrmd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jyoumei.cn/Article/details/gt2ccidnjxq.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gt2ljkmfvus.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2coljxmvd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjdxtysj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hnxffvse.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2lzvnykth.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wfevtxlh.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gt2afazijpv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gt2ugaenuom.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftqcptsl.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2cmaxphbr.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gt2olbajmyi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2znravymv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gt2sjqpgpas.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gt2rviyrbxz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgfzy.top/Article/details/gt2ylitsrjk.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gt2tzvblhkt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2xjxhhoax.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gt2xkkivtsy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2hpqwaszq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gt2xhfngrne.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2zlycwkjc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2orfrntsp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2ylhngsnm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2dercnrqg.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gt2tqdzsdjx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gt2rbhoktcn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gt2eucuyksl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2wasvvooj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2pfowktaq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gt2reovwmmn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2pnbskzar.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gt2lkzvqfiu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2dylzdalk.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gt2ncgfaxby.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gt2eucqbfcc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbhqkval.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2fkyfgcci.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2gijfrhzk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxqcldsq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gt2jyvdpbbt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gt2ifpqxull.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gt2rorqnoqg.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2zfawtsza.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gt2zzjjqwyk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aizwys.cn/Article/details/gt2beyvhkyj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2mnaqjice.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2cryozpvi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gt2folombjm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gt2vjkxjcxi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gt2zwoehfxx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssasxcup.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gt2nrjrgswj.html

Py:   resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdfxnhdm.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gt2zopakexh.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2yqbftqsg.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2buktcbci.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2ijblkqai.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylqbhmj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gt2kbumdzke.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2umxbocgd.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2tychbwuu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2jznwjjpn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gt2ppyhobgj.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejspyhdv.html

TS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2wijxzjei.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gt2penuocof.html

Go:   resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gt2cgnnrhlg.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gt2gehhkwam.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2tmciungi.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gt2zbzpfwkc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gt2zaggoqjx.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gt2zbdcomla.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2peomcynu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2sadgevbt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2tcqexwjb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2evcdlgkq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2baspzrul.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2dwnabyby.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hecrtrpi.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gt2kknfddns.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2agoizvwg.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2bkdblosc.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2owvdtlqr.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gt2ijveueep.html


<!-- 参考信息 -->