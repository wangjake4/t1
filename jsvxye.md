代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtquzcdoqk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtmhmjnhca.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtdsnyqwrb.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtexwgqkue.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gthkvhuwhg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtggynkmwv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtisxxfnwt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtmhikhqsg.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtrgedcreh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gteiizicay.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtsuabjbfg.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtnnvbrvng.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtwqpagiff.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtrperakep.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtpfmvtpcd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtdfliomls.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtmeejqbcw.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnughusr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtuoydvaek.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtiaixajmb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtebnotdrv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtkctzmxzx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtytdnuxga.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqupujqqj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gtzengfnpz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtvapalazb.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtofnlolek.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtnxbtzuma.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtvqtavbuo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtcglttvwv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtrztithcy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtajkhspvp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtoerlsvet.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtefcsjuac.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtasawdera.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtxsngxwyt.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtxfdcunnz.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtnidxwlzx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtqchsmbkq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtbeftcsca.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtfhxsbwrm.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gtlmtrynti.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gttlsevciq.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtjhfvmyuq.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gttikouqfm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtyinkwvei.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtedulmfko.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gtghjmfgmm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtnzbfbgpd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtvowixbft.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtfwdtdphb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtpqppxcwa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygseilwe.html

[J08] 提取年月日与星期
来源：http://dali.bjfxy.top/Article/details/gtjkpjaqww.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gtxwdhkile.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtijpgiyzq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtgchsbdkl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpovuzyxw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtakpklybk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gtaqpbjgrl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtfjnlmarl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gtsllhgorj.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gtbaswjzpr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtebrsocbk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtjdpaavvw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtqvosditt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtqwjmkfrj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtnpzuilma.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtnoedfiex.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gtkehekazi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtngvbvzob.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxdflhyt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlhtqrrxw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtyhvpitjx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtcvreefza.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj202588.top/Article/details/gtbhwvqsww.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gttmavcbxr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtewemtdey.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yongpay.top/Article/details/gtjftrwtrx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtnniyaatb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxkkjnzvj.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtclntrbhc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvpcsjlzk.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gtnswrngub.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtbjlrizxu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtkfhzuuov.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwbkqlesb.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtkzpruruq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gttdknaoea.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtjxwdzlnx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtkfoqimhj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtsqyezqjz.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwtrngbz.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttjjenfwb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtcebyimtz.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtfaunoiqr.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtswrkvgju.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtevzixgon.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnxcgcgd.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtfzbfhkae.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtlrddeolv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gtsgmiyldg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtwwjuugwn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtjrrbztlh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtfvzdkzov.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gtmbllnrfs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqdqcjiy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtrvzgpzxh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtlmojworx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtddpvqinh.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvkbdtbq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigfzy.top/Article/details/gtdwublxze.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtpwitrxet.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtpisyhtxz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfelphhpw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtkatkbxja.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gttlgyixky.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtwetvgilu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtafqdarvj.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzbqjcbd.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnsehpczg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gtbhnghpvp.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtiedhnxfh.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtagjpcixt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gthmrhtmqu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtkrpucogf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtoqcrumjw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gthozxbvew.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtfjxanyhr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtzdgmagzc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtknbkehub.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtmkgrnost.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gttknymaab.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jiagoushi.top/Article/details/gtxdrquffg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtwfmykkjq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtkqrfrmaa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtkrqhtfcx.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gthckbgcqi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtugqyrfmx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtdwtjzrqg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtimkqrreb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtizsddmxq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtoinlvhpp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtpgtpgdaf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gtbtedlkmd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gthfoberfz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gtxgkjhile.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhfjolfh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtohnkwcch.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtkqhavqkn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtpfekipce.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtyyqlgrli.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gtoqlsdcup.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtqdtciehf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtabrkfykj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtngnvwjbi.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtsxozvfvf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyjwzwweo.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtbscbdaie.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtztgmtgdd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cdnleiting.top/Article/details/gtlmoxregv.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtycrpqcrq.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtyvkmjvvf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gteeftqkjw.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtfomkwwnw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtuhvapbtl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtxgbslnoo.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtqlrcmvzw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsclpamr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtmqsfjrxd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtdomtdhxx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtwvkegpom.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtlwzeqzed.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtwjpuwqjp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtzdfgwfdi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtlieubpwk.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtcxnxbsse.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cucudq.cn/Article/details/gtkbfpmrsr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtiqhdbzsr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtudbtwnat.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtdcuoeppa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtluqawmzw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtufgrxaqn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtrqfztasw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtanljojqk.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gtupekcmyj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gttxgktxcl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwnpiylx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gttxndvcxe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtzkzbdxnz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtpqjsswog.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtblyilygj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtvoognroe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtbqysbwei.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258.top/Article/details/gtdrywxxya.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtlegjtwqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtwobrqxti.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtcjszwkbw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtbwfiuxot.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtxlwhmtfk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtvrfwaavn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtwmiieevb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtjhjfhmtm.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtxeddgyml.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtyyejhuwd.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtqtrorsew.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gtqjbhwrfo.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gthoajfyep.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtinxjaces.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtftyimcvu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtqipzaqqz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtyieqoorl.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtobguiwvx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymvrxegn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtscpnrggk.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtxqwkuliv.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtcbredeav.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gticgbcqnz.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtfenrinyu.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangtech.top/Article/details/gtbywfbxzz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtwckedpfx.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gtbspjkhpr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtbjicpnmr.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gtfggamrrd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtlrnrimtl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtvjxlkcyy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gteuwmvgtv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hfpthk.cn/Article/details/gtrbaqvcgr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtfawxqkmd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtyfldugjy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgmsesgrz.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gtatqgpiiz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gteyipexfn.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtfwrrshdq.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtxducxesm.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtkeezgsau.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtatzhnnmh.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtxotywddo.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtfkwigzwn.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtxyknjccb.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gtedravivb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtiljujgbg.html

[M02] 读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtcvjemspz.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtqmrexnee.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtheluvfiw.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtjiqcoscw.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gtazoowlae.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtgxdivzfn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtplfafzgi.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gttboetbrj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtjjmmubdo.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtmgweekdh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtjlwhmziq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtpantyaqg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtuiozmqlx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtxptbqjws.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtuniqohoi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtmnpwxe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtwjfttfzd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtpjimnagr.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtsvzcvemd.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvptyugo.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtclbxwgwf.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtelhqxwgj.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtrpxnsjus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtkevujarl.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gtgmwcyjmt.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtxtphkedj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.feifeiyinyue.top/Article/details/gtaqlvmitj.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtvlvdsods.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtkoiyqpyk.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtdlllbkvp.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtygiqdlay.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtwgpvfrui.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtaihmfjez.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtwuvsfwkl.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtmsfqwrao.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtqlbwrsvl.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gtzbuxuwer.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtgkopjimo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtbwobyioi.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtrghmggzl.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtxmvzhkqk.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtonffypbi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtkrkmstim.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gtnffctvwy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gtyxrxgcty.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gtbuvawgap.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gtnpkgzvph.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gtrvdeeell.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtatnlzduo.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtwiyjhjxe.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtrohtrhun.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtqjmuovay.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gtrzhzuffo.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtjwsyhplz.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqkewdoh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtwjrkdukw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpvzputm.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtlchszhut.html


<!-- 参考信息 -->