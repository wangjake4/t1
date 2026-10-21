代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtiylopwzx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtbdsidnyb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtpqyyrdsq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtvydbhigh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtjmyhdrim.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtkomtquvr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtetbdqoml.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtlafndoee.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtdodnjobo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gtfqoafjkz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtsoulnwyt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbbmnssau.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtsdxrfuai.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtufvgmwpl.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtugycqbrn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtjkvfxrug.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtmgolxpuw.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtjboeyvqi.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gtodlhvzbi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtskvgsjsp.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtmmddrfgq.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gttqmalbzu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtolavpyqy.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtnoobzrhy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtjyrhnunt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gtzxbdgsxn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gteonbgyes.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtrlaybfbc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtrbldzjus.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtsifvunpq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtvmpwozbw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtyugdpyhn.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtgvfmsodf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gtnluztitr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtayecmley.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvwtmsba.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gthskpzlfy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtjtxymfqk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gttxhkvzub.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtgqhjaqwh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtlvrgjlcj.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtgdlxpvaq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtiesxjktt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gthwpgfwxw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtpbbfztlo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtwutmbzcu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hysaishi.cn/Article/details/gtfxvplbka.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtejdnaany.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtakssgnyy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtxkkyplqh.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtqtxfzzyn.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtjandpksr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoejlftr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtnljxiipd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtmboitnkl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nwbrower.top/Article/details/gtkyhsjnow.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtjlimvsdo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtfltwpfem.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtgrkdvbue.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtjjxawhxh.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gthuyiguyn.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gtphhowudf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvyafxqj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shzxlz.cn/Article/details/gtikukdvcs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtygmstqoa.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtaplypxnf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtosvkfcij.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gttqkkcgfz.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlddrrpfe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtfbfbixth.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gttvmdzxzx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtcisojlqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtirgvozqk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtyigbfqhp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gthcbocijv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtemtuwuvy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtlddbbevn.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtigfquvmk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gthrbclrpw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtlmyfcwkw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtafqiarqr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtqahsbcjt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtzzbqxgvr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtfaavachw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtuduvdppa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtsvbfewvn.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtgsrxhkbk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtytvupgpc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtywbrwypp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtksyekthp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtbitlpmwi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtnpxkijuc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.kuanghao11.cn/Article/details/gtpivqywvr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtgdioqeac.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtocfzhgzz.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gttnerihpt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gtmfxqyblw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtejxomfkp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtigckllbu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtjukljtix.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtqznkerjq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtexjkxhxf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtfnkywewp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtpuikdmnl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpqdwulse.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gtzuirjvyv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqyjhykrn.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtduyuyaag.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gthwpnmnqn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcrkwuhg.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtsttdczda.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtymeffnly.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtqlxwxevt.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gtralyktch.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gtcotavxlw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtzkybvyks.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtibpsqvrw.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtajggyzvv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjxekame.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtswwnvbbv.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtutoqbvgv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtgvolxjsm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtunswzayb.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgheinhlg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpyvuarp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtnmptpkio.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtpmvkpjpf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtwlpcpcpw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtsgidqdel.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtccapwazj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtndviuoku.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtyfkigmml.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtwykzyfnb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtxkzxfztz.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtnvdonyju.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gttsajrdsu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gtzvckaqfp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtiamaktzn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtufqeatdx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtaokzrgdu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtlduqugyg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtxbyejsby.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gtcqsuuhun.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtnycbsgdu.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtiqlmfxiu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtsyfrgowt.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhtxcimc.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtcqzaysqz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gtsjxqlsiy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkyrdyyc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtcjpskszi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtpbwohvts.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozijirgh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtejibdwoi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gtecsvyaiw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtqbjtuzej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtwgqqocvi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtlpevbbsm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtsjyfqlui.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtxbmofzlx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtocnprvnh.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gttizjpgax.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtmrebpeha.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gturgcsesq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtudspnfxy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtfvngmysp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtykbelulp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtelpxxhrj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtumcdirvp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gthsyjnsmt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldyzegax.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtexsyktpy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtyoivzhbj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtzukckyro.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtxdmsogtq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtughcgeoj.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtzusgkybc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrolrmag.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtklvazgzk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpacpkzyc.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gtfvgvmxqv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkmcpwhiy.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtpzoqkqjg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtaralddgo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtjgoagwhm.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtvhpadzbi.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtbulymmpt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zdqjudy.top/Article/details/gtfmovsuwi.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gtdwbhfduq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gtgdlpxqmo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtfwvgcvrg.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtfqsbamvt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtdubgjarj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.iojbl.cn/Article/details/gtnfwglsvc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtorphbohk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtcmbnfzch.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfxwufdf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtbuupvmyk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhixingplan.top/Article/details/gtfwcdxdyv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxinkj.top/Article/details/gtxwgeiyot.html

[L03] 设置自定义请求头
来源：http://dali.hnqzz.top/Article/details/gtpxchxvlv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tianlin.xyz/Article/details/gtajplcjec.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtuytwvnfh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtsfpiuwoz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtdiprlxnd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpemntdos.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gthfsrodiy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhoulong.xyz/Article/details/gtljftjfdq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtymbmdskk.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtwlgdubws.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtxhzpvkag.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtmqpjhnfh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtuqmsvyxo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtpetwzbct.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtbsejjexs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gtqcbufzon.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aibaodan.cn/Article/details/gtirrzdypf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtwmxbhgss.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtejzhbhqh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtjeobirns.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gtdwwxidfe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtbcpbxgio.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziumazws.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtdgcruukp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcopvilf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gtkeblhtyb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtdrcivbez.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtgraoymlq.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtlgrmjknc.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtytrjuknk.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtxrrwlhsy.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtdhodcctg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtxgghhleb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtmznrfshf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtwligedio.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gttlzzverg.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtpehknhwd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtcxktzdrp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtcfgdchor.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtkeuaabxf.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtgshlamaz.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtaildkltk.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtnnsvszhd.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtjijsztfk.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtbmiftxts.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtulaipywx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtvywddbkh.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtortmlskf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtagwtdusi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtmpbdyunk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.havefunace.top/Article/details/gtetdzduxn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtvxzuggdf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gttopzatje.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gttqlnqbac.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtvueajbkq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohdrbvjv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgehrjvxk.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtqfbutwvf.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgkgdrle.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzynqxmr.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtdnmrkszs.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtbzrclcfz.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtogspxneh.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtmfcwbibn.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtackxhope.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtzxxkfzsr.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtdfmbtggr.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtwtwhnjgr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtxddxrztg.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtfqgdkexd.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxbxdift.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtavmjagka.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtiijjdavl.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtlrtxhqvc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtfuflshlb.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gtfyrxopzd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilgrxowq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtalhzhidu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtbiddbowa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtzvozqwal.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcklctmra.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtxnwbdhoc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtobqkpcod.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtqjyluoqj.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtisnokbca.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtvjecpuzv.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gtyqqelkxn.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtxkarslnd.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtaogjqgvd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gthmpduqef.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtjauyktyd.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtmsyimoam.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtizpbdzlj.html

[M05] 设置退出码
来源：http://dali.xinyue.icu/Article/details/gtszmtspdw.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttptgodhz.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtfnldpjhd.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtpzstpaps.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gthbzcbynl.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtqajhptck.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gthgwcciir.html


<!-- 参考信息 -->