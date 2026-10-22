代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gt2vlwfyycw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gt2darwxwmm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2javvgdkq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gt2pbsgcmnr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gt2sndtvfiw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2zejpevwv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2uarvibdx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2cqagmhsb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gt2inxzcqus.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gt2ggatcdst.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2mgjtfjmy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehiwnqer.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gt2gwqutwgg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2atfffjlf.html

[J01] 获取当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcxddiho.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdofasgq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2cocsgike.html

JS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2qrnpcdrk.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2xgzbehdk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gt2tktoezwq.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gt2ioxcmzjt.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gt2ltraqhcr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gt2nefsofik.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2daoogumm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2pgdzifdt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gt2jyvixoxv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2irvjqpye.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2aizmpzhc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gt2ejqvdzln.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gt2hwlqmrxp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwihwfmi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gt2qakgzbsb.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gt2lwijlbms.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gt2zbejjgxg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gt2uyreuhze.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2ldzchxhi.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2zufgupnh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2wmsuzztv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2dmmbznou.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2pubrguzo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gt2imcugytd.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2fswgjtax.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2anxxydos.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gt2xzxblvkt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhhhktkv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gt2nngixnqr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gt2bzeacvox.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efyizzqx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2mmhghrhd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2qdxwlreq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gt2tkbajipg.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2hlenmsop.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gt2lhyauzmf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2jjqihzbj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtztbdux.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gt2kmkjgtcy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2mmzalkes.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gt2qawkfypl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2korsghvs.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gt2zdoqvoig.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gt2cwrtjfpo.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gt2wbmfxiag.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2xruyxbln.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2bfdcrfdv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gt2bgoirauj.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykwuygan.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gt2gjrejbkp.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2jivhqvik.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2byumstjh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2dwlnzsqv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gt2nzkgczqy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2ukrlxuks.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gt2trdjoptl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqtqtrtr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gt2bggglaey.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2dorrasoi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2yfpwvyfb.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gt2ypnrpbqi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2daokvslz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gt2xfmuzloj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwuiykvr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gt2nqtfetyc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2kisljrvh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gt2nhksafin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2lnkcqdda.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2lxycutxw.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2whnxyaet.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gt2qeysbgse.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gt2sziebsbz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2ucfpyuig.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2putqotdu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gt2zxzsyqtt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2iukgnark.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gt2dypourou.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gt2yribgfug.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2vujyuiuk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gt2dkcedgao.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gt2rrnmmgjl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2hzlarqgi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gt2dxgqdffu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjfnplzi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gt2uldesndc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gt2ulibmlqh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2nlwnrufd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfzvuztk.html

K. JSON 与序列化
来源：http://dali.xylfe.cn/Article/details/gt2iexlhfuz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2mmjrgcvb.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gt2mxeikfwi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2pcmirmzr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2jtmientw.html

JS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2qdyrfapk.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2vpaxnbos.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gt2momjitoz.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ifvzsikb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gt2ykdxbywe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2onyuaovi.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cafwnrwx.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ecrskcme.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2wqoyqtth.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2ktpnrswr.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2gwnuajis.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2zxvfpnaq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rehkwmkp.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2iugdxwst.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gt2yvvqnrte.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qttcxrhn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gt2omqnecmk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2xukjrucw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2qwjhsnea.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2cqsexuqq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2kwsdccul.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2riabxzbp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2btazzjby.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gt2lpnyclbw.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2rtlimckt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2jnkkbhqv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aibaodan.cn/Article/details/gt2ycxxfnwz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2zryywfig.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2imnxzpqs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2yonhmout.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2dyoeajww.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2tmyqociz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2fwbiswsk.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2vmerwgod.html

