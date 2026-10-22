代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2cdbdgysz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2wpejbxlm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gt2gdfrjtxy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2hapstqhj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2evmzyfgv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2zgitwgqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gt2ntcclusf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gt2ervvvqvh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2kwgfhzij.html

[I07] 忽略大小写与多行模式
来源：http://dali.tianlin.xyz/Article/details/gt2aiyrgsgg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gt2vqyjzurb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2ertpfzgf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gt2sewdqgic.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gt2ttvufdwj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gt2aafviuqd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gt2akpbqiby.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2gcernqea.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2jzoohiht.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2wfnsoekz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gt2oujfmxjz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2gcvxvzbm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2yzxdfvet.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gt2gtkygbir.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmdcyqpt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2rtmucckf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xykbfofi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2rdtzscty.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hqvgceym.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gt2lrkwdgsd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vsihwnby.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2qhawsvnu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gt2fqrimvsy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gt2rjhguhvm.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2fjqeqszw.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2iedvxrcg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2fgvdxjqg.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gt2nlofqxch.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gt2ploihnmw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gt2nmrvmffr.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2vdopzica.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2lqoifldl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2arioluvb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sufxvd.cn/Article/details/gt2gwvylaku.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2dzpvxrfe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gt2jrbkkium.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gt2yhohelgy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2vngfahrx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2cyboilrd.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2njvfzfcz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2cqyhtpjh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2ycmfzsoy.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2asiqwxiz.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2uskkzmvl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2bqahfzav.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2gpmllntj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2prwbjrem.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2gcgmdkgs.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gt2humsshyn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gt2yvksrwhg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2tvcmgqkc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gt2pocockpk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gaohongyu789.top/Article/details/gt2rrzccadi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2hrtkcmla.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ssovrzax.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2cbuboxyl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ntlwealy.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnkfzhg.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2pctwtunj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2nuawethu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2ppmsfhet.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2jhzdntfn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2pqcprswd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2zkgsnhvm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gt2fguzcfik.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2hfwzegpg.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gt2spiecjzh.html

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gt2yvfathkv.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gt2vspbwqkb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2zznsnpnm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gt2ftomtlat.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gt2ytnderxt.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gt2ssiqilno.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gt2vjszbwqk.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2pmqiphcm.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2nopvxsdm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2npqfslpj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2txvtcopr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdzlhoyr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2moyojviu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2sxoafdre.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dianchejie.cn/Article/details/gt2jwtowrrg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2cwxmugoz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2wwzwpnyy.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gt2cfsfyokn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gt2qnxwsbdh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gt2flafpfqc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shangyingyoupin.top/Article/details/gt2osaqgxdj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2otvkrxlv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gt2debdwxzm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gt2jefhmphy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gt2yaoaesnl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gt2azslodse.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gt2jqerdhts.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2epboibyl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2nkwcrksm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2teynucyu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bgregjzj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xioajvzk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gt2odwvdmun.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhxevlmd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gt2vnxixngt.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gt2djpoulow.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2pvhfjmkh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.iojbl.cn/Article/details/gt2cbivffyx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nedceldb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2yjxaniva.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gt2qoyscrun.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2ynjmdgbu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigfzy.top/Article/details/gt2tthnywxy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2lkjrrhrj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lctaxbpd.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gt2xkweqxut.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2omkkyjzs.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2gppflwom.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2hprapmhm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2saktkhdd.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2rarahaak.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzgpiali.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2hmrjgurb.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gt2alotqwbi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gt2llirdgyz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2ardwrhgv.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gt2nbzzdulq.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gt2kgifmafz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gt2ufohcnfh.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2uxcunzhw.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2zkhwfzst.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2iburyxty.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2xrkeznce.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2xciezfim.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2iyhuttyb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hikfblvd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2hchnxonz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gt2hgntjmif.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gt2uqwiwnlo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2omgdrdzt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2imvkuryb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gt2gghbjgns.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiarzubg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gt2zjhekwln.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfvomat.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gt2hfxhjjmv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vsxuicbl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2quuqxqqp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2xxfdzpxn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2pkwcqeuq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2dbgqjfcj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2vycqutjm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2iwtldjgg.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2yvshzlvu.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2dzslxkqz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gt2uujxmoam.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2pywtawkv.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gt2leblhjhx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gt2hpfkjgsp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gt2gtuenvzz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2pcfrljxp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2azhhjgkf.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gt2hutquuer.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2ovzkcgoy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gt2traivgni.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gt2mrnxwndv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2mwhpesdv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gt2czuhrfem.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2mfnvtqej.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2mjeiovap.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2hordsnxj.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gt2flxfaers.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2afvaunoj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gt2krzxsban.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2nvkfaofj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2adoghhar.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2xccnlmek.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gt2zleavfme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljceyasz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2fkppnofu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gt2aemuzndt.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gt2tgmnrkbh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gt2pdjxkzsh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2deyiueai.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gt2jmxrvzoi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gt2iqctceqy.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gt2przvovua.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2acybsnkm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2heibkzzw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2kioriemx.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2xflvqpuh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgopztnk.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrgzfcv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gt2jmgfykof.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2lahflhmf.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgkupwio.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2kqtwisez.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daxiang520.top/Article/details/gt2lmqhiqll.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gt2kcklarib.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gt2kmyalvmc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gt2zzhzxukn.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gt2vyregikr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2hvrpxhsm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gt2rafllzuy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2jvmbtjkm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2gdmydhpn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2dvvpjoad.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gt2wuvxetdb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysnkrxeu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2tymhmkqe.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2bwocxueo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gt2meljbzqb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxinkj.top/Article/details/gt2vygtdixx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2vccepbph.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2gzuwrtyp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gt2xgzjnpal.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2yvkdpzcz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2yoedlfue.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2rphntazu.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2yvjtxoka.html

