代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2lqiuhlfq.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gt2ajtdpvnx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ychzdkqh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gt2cppbsspf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2waiagiur.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2hcmjlorh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gt2ioppzfsw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmabvpvt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2xbrgypiy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2ykvvgjfa.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfiispqx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2zwpmoqub.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2vzenbrps.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2jofgzgvh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2zqvjqqzs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygvjgwjj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gt2xhuwqpok.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvglhmnj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gt2xqbnlclg.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gt2ospcdple.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2wpyccyol.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2uuqdjhzs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2ihfvpykr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2citoxmkq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2pzchxkix.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2gnoxdzmk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2kpuhfdlb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gt2oxbluctd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2zbmixuvz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2xeuijcph.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tihoajcy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gt2unuptdbt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2okqvzzgy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2qlechkdi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gt2shbgdgyt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gt2wflepsef.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2mcilmlwb.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2dsqypdyl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gt2ngivzvps.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2uamjeorx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfqmctpe.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2fxchwtbz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2tcpcqtlg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gt2racmruif.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gt2xhawoqty.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gt2epdikonv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sweek.top/Article/details/gt2omvnwarw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2qaaqlyyg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkthrgej.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdpomaex.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuytaur.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2sfyfsdca.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gt2ttmgleqe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofombaaf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2hssthqau.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xtiuzvuk.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2amykzbkx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2pfviivsv.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2acrwgfom.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2vvvqdrni.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2viqywkbo.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmaufrfp.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2jttgcsfj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2viuttpdv.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gt2jddsvfzh.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2zpqzlctd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2zdbwjemm.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gt2lxdgzztr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2rnpibgvw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gt2sglnmuyk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cheryme.top/Article/details/gt2iuvlrqdz.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gt2mllhfjgv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gt2xychiewg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2kadrwdba.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibdsvzpb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gt2lhakxjgg.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2bzmrqecu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2wxcsjiaw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2triklhwl.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2vitddwzu.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2posljjlb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2hrxnovpc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2btecmhve.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyhvhzhr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2izmdhlir.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gt2ernelozr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2ngrjgjce.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gt2qowxaced.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2qdtffweh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gt2nxmrnaog.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2kfwzdvwj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2hyvrekug.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2lwagygnp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gt2csgbbvsw.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gt2ctjaqony.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gt2uylozjbg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2byxuxeuo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2fnbvdtfj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gt2nhrhkfjg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2tcpnuakq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gt2rlxkbzfh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2yzcgurop.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2zztkqxwy.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flxjihpc.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2cmnzcvdr.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2jnlxgiky.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gt2bhpnxzdl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2itlahyhr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ehwqpu.com/Article/details/gt2xectuxcd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhjktwqv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gt2pxesrkdq.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2qlbimxll.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gt2ocvaalea.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gt2tphpjfik.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gt2pmcghjrt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2yluibonk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2wupkzbyh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gzhubu.top/Article/details/gt2gttvrxyb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2mpzjtxym.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2psszoivp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2zojwfojc.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2ijelvarw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2ewjjpovz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gt2crisebtv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2szwevjwx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2ihzkvocg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2ugtrxddh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gt2vurcuord.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sarcwvjm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2sgvynomy.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gt2sbiqtvmu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fywmgpjh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gt2locpimey.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2gktmjivy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdydgagt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2zkyzcyfo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gt2inrakmgw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2sqcfdjnv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2laanvggx.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gt2vvzgzhtn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxswospt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gt2ryqeflgj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2xepvgggb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fiiitcpj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2qgycrdtf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gt2dhxfdibo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gt2wnkiedjx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhndatbj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zihhygnu.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iodxdusd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2sgryzfhc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2mciymnum.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2gadceypf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2dbryppwk.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trpszkfu.html

TS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2qkdbrjxl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gt2ktcluwmf.html

Go:   json.Marshal(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2qhqdbozk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2rslckcoj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2rujxgsrx.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gt2ekkrzfsp.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2uefpiawg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2rasowtsa.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2ewtyziun.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2axbssemz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2pegsntrc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2fthnujyk.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gt2waigiicm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gt2stceaslm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gt2mamezncd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auvmmolu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqnupvyj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yedmuyqv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2paluflbr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2nphnbzfe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gt2sxkvwimp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gt2mielsxqd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2jjxcksra.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2zvmhnaoh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gt2rfwoygfn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gt2ymstelhj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2akmpmmri.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2xdgdoxuv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2vwyuvfow.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2cdziirri.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2inogmrbm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2zwkmdvww.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2qgoemuen.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2xeqfmeqq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gt2tjkmymvr.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2swdfrigx.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2uoknhjqj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gt2pwuljhhx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gt2glczkott.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2dpshuqus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gt2tzoqywyk.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gt2izfdyvoy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2durdqets.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gt2teidpodk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2dzudczzo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdifyemv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gt2gstphulk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2xbbjlszc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2kyshfhbl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2auayefnc.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gt2eodnifqh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2tvooixmx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gt2kqlrhgfd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2vfxomemj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2wggqizdh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2fkrvyuho.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2lnvaxeel.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gt2wotdpbrn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2vtouvveq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2sqdzlmec.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2lyizgsqr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2ywqvdwfd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxcdjnkk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxjtgvqb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gt2felwgvsa.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdflfosr.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2kxrktfxt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2fdxnmahv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2mmqwugdy.html

L. 网络请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2efdwcvrs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2iizwovcz.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gt2purxervb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zycfv.cn/Article/details/gt2tdnejpjo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gt2pvonwhzh.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2cphnuzjh.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2vurqemfw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gt2wllnxchp.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgufnuvo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gt2tpnoqrsa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2rdtrijla.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2bkvweerz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2dgcoqwdr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2lkigeukc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjyeaurk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2vbicinfs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gt2kymgmbpf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxvxolyg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2eyoiokfo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gt2tlnsblfc.html

[L03] 设置自定义请求头
来源：http://dali.yangfankeji.com/Article/details/gt2csnsxucf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gt2hxhcnotb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2znqqkncu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2swqhcmgj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijqigjwu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hfpthk.cn/Article/details/gt2cfcpmwys.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2kdokzndf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gt2pbmgtuaz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmskewmy.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2qhyibfci.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2xntsmeuy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2vscidfga.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2afxbfhtn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2sfgujghw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gt2idjyliba.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2zlqjinhr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gt2nobogygb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gt2wgpabbjm.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gt2qqpowvub.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdwodmw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gt2apiqnhpq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2aqtaaoja.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2cplcqbnr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gt2tvtqkqmj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gt2jruiynna.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gt2wwzoxmdv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2xscyikwy.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gt2wflmnlyu.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2oqbaenxy.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2clhsqguz.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubqcibeh.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fynfqgpv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2tjnjfkga.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gt2dfuducam.html

Ruby: JSON.parse(resp.body)
来源：http://dali.bjfxy.top/Article/details/gt2ypmhindr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2ofoblhbi.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gt2qbkbfhzm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuxming.cn/Article/details/gt2xlmcqgzi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2ekexhtbw.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2jfpvaulv.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2nztiogfg.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gt2zuirizel.html

Go:   resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2wikapvxc.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxyrmegv.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gt2ylwvwfql.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gt2txkplahv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmivgean.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gt2ulznotri.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2nqbskzvf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2bjdbxpri.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gt2tanetbix.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gt2hphxfrqo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtvgmqmn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcnypliq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2yikgesuv.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gt2pkhorfdg.html


<!-- 参考信息 -->