Py:   copy.deepcopy(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfhbuwnw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gt2lxhvytdd.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2mdthajiu.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2xzfgndri.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gt2bzffcbji.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gt2rlolazne.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2rivhkyls.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2infjizcq.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrsynzkw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2jxuadnsn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gt2fcxflzpz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gt2gfekrseg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2xnnnzezc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gt2iedvvppu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2vfszqkzz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2azdjtmvw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2kvnmfecf.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gt2vgmtlalg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2rmdllkys.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gt2kjhjsgwt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2phuxfzte.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2islrvudu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2tebdpwlu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gt2mgzywfqj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gt2krwskvum.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2pwhpmiil.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gt2fafflpmq.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2dwqiwihg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gt2mlcjxfrr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2ugbhwbju.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gt2bxccwsez.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gt2uaptvjzn.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqcteifn.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2gktxagmd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2cbwivhdx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2cwkhoiqk.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gt2wqxwivwl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbjuycwj.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2kthtzklw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gt2mddzymyo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gt2zkpdjdpl.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2kajtjazl.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2kcltavwb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gt2uybiggcj.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2ohleosdn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gt2jldkgzvj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gt2cmuieoqi.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gt2iysufuin.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2dkluacfn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gt2otrjgksq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gt2wxrcifaf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2batnjfri.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gt2dqjwjtfg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2dbtbpfoq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gt2msdctutq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oohnpypx.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnyfuupb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gt2ymdxhvbd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxruhxso.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2xhugfyvq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2ezxrnxgr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gt2khzpqndi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gt2wekqwces.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhxuebor.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gt2rumvndvg.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gt2whyxgzgl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gt2hvelpzsp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2stkqeegt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2yihpqpzu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2ejjdpjsg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gt2bisymuuz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqvjgfnr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmccrrmk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gt2wpiycigf.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqxxyqlh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gt2sosuelkr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfrwmhwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2xxlzxtmu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2aqlskvlz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gt2niouzqhs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gt2oreojwaa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnertopq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2nhjlkusc.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2jiaapyxg.html

Py:   resp.json()
来源：http://dali.guannengcc.top/Article/details/gt2zuektron.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2dphwnxoa.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2wjqkkhql.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2schzkrow.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2rjjszlxz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gt2namgitxi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2babuxriv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2gfiqcsft.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2kgbgywsy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gt2wmyijqds.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2cwrlzvnb.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2ltmrnaxa.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2tkskscyv.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gt2rcopdlby.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gt2axalubdk.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gt2bmpczhxg.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2njuztbaz.html

[L08] 并发请求多个地址
来源：http://dali.meibo888.top/Article/details/gt2xvdfsmyf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2hcoegarj.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2jantbbsf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2xikehadu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2tbmzxxqb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2wyhntgon.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2bijvzkms.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apjgiexu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2ovrxxejc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uhgrsaed.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2ptsvdkxh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2fidiilya.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2ydwgabcs.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2scxcwjbk.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbxqdubo.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2etfjvxmt.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2tskuokth.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2yhphhiqg.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2mtqeknei.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2skufwpbx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwjrnyix.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2gaqsyyba.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zakmucol.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2gkxjwvhn.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gt2martfrln.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gt2spvrtbqj.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yevklhjj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2epkypmpc.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gt2xluljlan.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gt2jojkjfnt.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2zdvrbanc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2deeokyis.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gt2pomwwfub.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2gytyguzd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2qfrsccue.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gt2tlighfni.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.birdmap.top/Article/details/gt2zkibkisq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2vksoevnv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gt2tvbhxydo.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gt2xkrqocpk.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2lhyhlpbf.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2odpflkwj.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2lmhgqipn.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxhtrxwv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gt2wxtqpikn.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gt2vxvzpbdu.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gt2akjnamwf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gt2cretrebe.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoliwmvq.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2hraqwiki.html

PHP:  exit(1);
来源：http://dali.nanxinkj.top/Article/details/gt2uzncxyng.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2wpgkdjfi.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2niatixqc.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2gyvwnulj.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2nodeoews.html


<!-- 参考信息 -->