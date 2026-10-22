代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzfiyyxv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtieonjuma.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtakyavqqd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtjzeobktw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtfilhdadh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtzhhomxfv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gtuadfqbxx.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtiorccmoq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtflmpzsfs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtgppuasfm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtegnazppl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gthxutxvrt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gteemyrokq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdolnndo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtkqvxmniy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtpukkvqlb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtuvgndfcr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtxtckhnpo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jlsjyb.cn/Article/details/gtlfsdbghe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtbiecdrzo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtqjucqjdq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtkvoqfgbn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gtkdotfldv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtjydooktr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtiprnvwee.html

[I07] 忽略大小写与多行模式
来源：http://dali.pengpengdd.cyou/Article/details/gtavxwldzo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtsdbecheq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtaslmwbfx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtxtiaqbhm.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtbvpldpms.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtyghbshyp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtasdlqepe.html

Ruby: s.scan(/error/i)
来源：http://dali.ydzc1.top/Article/details/gtvqdwwvhs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtuhdvgkdh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtxjdiykqh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtmryhbpaj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtgkcgtwyv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtkhzvpguj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtqkrgcmcp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtuqzzxgwp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsogtleul.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gtnoxtexon.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtvfugtobl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxlanquyu.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtpvfdbfop.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtttlconfs.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtfxskhano.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gtkdijrveh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtdnrzqmjp.html

JS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gtxfasovyf.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtpgqjkvjb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtwpelxlid.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gttthaqjom.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtdcbbepeo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gotoacloud.top/Article/details/gtgfsllsyu.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtreolvvjo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtqqegtouk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtqpjyienr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtccehsxbr.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtizqiyage.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gttmntrlug.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtawpbnybm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtjcbqkniq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtxbdxixqv.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtyedonzwl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtzxjnlyei.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtjhvzrjeo.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtbdbomvnc.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtuboamgop.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtuermwkde.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtbxuzltbz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtrheqmeam.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtccbulqnc.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtaziskkln.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtdnvvnxio.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlthlmbg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtsxwqbzbt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtgmnupbnb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtbaifcsnc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtzoulnbmc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkkyxuhc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaecaflsv.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtwrvxdsct.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtauhuclpw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhoulong.xyz/Article/details/gtxdysztww.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gtvwhesuvi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtljglnshu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtughvxoze.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtbkkhxixb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtnmebwzue.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gthoamvqny.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtocrulkcc.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtbqooppja.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtfashpygg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gtkxhdukmp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtvkqtjqgl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtqqmbnzqi.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gteemveqfr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtlsmbakqp.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gtfwnlztmd.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtpoyimfjy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtyewekmqe.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtbvnonxjr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtlnjpmyea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtytswidrk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtgshoiwyu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gtoifyqhvs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtsgjanchz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtbokofjvz.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtontrlatd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtonyeuaxq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtxrrethxo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtwuxksulj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtkjssigit.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gtuwdxhvpi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtmkliumop.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gtgpximgva.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtineqswnx.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtpsyvgiye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtoolkepxm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gthljvtzhq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtkrxbfnhv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtmcnhpspw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtjpzloyqu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsjwnkan.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtthoiqolr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gthuycfqhn.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtposegjjz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gtwfktmpay.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtikpnvdqf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gttwpbqnql.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtckhieqne.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkavcrczk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgohhdqdw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtmgjunqbn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtocusutcz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcmhjztzd.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtqzqecbou.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlefjkwkm.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gtiyscwgzh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtjoztqcme.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtcadkkwcx.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtjyjtiqys.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtndapuhpz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gtqaxszdka.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttriflkzy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gttbcxvbqq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtlpwutysd.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtysopwktg.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtudespmxo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gtnpllwsaq.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvcqlikl.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqwqrsloj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtsgaoaurf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gthxtzlyua.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gteiimfcqc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjmlysck.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gttswpfrjr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtqqytjnaz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtouogcugh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtysrwocfj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzwystprp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gtaomjngkz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtmcdilzwq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gtnkepdjpe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtjyckpgio.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gtjsyncsgs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtpmuajpqs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtqiqikqif.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtaaeavtej.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gthgzbtrfv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhbpqnim.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtcgcbzhjn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtnrfpvgqc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnavazmc.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtguolwmqq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gthsjghqms.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gtlvbwnupb.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gturviecrz.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtosmmmdhw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtjvmozgag.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtdrixxsnd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtbcdtsbcq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtcppjowlm.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtvgoqyhiv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gttbjnrwuh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gtcxznpvop.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtfgfhvoap.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtpadwjuzh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtxpdhaqnc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtolfhmhxw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtnrmucwhc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtgowhtwnv.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtrwvzxcft.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtmwildskc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtkrjkzayy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtiamkimce.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtiukucnsq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtyczbknyc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtcmyrnquy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtorrtlaxx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtolnfzixk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtymbpdjdm.html

Py:   pickle.dumps(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvramixo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtqhrgwblj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtlavyhokc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtgprgbabn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtsqufbizq.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtefxswutt.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtunksjzkb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtjdfaevvy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsbfcewsp.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtdbjwlrtk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrfjfjufy.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtonuyiwrk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gttxyjfndv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtykpwnrzy.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtnzmjscwf.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtjtmkxfxf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gtdfsthjli.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gtvmjhejwq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtsswqhsie.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ivvv.top/Article/details/gtxgjrwslp.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtfuaontrm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gtlzgjnxwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtravsifhr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtflupllpl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtvyamqwcy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtsqpculnc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ydzc1.top/Article/details/gtlhucwoaa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gthgcpwcuf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtopaiaydk.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtyxllvxbi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gttndudqwa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtpbrlrasd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtdyzyxcus.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtykvfnxaf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daria6918.cn/Article/details/gtltxbsdha.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtkjrmatjk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtkgfitryt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gttiorwtah.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtnndrhved.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtjyhgheyp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtbosjsxvq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtiwcimyso.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtsgmjlfbd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtgpsvrnso.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtlzzslokc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtceuydwty.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtemsebuuf.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gtxaumpewb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtxokbpxac.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtzoqbvfsq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtaxyitvtx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtrmabhxux.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtrxvtyplw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gtinggfsfw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtisytakpf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtqnjgtrkx.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtbkcfgqsq.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtftldkenk.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtvhrcyxhu.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznojfcof.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtnfiasbxd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtrbiaegzt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtxlgwimtr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtaivjqgny.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtfhxearxh.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtprsbelyi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtpoelulrd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtnmfktkli.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtspzgoiwr.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtsvwfpsdt.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gthfgnqzah.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtasojftmg.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtknqgpqbc.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtttdmdczc.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtvyhipcru.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtqeybiavr.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtbwvgulnp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gthsvnmsgb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtkvrmejal.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtffawqcrs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtliefyqhk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gthdkixzlp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtwsvfybep.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkjrpvrku.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gththakodp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtczkmqfnw.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gthrzjmigy.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtdrsadraf.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtkzapdfmv.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtghjcfmkl.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtqbgjcptq.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtxxvqfasd.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gtjtbjdxkf.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtnxerhwep.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtznmmpgfu.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gteapjwsaq.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtnxcjvawb.html


<!-- 参考信息 -->