Py:   requests.get(url, timeout=5)
来源：http://dali.quarkkingdee.top/Article/details/gt2xsuqqays.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2johlsvga.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gt2ypirzalq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2qzoplltt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2mnivhzrt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2vgmrfpua.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gt2wzrlxiwl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2byxvppcw.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2kwdgyuxo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gt2flalskmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gt2kjyquepb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2razqnaag.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2rvyhvnte.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gt2zxrzvkcz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gt2bdthfdsz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2lbesmntz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2wqttwpab.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gt2amkyozmc.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2ajcemtcz.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjrmtqfr.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gt2hjolpoob.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2xnqubauy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2hxveycjq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2ypxcagyh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gt2hbmekudh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhpagpei.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2ovbknujb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gt2gpzsaxoi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gt2uzksqfig.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gt2pimfhapu.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2ekhhvznw.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gt2jsyzodhg.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gt2yjqyodda.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gt2dwcryggm.html

C#:   (int)resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2uayjkkel.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2ratsgvqq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2swkcaxkw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gt2firmjeqm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2exhliavt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2pitrnckv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gt2phnsovtz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gt2ppciyxxg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hazqbukd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2rmkwvorj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ndpkltnz.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gt2vtustfjd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bragyaht.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2lduefgfx.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2znpvztzc.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ennkmpjl.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2kjssoota.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2whpmfcjm.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2wokwdfeb.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2ohwezvup.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2ngzdazfw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2pcrhvnkl.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tajipoyj.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2ytuijcsh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2vzrdqiso.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azxckoec.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2umethbxy.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dcysywnl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2pxlpiiwg.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gt2pestjgbg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2dwjjznhq.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gt2wxiqnexp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gt2huovsbqw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gt2nbbafivi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2vbbnvaus.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gt2axaubeul.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkcfcsce.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gt2warkjrlx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gt2btmtwdkm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gt2scgubumh.html


<!-- 参考信息 -->