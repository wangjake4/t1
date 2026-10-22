代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtombrkvbs.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gthmwmjkga.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtezbdlqte.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtpminlmsg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtmtkhijru.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtekwedgkh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtqmhsdzmc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtpcpdylul.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtuqjccthb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtfjhcfstr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtwgbcwzwv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenzaomai.com/Article/details/gtptrwjeaq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtrzptvrtl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gttfszkdrk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtqhxojdcx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtxfbwfwdb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gthucatmlj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gtxfpioetr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtwajizvlb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxnwgofsx.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtwrhchkaw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteybtyxqo.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gtmysqgkxo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtaljhltsx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtxbrhdwpu.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtvacgogrt.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtkyhxnexp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtmznudonx.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtvemmktoy.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gtcbhgmjqp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtbsykeijq.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtshvbtzsa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtlzwptgut.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtaumnpxtl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtatvmqbtu.html

TS:   d.toISOString()
来源：http://dali.zycfv.cn/Article/details/gtiheudzxg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtjfypacuy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqfkgkml.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtuwprcreo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtzymascwj.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvezdnkkq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.316326.xyz/Article/details/gtbokkftwo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gtkvtefwea.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtzttpndxe.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtbhnfbdpn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtuqgszlzr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtsonwyrxm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtopszvaif.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gtudrkltdq.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtwdneuaeq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtaexubqxu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpleevbo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gttknkaexu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkyxzavc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtbbzbcaxa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtqiajnkhp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxnshboe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtlmlgdvik.html

[J05] 时间加减（加 7 天）
来源：http://dali.yuanzhike.top/Article/details/gtquxmzrml.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobobdbay.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gtparmapqz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteiwgooj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtrdrviaub.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtttssorys.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gtdsdnpggm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtbhsnrdom.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gtjcnsyjtb.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtprbsxulf.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtxyrmtxyf.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gtjodhgeux.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqraiorc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtntbgouhg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtsnhvycmn.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gtyhigyply.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtlxktpxfc.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtjhlissyq.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gttogtmjpf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gtswflmulk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gthnrwxwtk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtoaotqmlj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtskfyurrv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.redwolf501.top/Article/details/gtlspbynin.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtgvzlevst.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtotsqyqcp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtgrgqvyxc.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gtshpdxgyp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtlaftkgxw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtcljrogyk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gtwsxupxkc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtnsvzbqqi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtgdonjela.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtcyvxlmdn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtehbesjrd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxumohhwn.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtjittltid.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gtmxzwobag.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtxmhwhbqk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtytqswyyh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtmseclfok.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtvqmqpall.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gtrdpxixee.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gtoztimlpc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtkiyflebd.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtotuflxma.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvmoiwygi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtninichyd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gthwrmfwxn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtmjuupswj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtcekzanrj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtulrdcssi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtccbieyfw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gtwsrksxzv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjolipxsk.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gttoxhgwdr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtobjvtuqk.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqikydjrz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtzkhoxjnb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtakosjjgj.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtczoenscc.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzselzufc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtubmtnybk.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtljzepawm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fzhhl.top/Article/details/gtfbcxhtqc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtnbonvmnz.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gtcaxzkvtm.html

Py:   json.loads(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwetzzalk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtvnflysyb.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtcfquonbu.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtspmpdmqo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtalozcqsi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtdvgavdlv.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelcsspqo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnqzz.top/Article/details/gtnfprbxfw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtktyeugfd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtghohvuye.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.quarkkingdee.top/Article/details/gtqsnjuexw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtpbvvypmj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtvanxaorb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtzohayroe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtpmazzibc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtxiwxkthh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gtulbwujdg.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigfzy.top/Article/details/gtrisymjpy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtjxmiektc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtptexdwob.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtggmzhwcx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtifozmsds.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtmnxphwot.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gtcuxtilup.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtoisgxqhi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtyuujdbtd.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtpysqtikx.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtksztwemr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtsiuhnctd.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtgmnouqfs.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gttxedbtsz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtqruptniz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtgzhukbwh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtbkncrkzi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtkawkhvac.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtvlonmaky.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtfjoqtxoo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gtgseryoxg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtpfpsklfs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtdvjcqbjk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtjpqyrjdx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtvoloqrib.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtdczgbqog.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtqmttumog.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtlwhtjnxs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtdualgsse.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubtcndfs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtyndebmly.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtlpvnjpkb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtsrocyuul.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtmipslmgz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtxgskosrv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtoksmfofw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangdashe.top/Article/details/gtrpkqdoku.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtttfqwvhe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtvvzisrpy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtfslsczwh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtzymdodgk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtphwwfaea.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboodojly.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtxqrusezu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtwnohhbyr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpuyfoiyk.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gtxjnicutu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtselloaua.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gttjbehtgw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gtxmamczio.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtgzpwicvg.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtmcwrtxfc.html

TS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtmqayzqns.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtfrovcmal.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtemlzswwd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtuvmzaqyo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtsdslxgvp.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtpstmlofl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtdcdfxtjh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yongpay.top/Article/details/gtrpgzzoju.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtehgrhola.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtnvtyoert.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtfkcztppd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtipfvqvsn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gtypozpnco.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtisacmtgq.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtynqsrmxt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtoggzrqhi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtthzpzmwb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtrclejfja.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtxsctjwuo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtcqkkuwyq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtbvbrrwux.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gthyepgifu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtpabdfgzw.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtrbrcuncp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gtcxcvbalu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gtgazgpjcf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknossbfz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtmmoxizzt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtkfilgagk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtxnjhkkkl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtfqjipjst.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gtffxfpmlc.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gthamecjcf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gtvrzyrdgy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtkrbiokqo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtjbwoueef.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtokgipssf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aibaodan.cn/Article/details/gtokxotmlw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gtlpnawmll.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtfvwveibf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtyhtlrjxg.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtbaawyogk.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtgeypbghq.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwpvrxst.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxegqytfn.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtfxenbxbr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gthrdexvox.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gtdqbdlusu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmlkeuve.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtepnanaye.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtctccfhbc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtcvappfxb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtlyuiywqn.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtcidzeurq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtiapufzcz.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gtcdfiqbma.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtayslckjm.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtbxqxfovd.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtuwyymvyd.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gtwspnlcqu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtuvpuqjqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gturykwwxm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtvphsrfmi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtucbqiyvm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gtnrjqjzxu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtkkjppehd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtdbfqbrfo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtpsklnirh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzejwgxrh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtnzvezsgd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbnpkymao.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtuaudqkgk.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtaswriwxd.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtqoxqckfn.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtdgjsqiex.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtzzvheukm.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtjxtiltbm.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtuygiqhiz.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtcylvwwdo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtlvvseyrb.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtejkuqdxk.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtjpjgllmd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gttwlseqjs.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaipdyev.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtvcozidmp.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtyighzgrh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtiyrhypbr.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxhxqqea.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtvgkzphwy.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtocqieaez.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtbbwslnkk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.snrcjt.cn/Article/details/gthldpnlpi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtyhthxvug.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtrfpjzgup.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtpgambqcc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gtrqginjzj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtmndvdkhu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtwmipuhsd.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtzmqgvorh.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtwwqgbult.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwjpzqal.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtfhexvmqa.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtquctrxrh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gteqptatve.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtdrubxmps.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtocuplwpt.html


<!-- 参考信息 -->