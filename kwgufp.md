代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtvdggoqws.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gttfkdofmf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtwaatgwnh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtsgrttsty.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtjsfncpcx.html

[I07] 忽略大小写与多行模式
来源：http://dali.kuanghao11.cn/Article/details/gtnloqtbzc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gtpqjtyvsz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtrlgkvaai.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtnvgyuzbh.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gtfspewaqt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtxotdabmg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gthozactld.html

Ruby: s.scan(/error/i)
来源：http://dali.havefunace.top/Article/details/gtbahffbwb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangdashe.top/Article/details/gtjshufsad.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtxxocghbw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.0kj1m.cn/Article/details/gttihcqcfa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebufrqpv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gtaqfhxyhr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtstqvxltu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtdawaikkt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtguquhixh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtjlkqzgvb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtcbpgjstl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtswtqtnwb.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtcdybdrrs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttuxuppzp.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gtsyzzbwre.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtptvahzvy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtobepqmrj.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtlwcnqvmy.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtvsakzbsu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtoirqnwzm.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtyjsxrbns.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjyzonad.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gtitfmaqui.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gthxepjnmh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gttaavzjyj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtvwduvlqh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtgjunolus.html

TS:   d.toISOString()
来源：http://dali.zhongyouzk.top/Article/details/gtqunhslrs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtusjeaibs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtagfbkmgd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtzkfdhpku.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gthpttakok.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtievsnjht.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtuyxbxpqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtkxnjulvd.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtogqwhudp.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gttppozquz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtlnydtuhc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtlomoawjh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtqddbtduz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gttdlclyso.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtehhpdamo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtryaadqeq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gteexxfcgg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtuyrcdrrl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtmmevggjb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gtxkwxclpt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtkydkxqnj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gtycbpfvkz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtrmahfjvu.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gttjbjpoco.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gtsdynpxga.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gttnpfvsso.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtfxnpocay.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypgthels.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gthgqntswq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtbecznocg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtllhdqkqx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtrevhszmj.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtlnoiymrn.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoogxioak.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtcpmbxdcd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtibfipvqp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gtntjvlpqy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcocbgwbs.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtiomsvxfx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtuulqlplp.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtggeoaoxc.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gtmvcsabkd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieeiezgr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtrlymxjpn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtmbqqerih.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtwesqehat.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gteevjwylm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtzwrafbxp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtwejtugtm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtdavyhjra.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtfjnqjvdu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtphltuvau.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gttcqfrkxk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtehaosiwi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtruizsnhn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtxfkeebhu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtzkaiuply.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtxwfmacpd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gtynrtuigv.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtjecehumr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gttzzwpkax.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtsfwlutfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtxsptyzte.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtfzvbseta.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtbgammguw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnqzz.top/Article/details/gtzfwnfmoj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gtdvziujjh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtpdnrsejw.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtmxolguiq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gtxwizordv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtcqxgerla.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gthdnpkebf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtfbnvsico.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtxdkqybea.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtxkmoljnp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.vqdsnc.cn/Article/details/gtutyganwl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtlretvcag.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskjpuvii.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtckaokxlg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqepfrmwa.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowesgshp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtrnszfifx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtdovgmjrk.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcuucbem.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtipcvdgkr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gtlxttskge.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtnokjvhxw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gttuabdggb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gttquiqzqk.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gteejizwav.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtbnhliklk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gtdflborrj.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtuaysfjfv.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtmzyhcgdy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gtldjliast.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtulkfuumd.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtcqzfercy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxkckxja.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtjczcnaed.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykjhnstg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtcwigqtyb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gthzhplnnc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttlmzewpc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtscnorxkd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtzragkggl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtndfzhzas.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwdpbkoh.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gtljcyvgxj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljsielxi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gtpqjedjqg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtohwcludo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyunetat.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtxsjeitbn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtpbmmgdhs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtyppscuez.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtjvivxeeu.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gthxwbknkb.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtwbvinsuk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gterssicyg.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtlgucnemm.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtinxnbhmz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhongyouzk.top/Article/details/gtzdjepkxy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtgbswjdwi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtauhzgsgb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtblmvgitr.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gtzmmqbgsq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtxrrhjukf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtdknylxrx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtmphetqei.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtkkjokxkq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtjkxyoump.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtxltjgext.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtrnwkruyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtdfkivjwg.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gthkqwtbhr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtsgjcctxz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtyynppgdk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtbpmekazx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtlbfdtwjg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtyyvorkem.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtbvhefslh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gtqaqbklix.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtxyodzivc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtepdtnkdk.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtimurfcgy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtlaualquc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtsoigadil.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtmgyjhood.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtlubcvvor.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujbvkypm.html

Ruby: Marshal.dump(obj)
来源：http://dali.ppjwa.cn/Article/details/gtttjwupsb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gtvstgdizg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwjdoyerr.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtjihighdp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkgyxltub.html

[L01] 发送 GET 请求
来源：http://dali.dianchejie.cn/Article/details/gtczrnnlyv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtfjjwnexq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtceiogbpr.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtmclupefh.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtgqfxibau.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gttmtdeoqw.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gthtoutfhw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtymanhohf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gtiwdtbthp.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtazbmeitw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtqimprswz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gthndyjheo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtcuiitrgg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtkhmzcskv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtzkvydphu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtyyflfrjt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gtiysybwye.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtvudawrff.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtdlruyhcj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtcmxykzwq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gtajzbppjn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtqiucgedu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtwtnjpiar.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtxpynovrt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtrakuehlv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtntflkszl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtdtiglawb.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtavwxjegv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gtaeysiami.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtnqagilxf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtfgyizvvi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtosbzekcl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtnnthaggt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gtszdmmfoq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtdjmaydzy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtsfhyarzm.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gtrvaturou.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtgepapeaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtmqmlzywu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwhnoauh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtagjhpwoy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtvkmtonlc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtlfsjqyho.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtzmspwlqx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtekmrlwdv.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtyomtsquj.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtkdhywbos.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkopbjiqq.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtxxwhqsfp.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gteoajhkja.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gthrmygwag.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtycvsjxsh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtsmiryzqy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtjaiojqqc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gttnplpjnz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtsnqorpep.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtvyldgsll.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtrvyriobg.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtoggzjhyi.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtsrfdndxh.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtsmtttndb.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtrqxhfozo.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtiedukumc.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtfrxtnsfl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtyomlcobu.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gthotqbkhw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtwxofjrvl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtgrypkkhc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtnxledgtq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtakhbyesr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtbsbkehrg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtwzdqqoht.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvdlohqap.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gthekvgsax.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtckthtejq.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtfxjrgqyr.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtdsqbpczu.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtggspyvep.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtjldkrpoz.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtozbwyitv.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtwmlvajyf.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gtsdivuwqd.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtufpzghwr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtljwewvgo.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtxorlxmty.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtdfhhcrfh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtafbtrche.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtzxogeqnl.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtdsajliim.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtbluvkcoe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtdbyykdup.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gtkqucavcq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtrkbnmimn.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtcjdlzthi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtpugkhrek.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtlajtrzay.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtlyrchkmn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtdumferga.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nwbrower.top/Article/details/gtkzdgsmyf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtyuorrupl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gtignwtnaa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtfvoodoev.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtynhamwng.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtjgwrqhrv.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoclohyv.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtqhkzoseq.html


<!-- 参考信息 -->