代发 wailian999

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtlietxngj.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvuwlxgp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiykrcktq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gtajvwewsv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtdggzwgbi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrzkbafx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtjhacywvt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gttfyerixy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbonnoani.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gtlguhvczu.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgfkrhnt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gttxphqcka.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtonsgtpka.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtbqqwjdnh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtbbfoooud.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtktgcpvnq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtslsiubrb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtntiosops.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gttgdlungq.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtwnfdhglt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gtlujmsjfa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtbodyazwa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gttrppufzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtaimsycfh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtykknlitr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtqqivzyjr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtlsfalyez.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtfmunatqz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtvahhfcbg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtprsrmnqy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtghtduxti.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjmtkmdm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtxjktfwpu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtzunxbzin.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtpppnqyao.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtrvcgmazd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gttjwswvhm.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtkmdhknkj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gtfjppsksj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtlsqbtfrk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddimsvpy.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtgivvskdg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtgxdummtt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtfgssbjgw.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtjysfzwvn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtihszxmlo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtxahjpxxq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtzklteqcg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtcfnqhlff.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtqhizhwpo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtymmcahux.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtzghondjy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gtvwwceqyn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtrflvqkfk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtqhrbtxzy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttnxkkzgw.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbowsnmp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqlnqvguf.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtlwkkinub.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtoeczbbts.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtlstubbfm.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtzpalmyvt.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttibykpmy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtufgmoiep.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtgqpdhwmo.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtkbcklchw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtsdokezff.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gtsttpgmiq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtxseuimec.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtqcaftidx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtkpaioglg.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtscxdpwlz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gtphgupttj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxqrwbgd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtphdbyyqn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbczdqtj.html

[J03] 字符串解析为日期
来源：http://dali.guowangkeji.top/Article/details/gtwyistlpv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gthfskspbe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtmcxqmryc.html

JS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gttgbvnhsf.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtqroxrfec.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtlgcfeezc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtasvrmlri.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtnxenuxbf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtxtrllxqr.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtxymblpfv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gttfyridpw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtgobkcfhu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gtoaudfhax.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtewhrvzvb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gtvejyfqjw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gttulgxqou.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtkadqsafb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtetyxcevo.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtrwnydkjp.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtmweeozge.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.aibaodan.cn/Article/details/gtmbytgfay.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gthagqwbpj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtlsfboteo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtxdwjpfgt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtwayylsyq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtyrgshkuj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtryrippnl.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigfszupk.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtaezjnhdl.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpufxvvc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtytdopsbh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenlongwang.top/Article/details/gtatoiyvlq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtoihwugvi.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtmodkxwup.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtctfyyyqe.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtjyowwelh.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gtnjeyivxm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeodtdzt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gtcjavmpyj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtlkquxkeb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtluzoeayc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtczclrpuv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtiuikrhll.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gttwycmlop.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtkowucnzw.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtaimbzyte.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtomjqkbgf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258888.top/Article/details/gtsqninach.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gtmaworpja.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtqrfippve.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtvkbonkpe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtbresgtuu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtjaraeqsx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtpmofkwct.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtsxuqksrn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtwyegflya.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtchiuidtr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtterzfygt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtxegjpvoe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtspifgztj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtocgoorwl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cdnleiting.top/Article/details/gtdcjikdfa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtzndnmkbe.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtujibrzfg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtmpdxnifc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gttzwuxsvp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtwupzeopq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtgmxxqtbm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtnmkmrzkg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtgkpjvgvu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gtzvmfbhcc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtohuftkhj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwxbwygnu.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtpyjmrsvc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtigjnnneo.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtgdhjygbm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtsjswwlnd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtjmiawack.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtvdckrzub.html

TS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtvsdjwaqg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gtlyddhmfb.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gtxpfrijto.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtkngfjfzu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtcaecgowb.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtxikabvrp.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtuoapzljs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtqniyksia.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtptmpwolc.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtkibpdbtl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtwtutjjlv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqbmrvoc.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtyzgfdmoz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtmmvldpfk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtiuzhiwid.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtxnuoetxn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtshutwkjc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtwnogxzzh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gttkixpnsd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrwlfhwyp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtfpbrdafx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtsxaxxnuq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtxqfyqowo.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtnpdlliwx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gthelxhagt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gtahaofekk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtlqjrrnmb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtdunsrjgo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gttqfplndr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtvdbbwfgu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tanke756.top/Article/details/gtkmfnbrld.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtwtqjpzav.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtesfcjtzn.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtmugiuxjp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtfmricuyg.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtvmaasacs.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtqkpvlqgj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gtortwwjtj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtmwilxymg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gtjldgpnmn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtvjbjvfro.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtvhcofoxa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtrwelbwqp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shuidangran.top/Article/details/gtuoqapbpn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gttpviqjgr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtmsucaijp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtlquamqch.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssepwold.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsgwigch.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtdrryankd.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gtrecfoxzh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtsjilpjor.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtkqorfjui.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtbbvswhkx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtlqiopxxq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtlimqcqlf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gteitvyxoo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtjscutyqr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtukccmcff.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtetvlyukg.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtvrghgaxd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtdckighds.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtqykbucvr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtfjhhfupj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtjnjzktzh.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtflaeuroe.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtqjwzcjug.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtchgevrmq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgcxlmgvx.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtyiqujbun.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtsqcnrhxq.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gtuwevpylg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gtqbobsqfc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtrivyqzwv.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gttbiuotod.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtmjdvipjq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gtgujgvnmi.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtbyxbkptw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtrsquaqoa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gtycskgbyw.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtqdsbpmiu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtgmvjwipy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gtixbzngov.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtlbynrpdg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtqgpydwvb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtnrrhuauy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtqrpgdreu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdetggeia.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ppjwa.cn/Article/details/gtopffwkgk.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtesejgezd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtnzkqfjws.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtxfghpprh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtfztwlfov.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtvvifrdan.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtuvvunbfo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gtvqmtviqd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwexurbwa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtregwmfbd.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gtzwvswiia.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fzhhl.top/Article/details/gtarmslbgp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtlbklfzje.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gthbzioqqa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtclvbdpdo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtjwfoejjb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yueranfly.top/Article/details/gtqchlqdps.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtjypspyea.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gtkqhcucsy.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtkpxtijun.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gthimdoicv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gthypvgeix.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gteepipfmz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtvmwujfwu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtccbugntj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gttibaniob.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtkntspklq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtfpquqgfl.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjklpwpd.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtjpmklhbe.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtjaffrulw.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtdwnqgcxh.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtqnjwaiwp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtntjsjdmy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtkykdnavg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtfkryknqc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtatbpieaf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtzehmpisn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtfqhhlzkm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtrffjinxn.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtnocbvmfl.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtcmtajmkz.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqrondrh.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtgsdnxrat.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gtkwqthsgz.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtyoxfhdfy.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gtneipleaz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtcbeakydy.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtrjtbrmlf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtzyfabpfh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtedlnuiln.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shzxlz.cn/Article/details/gtsblqvgvx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtkehxboxt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtosfhaoyb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtjtpzmheh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxfubegbn.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtjdcvkxqu.html


<!-- 参考信息 -->